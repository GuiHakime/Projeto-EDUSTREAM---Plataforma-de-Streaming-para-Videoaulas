EDUSTREAM - Plataforma de Streaming para Videoaulas

PROJETO elaborado para TG

📚 Descrição

EDUSTREAM é uma plataforma de streaming de videoaulas voltada para professores e alunos, desenvolvida como protótipo funcional com foco em acessibilidade e facilidade de uso. A plataforma permite upload, gerenciamento e visualização de conteúdos educacionais, com uma interface responsiva adaptada para dispositivos móveis e desktops.
🎯 Objetivo do Projeto

O objetivo deste projeto é fornecer uma solução de ensino a distância que facilite o acesso a videoaulas, atendendo à crescente demanda por plataformas educacionais online. Com o EDUSTREAM, busca-se promover uma educação de qualidade e acessível, proporcionando uma experiência fluida e agradável para os usuários.
📝 Justificativa

O aumento da procura por ensino remoto, especialmente após a pandemia, impulsionou a necessidade de plataformas robustas e intuitivas para o ensino a distância. EDUSTREAM vem para preencher essa lacuna, oferecendo aos alunos uma plataforma onde podem acessar conteúdos de alta qualidade a qualquer momento.
📋 Escopo

As principais funcionalidades da plataforma incluem:

    Desenvolvimento de uma interface web responsiva para upload e visualização de videoaulas.
    Suporte a dispositivos móveis e desktops.
    Personalização de perfis de usuários (professores e alunos).

🖥️ Tecnologias Utilizadas

    React: Biblioteca para criação de interfaces de usuário.
    Tailwind CSS: Framework de CSS para estilização rápida e responsiva.
    React Router: Biblioteca para navegação entre as páginas da aplicação.
    AOS (Animate on Scroll): Biblioteca para animações suaves ao rolar a página.

🏛️ Arquitetura do Projeto

O projeto está estruturado em módulos que facilitam a reutilização e a manutenção:

    Páginas: Estrutura de rotas para principais páginas, como Home, Login, Aulas, Dashboard.
    Componentes: Componentes reutilizáveis para funcionalidades da plataforma.
    Modais: Modais para diálogos e interações do usuário.
    Layout e Navegação: O Layout geral inclui uma Sidebar para facilitar a navegação.
    Contexto: Uso do Context API para gerenciamento de estado global (ex: DrawerContext).
    ClassesData: Centraliza dados e simplifica a renderização de conteúdos.

🚀 Estrutura de Rotas do Projeto

Aqui estão as principais rotas implementadas no projeto:

    / - Página inicial (Home)
    /movies - Página de lista de filmes
    /movie/:id - Página para visualização de detalhes de um filme específico
    /watch/:id - Página para assistir ao filme
    /login - Página de login
    /register - Página de cadastro
    /profile - Perfil do usuário
    /password - Gerenciamento de senha
    /favorites - Lista de filmes favoritos
    /movieslist - Lista completa de filmes para administração
    /dashboard - Dashboard de administração
    /categories - Categorias de filmes
    /users - Gerenciamento de usuários
    /addmovie - Adição de novos filmes
    * - Página de erro (Not Found)

🛠️ Como Executar o Projeto Localmente

    Clone o repositório:

git clone https://github.com/seu-usuario/EDUSTREAM.git

Navegue até a pasta do projeto:

cd EDUSTREAM

Instale as dependências:

npm install

Execute o projeto:

    npm start

    Acesse o projeto em http://localhost:3000.

📂 Estrutura de Pastas

    src/
        Components/ - Componentes reutilizáveis da plataforma.
        Screens/ - Páginas principais da plataforma.
        Context/ - Contextos globais para gerenciamento de estado.
        App.js - Configuração das rotas e estrutura base do aplicativo.

✨ Funcionalidades

    Upload e visualização de videoaulas: Professores podem adicionar vídeos e os alunos têm acesso para visualização.
    Responsividade: Adaptado para telas de dispositivos móveis e desktops.
    Painel administrativo: Gestão de aulas, categorias e usuários.
    Favoritos e perfil personalizado: Alunos podem salvar videoaulas como favoritas e personalizar suas preferências.
