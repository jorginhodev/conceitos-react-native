<h1 align="center">
    <img alt="GoStack" src="https://rocketseat-cdn.s3-sa-east-1.amazonaws.com/bootcamp-header.png" width="200px" />
</h1>

<h3 align="center">
  Conceitos do React Native
</h3>

<p align="center">Desafio 04: Conceitos do React Native, aplicado no <a href="https://rocketseat.com.br/bootcamp">Bootcamp GoStack</a> 🎓</p>

<p align="center">
  <a href="#-tecnologias">Tecnologias</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-instalacao-e-execução">Instalação e execução</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-sobre-o-desafio">Sobre o desafio</a>
</p>

## 🖥 Tecnologias

Este projeto foi desenvolvido com as seguintes tecnologias:

- [React Native](https://reactnative.dev/)
- [Axios](https://github.com/axios/axios)

## 🚀 Instalação e execução

1. Faça um clone desse repositório;
2. Entre na pasta rodando `cd conceitos-react-native`;
3. Rode `yarn` para instalar as dependências;
4. Rode `react-native run-ios` para iniciar o app no emulador do iOS ou rode `react-native run-android` para iniciar o app no emulador do Android;
5. Rode `yarn test` para rodar os testes.

## 🚀 Sobre o desafio

Nesse desafio, foi criada uma aplicação para treinar o que foi aprendido até agora no React Native!

Consiste em continuar desenvolvendo a aplicação que irá armazenar repositórios do portfólio, que foi desenvolvido o backend utilizando o Node.js, e no último desafio em ReactJS.

### Funcionalidades da aplicação

- **`Listar os repositórios da sua API`**: Deve ser capaz de criar uma lista de todos os repositórios que estão cadastrados na API com os campos **title**, **techs** e número de curtidas seguindo o padrão `${repository.likes} curtidas`, apenas alterando o número para ser dinâmico.

- **`Curtir um repositório listado da API`**: Deve ser capaz de curtir um item na API através de um botão com o texto **Curtir** e deve atualizar o número de likes na listagem no mobile.

### Especificação dos testes

Para esse desafio temos os seguintes testes:

- **`should add a like to the like counter of the repository`**: Para que esse teste passe, sua aplicação deve permitir ao clicar no botão `Curtir`, um like seja adicionado ao repositório listado, e que essa atualização possa ser visualizada na tela.

Feito com 💜 by Jorge Ramos
