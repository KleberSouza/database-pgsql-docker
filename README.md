# Database PostgreSQL

Repositório para configuração de um servidor PostgreSQL usando Docker Compose.

## Requisitos

- Docker
- Docker Compose

## Passos para configurar a instância do PostgreSQL

1. Clone o repositório:

   ```sh
   git clone https://github.com/klebersouza/database-pgsql-docker.git
   cd database-pgsql-docker
   ```

1. Suba o container com Docker Compose:

   ```sh
   docker-compose up -d
   ```

1. Verifique se o container está rodando:

   ```sh
   docker-compose ps
   ```

1. Acesse o banco de dados (opcional):

   ```sh
   docker exec -it database_postgres psql -U postgres -d mydatabase
   ```
