# Toughts Project Node.js

Este é um projeto de uma micro rede social de pensamentos, onde os usuários podem se cadastrar, publicar e ler pensamentos da comunidade.

## Descrição

O Toughts Project permite que os usuários criem uma conta, façam login, compartilhem seus pensamentos, editem e removam seus próprios pensamentos. Além disso, eles podem ver os pensamentos de outros usuários na comunidade.

## Funcionalidades

- Cadastro de usuário
- Login de usuário
- Publicação de pensamentos
- Edição de pensamentos
- Remoção de pensamentos
- Uso de sessões para manter usuários logados
- Criptografia de senhas com bcrypt

## Tecnologias e Pacotes Utilizados

- Node.js
- Express
- Express-Handlebars
- Express-Session
- Session-File-Store
- Bcryptjs
- Connect-Flash
- Cookie-Parser
- Cookie-Session
- Mysql2
- Sequelize
- Nodemon

## Instalação

1. Clone o repositório para sua máquina local:

    ```bash
    git clone https://github.com/Levi-21545/toughts_project_nodejs.git
    ```

2. Navegue até o diretório do projeto:

    ```bash
    cd toughts_project_nodejs
    ```

3. Instale as dependências do projeto:

    ```bash
    npm install
    ```

## Uso

1. Inicie o servidor:

    ```bash
    npm start
    ```

2. Abra o navegador e acesse `http://localhost:3000` para visualizar a aplicação.

## Estrutura de Diretórios

- `index.js`: Arquivo principal da aplicação.
- `routes/`: Contém as definições de rotas.
- `controllers/`: Contém os controladores que lidam com a lógica de negócios.
- `models/`: Contém os modelos que interagem com os dados.
- `views/`: Contém os templates Handlebars para renderização.
- `public/`: Contém arquivos estáticos como CSS e JavaScript.

## Contribuição

Sinta-se à vontade para fazer um fork do projeto e enviar pull requests. Qualquer feedback é bem-vindo!
