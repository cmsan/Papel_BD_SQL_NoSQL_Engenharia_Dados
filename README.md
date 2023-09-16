# Papel dos BDs SQL e NoSQL na Engenharia de dados

## Banco de Dados Relacional

 - Um BD Relacional � um BD onde os dados tem rela��o entre si. Muito utilizado em sistemas transicionais como ecommerce em pedidos, etc.
 
## Banco de Dados N�o Relacionais
 
  - Um BD N�o Relacional os dados n�o possui rela��o entre si. E uma das vantagens � a escalabilidade hotizontal e dados n�o estruturados.
  
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
Basicamente s�o estruturas matem�ticas, compostas entre n�s e vertices. Os *n�s* comp�e os daqdos e *vert�ces* comp�e os relacionamentos.
S�o comuns em detec��o de fraudes, mecanismos de recomenda��o, redes socias, sistemas de arquivo, games, etc.
Os mais conhecidos s�o: *Neo4j* e *Microsoft Azure*.

 - Wide Column
 
Keyspace - Agrupamento Familias => database de colunas
Column Family/table - agrupamento de colunas => table
Row key - chave que representa uma linha de coluna => Primary key
Column - representa um valor conterndo name, value: timestamp.
Os mais conhecidos s�o: *Cassandra* e *Hbase*
 
 - Key Value

Armazena um conjunto de dados, seja ele simples ou complexo, identificados por um identificador exclusivo.
+ bom desempenho em aplica��es na nuvem
- menos capacidade de busca
*Uso*: cache, sess�o de usuario, carrinhos de compra.
Os mais conhecidos s�o: *Redis* e *Amazon DynamoDB*

 - Column
 
Alto desempenho, estrutura de dados na mem�ria, versatilidade de uso, replica��o e persist�ncia.
Quem usa: Twitter, GitHub, Stackoverflow, etc.
Os mais conhecidos s�o: *MongoDB* e *HBase**

### Conhecer SGBD de cada tipo
Conhecer o contexto dos BDs e para que foram criados � t�o importante quanto ter habilidade com cada tipo.

5 capacidades b�sicas dos BDs

 - Gest�o
 - armazenamento
 - seguran�a
 - processamento
 - disponibilidade da informa��o
 - seguran�a e governan�a
 
### Rela��o Engenheiro e Cientosta de Dados

Eles se completam e o Engenheiro de Dados est� para a prepara��o dos dados; Cientista de Dados est� para cria��o de modelos.

Hoje muitas empresas est�o trabalhando com o modelo h�brido. E os BDs NoSQL vieram para agregar mais versatilidade e suprir defic�ncias dos BDs SQL.

 