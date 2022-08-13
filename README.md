<h1 align="center">Desafio 03 </h1>
<h4 align="center">Ignite - <a href="https://rocketseat.com.br/" >Rocketseat</a> - Trilha Node js</h4>

## Descrição

Essa aplicação realiza o CRUD (**C**reate, **R**ead, **U**pdate, **D**elete) de repositórios de projetos. Além disso, é possível dar likes em repositórios cadastrados, aumentando a quantidade de likes em 1 a cada vez que a rota é chamada.

## Funcionalidades

- Criar um novo repositório com `title`, `url`, `techs` e `likes`
- Listar todos os _repositórios_;
- Alterar o `title`, `url` e `techs` de um _repositório_ existente;
- Dar like em um _repositório_ existente;
- Excluir um _repositório_;

## Rotas

- GET `/repositories` → lista com todos os repositórios.
- POST `/repositories` → criar um repositório.
- PUT `/repositories/:id` → atualiza um repositório.
- POST `/repositories/:id/like` → adiciona um like para um repositório.
- DELETE `/repositories/:id` → deleta um repositório pelo `id`

## Instalação e uso

```bash
# Abra um terminal e copie este repositório com o comando
git clone https://github.com/guerreiru/ignite-corrigindo-o-codigo.git
# ou use a opção de download.

# Entre na pasta web com 
cd ignite-conceitos-do-nodejs

# Instale as dependências
yarn install

# Rode a aplicação
yarn start
```

<br>

[![Linkedin Badge](https://img.shields.io/badge/-Fernando%20Guerreiro-1293d2?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/guerreiru/)](https://www.linkedin.com/in/guerreiru/) 
[![Gmail Badge](https://img.shields.io/badge/-dev.fernandoguerreiro@gmail.com-EA4335?style=flat-square&logo=Gmail&logoColor=white&link=mailto:dev.fernandoguerreiro@gmail.com)](mailto:dev.fernandoguerreiro@gmail.com)
