# Desafio-de-projeto-DIO-O-Papel-dos-Bancos-de-Dados-SQL-e-NoSQL-na-Engenharia-de-Dados
 O Papel dos Bancos de Dados SQL e NoSQL na Engenharia de Dados

Resumo SQL x NoSQL

	Dentro de um modelo de dados relacional os dados são armazenados em suas respectivas tabelas de forma organizada e sem repetição onde para se obter os seus dados são necessários fazer as junções e transações , gerando produtos cartesianos entre as tabelas para recuperar os dados, gerando uma complexidade alta e cara em termos de processmaneto. Essas operações degradam a performance na obtenção dos dados para certas gravações de dados.

	Outro grande problema no quesito bando de dados relacional está relacionado a questão de infra estrutura onde o se tem defazer uma escalonamento vertical onde se tem a opção de atualizar ou comprar um hardware mais potente ou optar pelo escalonamento horizontal, onde se terá vários computadores com poder computacional menor em clusters, onde se tem um custo menor que um super computador, um crescimento menos limitador, uma alta confiabilidade devido ao fato de que se um deles der problema os outros continuam operando e também tem  a opção de contratar uma empresa de virtualização.
Os bancos de dados relacionais não foram projetados pra trabalharembem com clusters, embora tenha algumas alternativas mas tem um custo muito alto gerando um  problema para os banco de dados relacionais.

	Devido também ao alto volume de dados na internet os big data necessitavam de formas mais flexiveis de armazenamento de dados foi criado o NoSQL para suprir uma nova necessidade de armazenamento que os sistema de banco de dados relacional não conseguiam resolver, dentre esses problemas eles não utilizam modelo relacional geralmente de código aberto, tem uma boa execução em clusters e sua base de dados não tem um modelo pré-definido.

	Os banco de dados NOSQL se dividem em 2 classes principais de banco de dados:
- os BD orientado a agregados,que é um conjunto de objetos relacionados que desejamos tratar como uma unidade, que se dividem em modelo chave-valor(Riak, Redis), Modelo de documentos(MongDB, CouchDB) e modelo família de colunas(Casssandra, Apache HBase) - Os dados acessados aqui frequentemente sao mais importantes que a normalização (duplicação dos dados) devido a velocidade de recuperação dos dados
- os BD de grafos(Neo4j)

