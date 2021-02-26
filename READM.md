# IF MAP

Projeto Integrador, trabalho submetido ao Instituto Federal Catarinense, Campus Camboriú.

## Instalação

Na pasta `back/`, isso irá instalar todas as dependencias que estão no `package.json`:
```bash
npm install
```

Na pasta `front/`, isso irá instalar todas as dependencias que estão no `package.json`:
```bash
npm install
```

## Configuração

Primeiro, crie um arquivo em `back/src/config/` chamado `db.js`, seguindo o exemplo de `db-example.js`, mas seguindo as suas credenciais.

Para criar o banco, use:
```hash
npx sequelize db:create
```

Para criar as migrates, use:
```hash
npx sequelize db:migrate
```

## Inicialização
Para inicializar o projeto, use:
```bash
npm run serve
```

## Requisitos
- [Node](https://nodejs.org/en/download/)
- [MySQL](https://dev.mysql.com/downloads/windows/installer/8.0.html)