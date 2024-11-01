# DMPP - Docker, MariaDB, PostgreSQL e PHP

Simples configuração para um ambiente de desenvolvimento com o PHP moderno

## Requerimentos

- [Docker](https://www.docker.com) >= 27
- [Docker Compose](https://docs.docker.com/compose/install) >= v2

## Como usar

Para iniciar basta clonar o repositório:

```shell
git clone https://github.com/eduardoteles17/dmpp.git
```

Copiar o arquivo `.env.example` para `.env`. E depois editar o arquivo `.env` para editar para as configurações
desejadas

```shell
vim .env
```

Agora basta criar um link simbólico para o seu projeto:

```shell
ln -s <caminho-ate-o-projeto> ./projects/<nome-do-projeto>
```

Agora basta iniciar com o docker

```shell
docker compose up -d
```
