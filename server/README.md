# INSTALAÇÃO DE DEPENDENCIAS DO PROJETO

## npm i typescript -D

## npx tsc --init

## Dentro do tsconfig.json
## trocar "target": "es2020"

## npm i fastify

## Criar uma pasta "src" e dentro server.ts

## Instalar dependencia para que compile automaticamente o Typescript
## npm i tsx -D
## no package.json fazer a seguinte alteração
## "dev": "tsx watch src/server.ts"

## para executar é: npm run dev

## npm i prisma -D
## npm i @prisma/client

## criar uma conexão com o BD com prisma
## npx prisma init --datasource-provider SQLite