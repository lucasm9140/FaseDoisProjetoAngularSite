🎮 # Loja de Jogos - Angular






### Loja de jogos desenvolvida em Angular, com cadastro e listagem dinâmica de produtos utilizando JSON Server como backend fake.

## 🖥️ Demonstração

- A aplicação possui:

  - Página inicial com carrossel de promoções.

  - Grid de produtos com cards detalhados.

  - Cadastro e listagem de produtos em tempo real sem precisar recarregar a página.

  - Carrossel de promoções


## 📁 Estrutura do Projeto
projeto-angular/
├── src/app/
│   ├── inicio/               # Página inicial
│   ├── produtos/             # Wrapper de produtos
│   ├── lista-produtos/       # Lista de produtos
│   ├── cadastro-produto/     # Formulário de cadastro
│   ├── produto.service.ts    # Serviço CRUD
│   └── app-routing.module.ts # Rotas
├── assets/                   # Imagens e recursos
├── db.json                    # Banco de dados fake
├── server.js                  # JSON Server
└── package.json               # Dependências

## ⚡ Tecnologias

- Angular

- Angular Material

- Bootstrap 5

- JSON Server

- TypeScript, HTML5 e CSS3

## 🚀 Como rodar o projeto

- Clone o repositório

- git clone https://github.com/lucasm9140/FaseDoisProjetoAngularSite.git
- cd ProjetoAngularSiteJogos/projeto-angular/loja-games


- Instale as dependências

- npm install


- Inicie o JSON Server

- node server.js


- Inicie a aplicação Angular

- ng serve


  - Acesse em: http://localhost:4200

## 🔄 Funcionalidades

- Cadastro de produtos com atualização em tempo real.

- Listagem de produtos armazenados no db.json.

- Layout responsivo com Angular Material e Bootstrap.

- Página inicial com carrossel de promoções e grid de jogos.

## Rotas implementadas:

- /inicio → página inicial

- /produtos → wrapper de produtos

- /lista → lista de produtos

- /cadastrar → cadastro de produtos

- /login → página de login (em construção)

## 🛠️ Contribuição

- Siga o fluxo:

- Fork → Branch → Commit → Push → Pull Request

- Abra uma issue descrevendo a melhoria ou bug.

- Todas as contribuições serão revisadas antes de integrar ao projeto.

-📄 Licença


MIT Licens

