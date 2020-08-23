# GoRestaurant Web

<p align="center">
    <a href="readme_en.md">English</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
    <a href="readme.md">Português</a>&nbsp;&nbsp;&nbsp;
</p>

## Application Preview

<p align="center">
  <img src="https://github.com/felipedmsantos95/gorestaurant-web/blob/master/img/gorestaurant-web.gif"/>
</p>

## About

CRUD web application for a restaurant that displays created food dishes and allows the creation, removal and updating of these menu itens.


## Technologies used

- React.js

## Requirements

To execute the project it is necessary to have the following requirements installed in the system:

- Node 12.x or later
- Yarn 1.21 or later

## Running the project

### Cloning the project

```bash
$ git clone https://github.com/felipedmsantos95/gorestaurant-web
$ cd gorestaurant-web
```

### Scripts for project execution

Inside the project directory for the first time, you must run the `yarn` command to install the dependencies, so it will be possible to run the following scripts:

#### Running Fake API

```bash
$  yarn json-server server.json -p 3333
```

To display data on screen, there is a file to be used as a kind of fake API to provide this data. For that, there is a dependency in package.json called json-server, and a file called server.json that contains the data for a `/foods` route.


#### Run the app in the development mode

```bash
$ yarn start
```
Abra [http://localhost:3000](http://localhost:3000) para ver em um navegador web.

The page will reload if you make edits.
You will also see any lint errors in the console.


#### Run tests script

```bash
$ yarn test
```


<h3 align="center">
  Enunciado do desafio proposto
</h3>

## Sobre o desafio

Nesse desafio, você irá desenvolver mais uma aplicação, a GoRestaurant. Agora você irá praticar o que você aprendeu até agora no React.js junto com TypeScript, praticando o conceito de CRUD (Create, Read, Update, Delete).


### Funcionalidades da aplicação


- **`Listar os pratos de comida da sua API`**: Sua página `Dashboard` deve ser capaz de exibir uma listagem, com o campo `title`, `value`, e  `description` e `available` de todos os pratos de comida que estão cadastrados na sua API.

- **`Adicionar novos pratos de comida a sua API`**: Em sua página Dashboard você deve abrir um modal ao clicar no botão `Novo Prato` no Header. Esse modal deve ser responsável por cadastrar uma nova `food` passando os campos `image`, `name`, `description`, `value`.

- **`Editar pratos de comida da sua API`**: Em sua página Dashboard você deve abrir um modal ao clicar no botão `Editar Prato`. Esse modal deve ser responsável por editar uma `food` passando os campos `image`, `name`, `description`, `value`.

- **`Remover pratos de comida da sua API`**: Em sua página Dashboard você deve remover um prato de comida ao clicar no botão com ícone de lixeira no componente Food.

- **`Alterar disponibilidade dos pratos de comida da sua API`**: Em sua página Dashboard você deve alterar a disponibilidade de um prato de comida ao clicar no switch que é controlado pelo valor de `available`.


### Específicação dos testes

Para esse desafio temos os seguintes testes:

* **`should be able to list all the food plates from your api`**: Para que esse teste passe, sua aplicação deve permitir que sejam listados, toda os pratos de comidas que são retornadas da sua fake API.

- **`should be able to add a new food plate`**: Para que esse teste passe, você deve permitir que um prato de comida seja adicionado a sua api, adicionando-o também à listagem.

- **`should be able to edit a food plate`**: Para que esse teste passe, você deve permitir que um prato de comida seja editado na sua api, editando-o também na listagem.

- **`should be able to remove a food plate`**: Para que esse teste passe, você deve permitir que um prato de comida seja removido da sua api, removendo-o também da listagem.

- **`should be able to update the availibility of a food plate`**: Para que esse teste passe, em sua dashboard você deve permitir que o status do prato de comida seja alterado entre `Disponível` e `Indisponível`;


