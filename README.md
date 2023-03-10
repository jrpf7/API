<h1 align="center"> Desafio c# </h1>

<p align="center">
<img src="http://img.shields.io/static/v1?label=STATUS&message=EM%20DESENVOLVIMENTO&color=GREEN&style=for-the-badge"/>
</p>

## Descrição do projeto 

<p align="justify">
  Projeto com finalidade de desenvolver um conjunto de endpoints que serao disponibilizados para o time de frontend desenvolver o site. 
</p>

## Observações 

<p align="justify">
  Sempre, antes de qualquer requisição de dados é necessário gerar um token. Esse token é gerado a partir do usuário e senha informados no endPoint de Login.  

  Usuários  com acesso “comum” possuem apenas permissão de visualização, enquanto que usuários com acesso “admin”, podem criar e modificar dados.
</p>

## Pré-requisitos

:warning: [.NET 5.0](https://dotnet.microsoft.com/en-us/download/dotnet/5.0)

## Bibliotecas utilizadas :books:

- Fluent Validation
- Authentication.Core
- Authentication.JwtBearer

## Como rodar a aplicação :arrow_forward:

Habilidar o projeto inicial como API -> Botao direito no projeto API -> Set as StartUp Project

## Usuários

|usuario|acesso|senha|id|
| -------- |-------- |-------- |-------- |
|admin|admin|admin|1|
|comum|comum|comum|2| 

Copyright :copyright: 2023 - DESAFIO C#
