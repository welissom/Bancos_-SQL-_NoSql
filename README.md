# Bancos_-SQL-_NoSql
o papel do bancos de dados relarionais(SQL) e Não Relacionais(NoSQL)

Banco de Dados Relacional(SQL) - É um tipo de banco de dados que armazena e fornece acesso a pontos de dados relacionados entre si.
"Nós sabemos de fato o que vamos armazenar"

Em um banco de dados relacional, cada linha na tabela é um registro com uma ID exclusiva chamada chave. As colunas da tabela contêm atributos dos dados e cada registro geralmente tem um valor para cada atributo, facilitando o estabelecimento das relações entre os pontos de dados.

Quatro propriedades cruciais definem transações de banco de dados relacional: atomicidade, consistência, isolamento e durabilidade; em geral, denominadas ACID.

- A atomicidade define todos os elementos que compõem uma transação completa do banco de dados.
- A consistência define as regras para manter os pontos de dados em um estado correto após uma transação.
- O isolamento mantém o efeito de uma transação invisível para outras pessoas até ser confirmada, para evitar confusão.
- A durabilidade garante que as alterações de dados se tornem permanentes quando a transação for confirmada.

Banco de Dados Relacional(NoSQL) - É um banco de dados que não usa o esquema de tabela de linhas e colunas encontrado na maioria dos sistemas de banco de dados tradicionais. Em vez disso, os bancos de dados não relacionais usam um modelo de armazenamento otimizado para os requisitos específicos do tipo de dados que está sendo armazenado.

Armazenamentos de dados de documentos - Um armazenamento de dados de documento gerencia um conjunto de campos de cadeia de caracteres nomeados e valores de dados de objeto em uma entidade conhecida como documento. Normalmente, esses repositórios de dados armazenam dados na forma de documentos JSON. Cada valor de campo pode ser um item escalar, como um número ou um elemento composto, como uma lista ou uma coleção de pai-filho.

- exemplo de Banco NoSQL relacionado a documento - MongoDB e Azure Cosmos DB

Armazenamentos de dados de colunas - Um armazenamento de dados de colunas ou de família de colunas organiza os dados em colunas e linhas. Em sua forma mais simples, um armazenamento de dados de família de colunas pode parecer muito semelhante a um banco de dados relacional, pelo menos conceitualmente.

- exemplo de Banco NoSQL relacionado em colunas - Cassandra DB, HBase

Armazenamentos de dados de chave/valor - Um armazenamento de valor/chave é essencialmente uma tabela de hash grande. Você associa cada valor de dados a uma chave exclusiva e o armazenamento de valor/chave usa essa chave para armazenar os dados, utilizando uma função de hash apropriada. A função de hash é selecionada para fornecer uma distribuição uniforme de chaves de hash em todo o armazenamento de dados.

- exemplo de Banco NoSQL relacionado em chave/valor - Redis

Armazenamentos de dados de grafos - Um armazenamento de dados de gráficos armazena dois tipos de informações: nós e bordas. Nós representam entidades e bordas especificam as relações entre essas entidades. Ambos os nós e as bordas podem ter propriedades que fornecem informações sobre esse nó ou borda, semelhante às colunas em uma tabela. As bordas também podem ter uma direção indicando a natureza do relacionamento.

- exemplo de Banco NoSQL relacionado em grafos - Neo4j, Cosmos DB

Armazenamentos de dados de objetos - Os armazenamentos de dados de objetos são otimizados para armazenar e recuperar grandes objetos binários ou blobs como imagens, arquivos de texto, fluxos de áudio e vídeo, grandes documentos e objetos de dados de aplicativos e imagens de disco de máquina virtual. Um objeto consiste nos dados armazenados, em alguns metadados e uma ID exclusiva para acessar o objeto.

- exemplo de Banco NoSQL relacionado em objetos - Azure Data Lake
