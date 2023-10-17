# Ph E-Shop

**Este é um projeto de loja de um E-commerce utilizando o React JS, ele possui as seguintes funcionalidades: listar produtos na tela; buscar produtos com a API do Mercado Livre; adicionar produtos e remover produtos do carrinho.**

:point_right: Para testar online o projeto, clique neste [Link](https://phelipevt.github.io/ph-e-shop/).

## Funcionalidades

* Listagem de produtos: exibe uma lista de produtos da API do Mercado Livre.
* Busca de produtos: permite pesquisar produtos com base em palavras-chave, consumindo a API do Mercado Livre.
* Adição e Remoção de produtos ao carrinho: permite adicionar e remover produtos ao carrinho de compras.

## Pré-requisitos

Antes de começar, você vai precisar ter instalado em sua máquina as seguintes ferramentas:
* [Git](https://git-scm.com/)
* [Node.js](https://nodejs.org/en)

Também é necessário ter um editor para trabalhar com o código como o [VSCode](https://code.visualstudio.com/).

### Rodando a aplicação

```bash
# Clone este repositório
git clone https://github.com/PhelipeVT/ph-e-shop.git 

# Acesse a pasta do projeto no terminal/cmd
cd ph-e-shop

# Instale as dependências
npm install  

# Execute a aplicação em modo de desenvolvimento
npm start

# O servidor iniciará na porta:3000 - acesse http://localhost:3000/
```

## Tecnologias utilizadas

* React JS: biblioteca JavaScript para construção de interfaces de usuário.
* HTML5: linguagem de marcação para estruturar o conteúdo da aplicação.
* CSS3: linguagem de estilo para estilizar a interface do usuário.
* [API](https://api.mercadolibre.com/sites/MLB/search?q=) do Mercado Livre: utilizada para obter dados de produtos.
