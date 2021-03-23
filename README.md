# aulajpamaven

## JPA  
Java Persistence API (JPA) é a especificação padrão da plataforma Java EE (pacote javax.persistence) para mapeamento objeto-relacional e persistência de dados.

Para trabalhar com JPA é preciso incluir no projeto uma implementação da API (ex: Hibernate).

Os objetos que são manipulados tem que estar monitorados.

### Principais classes  

#### EntityManager  

Um objeto EntityManager encapsula uma conexão com a base de dados e serve para efetuar operações de acesso a dados (inserção, remoção, deleção, atualização) em entidades (clientes, produtos, pedidos, etc.) por ele monitoradas em um mesmo contexto de persistência.

#### EntityManagerFactory  

Um objeto EntityManagerFactory é utilizado para instanciar objetos EntityManager.
