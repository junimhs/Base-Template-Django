## Template inicial do django

Base incial vem com o django + postgres, sendo um projeto limpo do django

## Começando

Para executar o projeto, será necessário instalar apenas o docker com o docker-compose:

- [Docker: Necessário para executar o projeto](https://www.docker.com)

## Instalação

- Crie o volume do PostgreSQL

```bash
docker volume create base-pgdata
```

- Execute o projeto com o Docker:

```bash
docker-compose up
```

## Rodar o projeto

- Acesse http://localhost:8000 para acessar o Django
