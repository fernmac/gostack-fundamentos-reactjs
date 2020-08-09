# GOSTACK - Fundamentos do React JS

![](https://img.shields.io/badge/made%20by-fernmac-04d361?style=flat&color=04d361) 
![](https://img.shields.io/github/languages/count/fernmac/gostack-fundamentos-reactjs?style=flat&color=04d361) 
[![GitHub stars](https://img.shields.io/github/stars/fernmac/gostack-fundamentos-reactjs?style=social)](https://github.com/fernmac/gostack-fundamentos-reactjs/stargazers)

GoFinances Web - Aplicação para armazenar transações financeiras de entrada e saída, que deve permitir o cadastro/listagem dessas transações e a importação de um arquivo CSV para gerar novos registros no banco de dados.

------------

## Instalação

- Para iniciar a instalação é necessário clonar o repositório

  ```shell
  git clone [url_repositorio]
  ```

- Entrar no diretório clonado

  ```shell
  cd gostack-fundamentos-reactjs
  ```

- Instalar as dependências do projeto via **NPM** ou **YARN**

  ```shell
  npm install
  ```

- Essa aplicação depende do back-end criado no desafio anterior: **[gostack-typeorm-upload](https://github.com/fernmac/gostack-typeorm-upload)**

## Execução

- Instalar o componente react-app-rewired

  ```shell
  npm install react-app-rewired --save-dev
  ```

- Executar o comando para iniciar o front-end

  ```shell
  npm run start
  ```

## Funcionalidades

O front-end tem o objetivo de fornecer as seguintes funcionalidades:

- Listar as transações: Exibir uma listagem através de uma tabela, com o campo title, value, type e category de todas as transações que estão cadastradas na API.

- Exibir o balance: Exibir o balance que é retornado do backend, contendo o total geral, junto ao total de entradas e saídas.

- Importar arquivos CSV: Permitir o envio de um arquivo no formato csv para o backend, que irá fazer a importação das transações para o banco de dados. O arquivo csv deve seguir o seguinte seguinte [modelo](./assets/file.csv).
