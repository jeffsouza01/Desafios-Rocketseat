# Desafios Rocketseat

Aqui estão desafios realizados dentro do bootcamp Ignite - NodeJS da Rocketseat.



# Chapter I




## Desafio 1 - Conceito NodeJS
### [Conceito NodeJS](https://github.com/jeffsouza01/ignite-nodejs-mod1/tree/ad7c23a4dc631a1d385e29f563fa7777ded720b7)
<p>Nesse desafio, foi criado uma aplicação para gerenciar tarefas (em inglês *todos*). 
Será permitida a criação de um usuário com `name` e `username`, bem como fazer o CRUD de *todos*:

- Criar um novo *todo*;
- Listar todos os *todos*;
- Alterar o `title` e `deadline` de um *todo* existente;
- Marcar um *todo* como feito;
- Excluir um *todo*;

Tudo isso para cada usuário em específico (o `username` será passado pelo header). 🚀


## Desafio 2 - Trabalhando com middlewares
### [Trabalhando com middlewares](https://github.com/jeffsouza01/ignite-nodejs-middleware)
<p>Nesse desafio foi mais a fundo com middlewares no Express. 

Para facilitar um pouco mais do conhecimento da regra de negócio, foi trabalhado com a mesma aplicação do desafio anterior: uma aplicação para gerenciar tarefas (ou *todos*) mas com algumas mudanças.

Será permitida a criação de um usuário com `name` e `username`, bem como fazer o CRUD de *todos*:

- Criar um novo *todo*;
- Listar todos os *todos*;
- Alterar o `title` e `deadline` de um *todo* existente;
- Marcar um *todo* como feito;
- Excluir um *todo*;

Tudo isso para cada usuário em específico. Além disso, dessa vez teremos um plano grátis onde o usuário só pode criar até dez *todos* e um plano Pro que irá permitir criar *todos* ilimitados, isso tudo usando middlewares para fazer as validações necessárias. 🚀



## Desafio 03 - Corrigindo o código

### [Corrigindo o código](https://github.com/jeffsouza01/ignite-nodejs-verify-code)

Nesse desafio, temos uma aplicação Node.js que está em processo de desenvolvimento mas que já possui os testes necessários para fazer toda a validação dos requisitos. Após algumas alterações no código da aplicação, parte dos testes deixaram de passar e agora só você pode resolver esse problema. Bora lá? 🚀

Essa aplicação realiza o CRUD (**C**reate, **R**ead, **U**pdate, **D**elete) de repositórios de projetos. Além disso, é possível dar likes em repositórios cadastrados, aumentando a quantidade de likes em 1 a cada vez que a rota é chamada.

A estrutura de um repositório ao ser criado é a seguinte:

```jsx
{
  id: uuid(),
  title,
  url,
  techs,
  likes: 0
}
```

Descrição de cada propriedade:

- **id** deve ser um uuid válido;
- **title** é o título do repositório (por exemplo "unform");
- **url** é a URL que aponta para o repositório (por exemplo "https://github.com/unform/unform");
- **techs** é um array onde cada elemento deve ser uma string com o nome de uma tecnologia relacionada ao repositório (por exemplo: ["react", "react-native", "form"]);
- **likes** é a quantidade de likes que o repositório recebeu (e que vai ser incrementada de 1 em 1 a cada chamada na rota de likes).

Note que a quantidade de likes deve sempre ser zero no momento de criação.



# Chapter II



## Desafio 01 - Introdução ao SOLID

### [Introdução ao SOLID](https://github.com/jeffsouza01/ignite-nodejs-solid/tree/a6e98aa7b2f773739c18c517bd78e632fadc2d16)



Nesse desafio, Foi criado uma de listagem e cadastro de usuários. Para que a listagem de usuários funcione, o usuário que solicita a listagem deve ser um admin.






### Projetos em Desenvolvimento
🚧🚧🚧🚧



#### Author
*Made with* 💜 *by* **__Jefferson da Silva__**
