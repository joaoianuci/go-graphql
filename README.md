# Go GraphQL
Um CRUD utilizando GraphQL, Go, gqlgen e SQLite.

## Começando

Estas instruções vão te ajudar a configurar e rodar o projeto na sua máquina local para desenvolvimento e testes. 

### Pré-requisitos
- Go
- SQLite3
- gqlgen

### Instalação

Clone o repositório:

```bash
git clone https://github.com/joaoianuci/go-graphql.git
```

Navegue até o diretório do projeto:

```bash
cd go-graphql
```

Instale as dependências:

```bash
go mod tidy
go run github.com/99designs/gqlgen generate
```

### Rodando o projeto
Inicie o servidor:

```bash
go run cmd/server/server.go
```

## Tecnologias Utilizadas

- **Go**: Linguagem de programação utilizada.
- **GraphQL**: Usado para criar queries e manipular dados.
- **gqlgen**: Biblioteca Go para construir servidores GraphQL de forma idiomática.
- **SQLite**: Banco de dados utilizado para armazenar dados.
