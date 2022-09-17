# Projeto Relacional e não Relacional _
 Projeto Dio de Banco de Dados
<h1>Modelo Relacional</h1>
<p>Para sabemos qual é a diferença devemos primeiramente defini-los, o modelo relacional surgiu por volta da década de 70 aos, ao pouco foi popularizando, e aprimorou em um modelo relacional, podendo estacar em dois modelos Entidade e Relação.

A Entidade tem como característica por ser formalmente chamado de tabela, na tabela definine , seu atributos e as linhas que são os seus registros. 

Relação ela determina cada tabela se associa coms registro de outra tabela, para que se localiza, as relações geralmente as chaves primárias e chaves estrangeiras. As chaves são colunas que identificam unicamente cada região isso dentro de uma tabela. As chaves estrangeiras a coluna que faz relacionamento com outra chave primária de outras tabelas. assim com as construção do meu banco devo formatar a relação entre eles , projeto , esquema , estrutura de dados com suas tabelas , define como os dados serem inserido na lease, não podendo inserir nenhum dados se a estrutura não for definida.No modelo relacional de assinar um controle de valor , vão se comportar antes de efetivamente ele vai para o banco Relacional ACID , vão assumir as seguintes caraterística : 

1- Atomicidade;
2- Consistência;
3- Isolamento;
4- Durablidade.
foi feito de uma indivisil as transações só vai acontecer se tiverem usando a linguagem sql.</p>
<h1>Modelo não relacional</h1>
Comecou a ganhar popularidade no final do ano 2000, antigamente uso era caro , por nome ser não relacional a relação aconte, na verdade podemos inserir com várias atributos diferentes, sem definir quais os atributos que voce quer inserir , não precisar utilizar a linguagem de SQL para consulta . Além disso possui a caracteristia Basically solt state eventual consistency nem sempre os dados estará disponível e consistente  por isso sempre os dados estará disponivel o consistente por isso é muito importante planejar o uso no sistema ele tem vários clusters e cada elemento para acessar rápido voce tem que acessar determinada parte da cluster .

O modelo relacional garante a Integridade e Robustez da informação . Não relacional facilita a escabilidade do armazenamento de vários formatos de dados além disso, o não relacional os dados nem sempre estão consistentes.

Não relacional possui banco de dados orientados agregados.
Modelo chaves valor (Piak, Redis)
Modelo documento (MongoDB e Couch)
Modelo família de coluna (Cassandra , Apache, Apache HBase)
Agregado é um Conjunto de objetos relacionados.

Por que o uso de agregados ?
Incompatibilidade de impedância;
Grande de Volume de dados acessar (cluester)
Ele já possui a esttutura de objetos associados é um unidade natural de replica e fragmentadas.

Todos os dados de um agregados estão armazenados juntos no mesmo Nodo cluster