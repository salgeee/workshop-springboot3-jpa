# Web Services com Spring Boot e JPA/Hibernate
[![NPM](https://img.shields.io/npm/l/react)](https://github.com/salgeee/workshop-springboot3-jpa/blob/main/LICENSE) 

# Sobre o projeto


Web Services com Spring Boot e JPA/Hibernate é uma aplicação backend, com padrão REST, construída durante o curso Java COMPLETO 2023 Programação Orientada a Objetos + Projetos, evento ministrado por Nelio Alves pela [DevSuperior](https://devsuperior.com.br/ "Site da DevSuperior").

A aplicação consiste em um web service, onde é divido em camadas quais são, Resource Layer(rest controllers) recebe as requisições e respondem de acordo com o comportamento do sistema, existe também a Service Layer e a Data Access Layer, toda essa pilha de camadas conversa com as entidades do projeto.

## Modelo de dominio 
![Modelo 1](https://raw.githubusercontent.com/salgeee/workshop-springboot3-jpa/main/assets/DomainModel.png) 


## Modelo de instanciação
![Modelo 2](https://raw.githubusercontent.com/salgeee/workshop-springboot3-jpa/main/assets/DomainInstance.png)

# Tecnologias utilizadas
## Back end
- Java
- Spring Boot
- JPA / Hibernate
- Maven

## Implantação em produção

- Banco de dados: Postgresql

# Como executar o projeto

## Back end
Pré-requisitos: Java 17+

```bash
# clonar repositório
git clone https://github.com/salgeee/workshop-springboot3-jpa.git

# entrar na pasta do projeto 
git bash here

# executar o projeto
./mvnw spring-boot:run

# no postman:
get http://localhost:8080/users

# no navegador:
localhost:8080/h2-console/
Driver Class: org.h2.Driver
JDBC URL: jdbc:h2:mem:testdb
Username: sa



```

# Autor

Leonardo Ferreira Salge

https://www.linkedin.com/in/leonardosalge/

