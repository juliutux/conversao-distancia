# Desafio DevOps & Cloud

## Projeto: Implementar um conversor de unidade de distâncias


## Descrição

Conversão entre diferentes unidades de distância, como metros, quilômetros, milhas, etc.

## Ferramentas utilizadas

- **Python**: Linguagem de programação do projeto.
- **Flask**: Framework web utilizado para criar a interface do conversor.
- **Docker**: Utilizado para containerizar a aplicação

## Estrutura do projeto

- `app.py`: Arquivo principal que contém a lógica da aplicação Flask.
- `requirements.txt`: Lista de dependências necessárias para executar a aplicação.
- `Dockerfile`: Script para construir a imagem Docker da aplicação.
- `templates/`: Diretório que contém os templates HTML para a interface web.

## Como executar

**1. Executar o container com o Docker**:

```bash  
docker container run -d -p 8080:5000 juliu12/conversao-distancia:v1
```

A aplicação estará disponível em `http://localhost:8080`



Link da imgagem no Docker Hub: https://hub.docker.com/repository/docker/juliu12/conversao-distancia/general