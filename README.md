<h1 align="center"> ViageMais </H1>

<h1 align="center">
        <img src="https://raw.githubusercontent.com/LeandroNcosta/ViageMais/main/images/airplane.svg" width="50px" />
</h1>

<h4 align="center">Status: Em desenvolvimento... </h4>

<p align="center">
 <img src="https://img.shields.io/static/v1?label=Tipo&message=Desafio&color=8257E5&labelColor=000000" alt="Exercicio" />
</p>

<p align="center">
 <a href="#-about">Executar</a> •
 <a href="#-Features">Sobre</a> •
 <a href="#-layout">Layout</a> • 
</p>

API para gerenciar tarefas (CRUD) que faz parte do desafio do modulo 5 da RECODEPRO 2023

## Tecnologias
 
- [Spring Boot](https://spring.io/projects/spring-boot)
- [Spring Data JPA](https://spring.io/projects/spring-data-jpa)
- [SpringDoc OpenAPI 3](https://springdoc.org/v2/#spring-webflux-support)
- [Mysql](https://dev.mysql.com/downloads/)

## Práticas adotadas

- API REST
- Consultas com Spring Data JPA
- Injeção de Dependências
- Geração automática do Swagger com a OpenAPI 3

## Como Executar

- Clonar repositório git
- Construir o projeto:
```
$ ./mvnw clean package
```
- Executar a aplicação:
```
$ java -jar target/viagemais-0.0.1-SNAPSHOT.jar
```

A API poderá ser acessada em [localhost:8080](http://localhost:8080).
O Swagger poderá ser visualizado em [localhost:8080/swagger-ui/index.html#/](http://localhost:8080/swagger-ui/index.html#/)

## API Endpoints

```markdown
GET /destination 

GET /destination/{id} 

GET /hotel

...

As rotas restantes podem ver pelo Swagger

```

### application.properties

```
spring.datasource.url=jdbc:mysql://localhost:3306/viagemais?createDatabaseIfNotExist=true
# &useTimezone=true&serverTimezone=UTC
spring.datasource.username=root
spring.datasource.password=1234

spring.datasource.driver-class-name=com.mysql.cj.jdbc.Driver

spring.jpa.hibernate.ddl-auto=update
spring.jpa.show-sql=true
spring.jpa.properties.hibernate.format_sql = true

spring.jpa.open-in-view=false
```
## 🚀 Como executar o projeto.

Este projeto é divido em duas partes:
1. Backend (API) 
2. Frontend 


### Pré-requisitos

Antes de começar, você vai precisar ter instalado em sua máquina as seguintes ferramentas:
[Git](https://git-scm.com), [java sdk](). 
Além disto é bom ter um editor/ide para trabalhar

### 🎲 Rodando o Back End

```bash
# Clone este repositório
$ git clone https://github.com/LeandroNcosta/ViageMais.git

# Acesse a pasta do projeto no terminal/cmd
$ cd + sua pasta + /api

# O servidor inciará na porta:8080 - acesse <http://localhost:3333>
```

### Adicional:

#### 🎲 Rodando a aplicação (Frontend para testar API)

```bash

# Clone este repositório
$ git clone https://github.com/LeandroNcosta/ViageMais.git

# Acesse a pasta do projeto no terminal/cmd
$ cd + sua pasta 

# Instale as dependências com:
$ npm install

# Rode a aplicação em modo de desenvolvimento:
$ npm run dev

# O servidor inciará na porta:3000 - acesse <   http://127.0.0.1:3000/ >
```
---

```
