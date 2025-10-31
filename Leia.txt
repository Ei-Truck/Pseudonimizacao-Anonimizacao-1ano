Organização das Entregas de IA
Na pasta Scripts_IA estão reunidos todos os materiais relacionados aos scripts do projeto, incluindo os códigos, memoriais descritivos, arquivos CSV e imagens contendo a saída do banco de dados utilizado para o armazenamento dos dados anonimizados.

Além dos arquivos padrão do GitHub e do arquivo de ambiente (.env), a pasta Scripts_IA é composta por quatro subpastas:

-Administrador

-Analista

-Endereco

-Memoriais

Cada uma dessas pastas, com exceção de “Memoriais”, corresponde a uma tabela do banco de dados do grupo, que contém informações sujeitas à anonimização.

Dentro de cada pasta (exceto “Memoriais”), encontram-se:

-Um notebook nomeado conforme a tabela (Notebook_nome_tabela.ipynb);

-Uma pasta contendo os arquivos CSV — um com os dados originais e outro com os dados pseudonimizados (ambos incluídos no .gitignore);

-Uma pasta com as capturas de tela da saída do banco de dados.

Adicionalmente, existe uma pasta chamada Dados_Originais, que está no .gitignore, porém também foi enviada à professora de forma particular para conferência dos dados. Essa pasta contém o script SQL de entrada (responsável pelo dataload utilizado nos scripts de saída) e os mesmos arquivos CSV que estão no .gitignore, servindo como um atalho para facilitar a verificação.

Ressalta-se que, para fins de conferência dos dados pseudonimizados, além dos arquivos CSV, os displays com os dados já pseudonimizados estão executados em todos os notebooks disponíveis no GitHub, permitindo a visualização direta dos resultados dentro dos próprios scripts.

Na pasta “Memoriais”, encontram-se três documentos Word:

-Memorial de Prompt;

-Memorial de Script;

-Memorial Extra de Criptografia.

Obrigada,
Ei Truck :)