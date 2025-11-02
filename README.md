# Pseudonimização e Anonimização de dados do Ei Truck

O diretório **`Pseudonimizacao-Anonimizacao-1ano`** reúne todos os materiais relacionados à etapa de **Inteligência Artificial do projeto Ei Truck**, incluindo códigos, memoriais descritivos, arquivos CSV e imagens geradas a partir da base de dados utilizada para o armazenamento dos dados anonimizados.

---

## Estrutura Geral

Além dos arquivos padrão do GitHub e do **arquivo de ambiente (.env)**, a pasta `Scripts_IA` está organizada em **quatro subpastas principais**:

| Pasta | Descrição |
|--------|------------|
| **Administrador/** | Scripts e dados referentes à tabela de administradores. |
| **Analista/** | Scripts e dados relacionados à tabela de analistas. |
| **Endereco/** | Scripts e dados vinculados à tabela de endereços. |
| **Memoriais/** | Documentos Word contendo os memoriais descritivos dos scripts e prompts utilizados. |

---

## Estrutura Interna das Pastas

As pastas **Administrador**, **Analista** e **Endereco** possuem a mesma estrutura interna:

| Item | Conteúdo |
|------|-----------|
| **Notebook_nome_tabela.ipynb** | Script principal em Jupyter Notebook com a lógica de anonimização/pseudonimização. |
| **/csv/** | Contém dois arquivos CSV — um com os dados originais e outro com os dados pseudonimizados (ambos no `.gitignore`). |
| **/Saidas_Banco/** | Capturas de tela mostrando a saída do banco de dados com os resultados do processo. |

A pasta **Memoriais/** contém três documentos Word:

- *Memorial de Prompt*  
- *Memorial de Script*  
- *Memorial Extra de Criptografia*  

---

## Dados Originais e Verificação

Existe também a pasta **`Dados_Originais/`**, incluída no `.gitignore` e enviada **somente à professora** para conferência dos dados.  
Essa pasta contém:

- O **script SQL de entrada**, utilizado no processo de *dataload*;  
- Os mesmos arquivos CSV originais (presentes no `.gitignore`), servindo como atalho para conferência e verificação.

---

## Visualização dos Resultados

Para facilitar a validação dos dados anonimizados e pseudonimizados:

- Todos os notebooks do repositório exibem, ao final da execução, **os displays com as tabelas resultantes** diretamente na interface do Jupyter.  
- Isso permite que qualquer pessoa visualize os dados processados sem a necessidade de abrir os arquivos CSV manualmente.

---

## Observações Finais

- Certifique-se de possuir as dependências do Python instaladas (pandas, numpy, faker, etc.).  
- Configure o arquivo `.env` com as variáveis de ambiente necessárias para conexão com o banco de dados, caso o notebook dependa de acesso externo.  
- Todos os dados sensíveis foram tratados conforme as diretrizes de **anonimização e pseudonimização de dados pessoais** definidas pelo grupo Ei Truck.

---

## Autores

Equipe **Ei Truck**  
Desenvolvido como parte do **projeto interdisciplinar de análise e automação de telemetria de transportes**.
