# Papel dos BDs SQL e NoSQL na Engenharia de dados

## Banco de Dados Relacional

 - Um BD Relacional é um BD onde os dados tem relação entre si. Muito utilizado em sistemas transicionais como ecommerce em pedidos, etc.
 
## Banco de Dados Não Relacionais
 
  - Um BD Não Relacional os dados não possui relação entre si. E uma das vantagens é a escalabilidade hotizontal e dados não estruturados.
  
#### BD SQL 

   - Oracle;
   - MySQL;
   - Microsoft SQL Server;
   - Postgre SQL;
   
### BD NoSQL
 
 - MongoDB;
 - REdis;
 - Cassandra;
  
#### Tipos de NoSQL

 - Document Store;
 - Key - Value;
 - Wide - Column;
 - GRaph Store.
 
#### NoSQL
 - GRaph Store(Grafos)
Basicamente são estruturas matemáticas, compostas entre nós e vertices. Os *nós* compõe os daqdos e *vertíces* compõe os relacionamentos.
São comuns em detecção de fraudes, mecanismos de recomendação, redes socias, sistemas de arquivo, games, etc.
Os mais conhecidos são: *Neo4j* e *Microsoft Azure*.

 - Wide Column
 
Keyspace - Agrupamento Familias => database de colunas
Column Family/table - agrupamento de colunas => table
Row key - chave que representa uma linha de coluna => Primary key
Column - representa um valor conterndo name, value: timestamp.
Os mais conhecidos são: *Cassandra* e *Hbase*
 
 - Key Value

Armazena um conjunto de dados, seja ele simples ou complexo, identificados por um identificador exclusivo.
+ bom desempenho em aplicações na nuvem
- menos capacidade de busca
*Uso*: cache, sessão de usuario, carrinhos de compra.
Os mais conhecidos são: *Redis* e *Amazon DynamoDB*

 - Column
 
Alto desempenho, estrutura de dados na memória, versatilidade de uso, replicação e persistência.
Quem usa: Twitter, GitHub, Stackoverflow, etc.
Os mais conhecidos sâo: *MongoDB* e *HBase**

### Conhecer SGBD de cada tipo
Conhecer o contexto dos BDs e para que foram criados é tão importante quanto ter habilidade com cada tipo.

5 capacidades básicas dos BDs

 - Gestão
 - armazenamento
 - segurança
 - processamento
 - disponibilidade da informação
 - segurança e governança
 
### Relação Engenheiro e Cientosta de Dados

Eles se completam e o Engenheiro de Dados está para a preparação dos dados; Cientista de Dados está para criação de modelos.

Hoje muitas empresas estão trabalhando com o modelo híbrido. E os BDs NoSQL vieram para agregar mais versatilidade e suprir deficências dos BDs SQL.

 