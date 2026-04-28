# Catálogo Interativo App

Este é um aplicativo de e-commerce simples desenvolvido com React Native e React Navigation. Ele permite que os usuários se autentiquem, naveguem por categorias de produtos, visualizem a lista de produtos, e visualizem os detalhes de cada produto.

## Funcionalidades

- **Login**: Tela de Login: Permite que o usuário entre com um nome de usuário e senha. 
- **Home**: Página de boas-vindas com botão para sair (logout) e acessar a lista de produtos.  
- **Lista de Produtos**: Mostra todos os produtos cadastrados com nome, imagem e breve descrição.  
- **Detalhes do Produto**: Ao selecionar um item da lista, o usuário vê informações completas como descrição, imagem e preço.  
- **Logout**: Disponível na Home para encerrar a sessão e voltar ao login.

## Tecnologias utilizadas

- [React Native] Framework para desenvolvimento de aplicativos móveis.
- [React Navigation] Biblioteca para navegação entre telas.
- Axios - Cliente HTTP para fazer requisições à API.
- Expo - Ferramenta que facilita o desenvolvimento e execução de aplicativos React Native.
- JavaScript ES6+ 

## Estrutura do projeto

```
src/
 ├── components/
 │   ├── LogoutButton.js        // Botão para sair da conta
 │   └── ProductItem.js         // Exibição de item individual da lista
 ├── navigation/
 │   └── AppNavigation.js       // Rotas e navegação do app
 ├── screens/
 │   ├── HomeScreen.js          // Tela inicial
 │   ├── LoginScreen.js         // Tela de login
 │   ├── ProductDetailScreen.js // Tela de detalhes
 │   └── ProductListScreen.js   // Lista de produtos
```

## Pré-requisitos

- [Node.js]  
- [Expo CLI]
- Git instalado  


## Como rodar o projeto

```bash
# Clonar o repositório
git clone https://github.com/seu-usuario/catalogoInterativoApp.git

# Acessar a pasta do projeto
cd catalogoInterativoApp

# Instalar a dependência
npm install

# Para iniciar o app:

npx expo start

```

## Login e senha para acessar o app
 - Login: Admin
 - Senha: 1234

Autor
Matheus Souza