# API REST TypeScript

Este é um exemplo básico de uma API RESTful utilizando Express e TypeScript.

## Instalação

Para instalar as dependências, execute o seguinte comando:

```
npm install
```

## Executando o projeto

Para executar o projeto em modo de desenvolvimento, utilize o seguinte comando:

```
npm run dev
```

Isso iniciará o servidor de desenvolvimento e a API estará disponível em `http://localhost:3000`.

Para executar o projeto em modo de produção, utilize o seguinte comando:

```
npm start
```

Isso iniciará o servidor em modo de produção e a API estará disponível na porta configurada.

## Estrutura do Projeto

A estrutura do projeto está organizada da seguinte forma:

```
.
├── src
│   ├── routes
│   │   └── index.ts
│   ├── app.ts
│   └── server.ts
├── .gitignore
├── package.json
├── tsconfig.json
└── README.md
```

- A pasta `src` contém todos os arquivos do código-fonte.
- `routes` contém as definições das rotas da API.
- `app.ts` é o arquivo principal que configura o Express e seus middlewares.
- `server.ts` é o arquivo responsável por iniciar o servidor.

## Contribuindo

Se você quiser contribuir para este projeto, sinta-se à vontade para enviar um pull request. Ficarei feliz em analisá-lo!
