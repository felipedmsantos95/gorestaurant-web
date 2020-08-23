# GoRestaurant Web

<p align="center">
    <a href="readme_en.md">English</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
    <a href="readme.md">Português</a>&nbsp;&nbsp;&nbsp;
</p>

## Prévia da Aplicação

<p align="center">
  <img src="https://github.com/felipedmsantos95/gorestaurant-web/blob/master/img/gorestaurant-web.gif"/>
</p>

## Sobre

Aplicação web CRUD de um restaurante que exibe os pratos de comida criados e permite a criação, remoção e atualização desses pratos.


## Tecnologias utilizadas

- React.js

## Requisitos

Para executar o projeto é necessário ter os seguintes requisitos:

- Node 12.x ou superior
- Yarn 1.21 ou superior

## Executando o projeto

### Clonando o projeto

```bash
$ git clone https://github.com/felipedmsantos95/gorestaurant-web
$ cd gorestaurant-web
```

### Scripts para execução do projeto

Dentro do diretório do projeto pela primeira vez, você deve executar o comando `yarn` para instalar as dependências, então será possível rodar os seguintes scripts:

#### Executar Fake API

```bash
$  yarn json-server server.json -p 3333
```

Para exibir dados em tela, há um arquivo para ser utilizado como uma espécie de fake API para prover esses dados. Para isso, há no package.json uma dependência chamada json-server, e um arquivo chamado server.json que contém os dados para uma rota `/foods`.


#### Executar a aplicação em modo de desenvolvimento

```bash
$ yarn start
```
Abra [http://localhost:3000](http://localhost:3000) para ver em um navegador web.

A página irá recarregar quando você fizer edições.<br />
Você poderá visualizar quaisquer erros no console.


#### Executar o script de testes que foram feitos na aplicação

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


