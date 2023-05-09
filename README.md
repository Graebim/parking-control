# Parking Spot Control
> _Construir uma API com banco de dados(postgreSQL) usando java(17), Postman e Spring Boot (parking-control)._

## Visão geral do sistema
Construir um pequeno sistema (API) para Controle de Vaga de Estacionamento, com os seguintes casos de uso:

- Inserir um novo usuário.
- Buscar todos usuários.
- Buscar um usuário pelo seu id.
- Alterar usuário existente.
- Deletar um usuário pelo seu id.

## Ferramentas:
- JDK 17
- Maven
- Postman
- PgAdmin (Postgres)
- IDE (Eclipse)

## Configurações db:
```spring.datasource.url= jdbc:postgresql://localhost:5432/parking-control-db
spring.datasource.username=postgres
spring.datasource.password=postgres123
spring.jpa.hibernate.ddl-auto=update
spring.jpa.properties.hibernate.jdbc.lob.non_contextual_creation=true
```
