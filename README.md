# Estudo Spring Webflux com MongoDB
[![NPM](https://img.shields.io/npm/l/react)](https://github.com/fabiosimplis/DEV-dscommerce-back-end/blob/main/LICENSE) 

# Sobre o projeto

DSPost é uma aplicação back end web construída em conjunto ao curso **Java Spring Reference**, da plataforma [DevSuperior](https://devsuperior.com "Site da DevSuperior"), para estudo do spring Webflux usando o banco NoSQL MongoDB

O sistema consiste em um forum onde há posts e comnetários feitos por usuários.

## Postman Collection and Environment:
(download from the main folder of this repository, then import it into your Postman)
```
host: http://localhost:8080
```
## Modelo de Dominio
![Image](/assets/model-spring-mongodb.png "Modelo conceitual")

# Tecnologias utilizadas
## Back end
- Java
- Spring Webflux
- MongoDB
- Maven

### Features
- Find users
- Find users by id
- Insert new user
- Update user
- Delete user
- Find user posts
- Find posts by id
- Search posts by title
- Search posts using multiple criteria

### Spring Boot versions
- 3.0.0-RC1
- 3.2.8

# Como executar o projeto

## Back-end
Pré-requisitos: Java 17

```bash
# clonar repositório
git clone 

# entrar na pasta do projeto back end
cd spring-webflux-mongodb

# executar o projeto
./mvnw spring-boot:run
```
## Recursos adicionais


### Container Docker do MongoDB para desenvolvimento

```
docker run -d -p 27017:27017 -v /data/db --name mongo1 mongo:4.4.3-bionic
```

```
docker exec -it mongo1 bash
```