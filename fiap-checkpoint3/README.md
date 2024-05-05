# Checkpoint 3

Aplicação Java com container checkpoint 3 - 1° Semestre

## Pré-requisitos

- Java 17+
- Docker 
- Acesso a internet
- Acesso ao Docker Hub

## Instalação

#### Clone

```
git clone https://github.com/art5hur/fiap-checkpoint3.git
```

## Execução


#### Docker

* Criar imagem

```
docker build -t fiap-checkpoint3 .
```

* Executar container

##### Comando "docker" para executar a aplicação a partir do docker hub do respectivo membro com profile "dev"
```
docker run -d -p 8080:8080 -e PROFILE=dev fiap-checkpoint3
```

##### Comando "docker" para executar a aplicação a partir do docker hub do respectivo membro com profile "stg"
```
docker run -d -p 8080:8080 -e PROFILE=stg fiap-checkpoint3
```

##### Comando "docker" para executar a aplicação a partir do docker hub do respectivo membro com profile "prd"
```
docker run -d -p 8080:8080 -e PROFILE=prd fiap-checkpoint3
```

## Navegação

- Base em 'dev'

http://localhost:8080/h2-console 

- Username

  sa

- Senha

  password

## Features (Funcionalidades)

### Múltiplos bancos de dados

- H2 = dev

- mySQL = prd

- Oracle = stg

## Integrantes

- Arthur Miranda Santos - RM:93023  -  https://hub.docker.com/repository/docker/art5hur/fiap-checkpoint3/general
- Thomas D'ávila Meyer Pflug - RM:92915  -  https://hub.docker.com/repository/docker/thouser12/fiap-checkpoint3/general
- Renan Bandeira Leite - RM:96168 - https://hub.docker.com/repository/docker/renanleite7/fiap-checkpoint3/general

# fiap-checkpoint3
