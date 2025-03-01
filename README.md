Esse é um boilerplate para um backend feito em NestJS utilizando Typescript e TypeORM.

Esse boilerplate já contém todas as configurações necessárias para que haja conexão com o banco de dados (PostgreSQL, mas pode ser facilmente para outros bancos relacionais).

#### Importante:

Ao baixar, lembre-se de instalar as dependências do projeto antes de fazer qualquer coisa:

```bash
  npm install
```

## Principais comandos:

#### Rodar o projeto

```bash
  npm run start:dev
```

##### Criação de resources (módulos)

```bash
  nest g resource nomeDaResource
```

#### Criação de migrations

```bash
  npm run migration:create -name=nomeMigration
```

#### Rodar migrations

```bash
  npm run migration:run
```

#### Reverter migrations

```bash
  npm run migration:revert
```

Importante lembrar de sempre ligar a extensão do ESLINT e do Prettier, para que o lint funcione no projeto todo.
