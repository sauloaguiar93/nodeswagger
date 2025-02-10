# NodeSwagger

Este projeto utiliza Fastify com Swagger para documentação de APIs e Zod para validação de tipos.

## Tecnologias Utilizadas

- [Fastify](https://www.fastify.io/)
- [Swagger](https://swagger.io/)
- [Zod](https://zod.dev/)
- [TypeScript](https://www.typescriptlang.org/)

## Requisitos

- Node.js 18+

## Instalação

Clone o repositório e instale as dependências:

```sh
npm install
```

## Execução do Servidor

Para rodar o servidor em modo de desenvolvimento:

```sh
npm run dev
```

O servidor iniciará e o Swagger UI estará disponível em: [http://localhost:3000/docs](http://localhost:3000/docs)

## Estrutura do Projeto

```
project-root/
│── src/
│   ├── server.ts    # Servidor Fastify
│   ├── routes/      # Rotas da API
│   ├── schemas/     # Schemas de validação com Zod
│── package.json
│── tsconfig.json
│── README.md
```

