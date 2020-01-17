Usando CLI da Rocketseat para criar base de projeto
omni init modulo11 --only=server
Se nao passar opcao cria node, react e native na mesma pasta 

yarn add jest -D
yarn jest --init

yarn add --dev @sucrase/jest-plugin

Then add it as a transform to your Jest config in package.json:

  "jest": {
    "transform": {
      ".(js|jsx|ts|tsx)": "@sucrase/jest-plugin"
    },
    ...
  }

  yarn add -D @types/jest

yarn sequelize migration:create --name=create-users