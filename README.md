# 🥭 App Mango | Filmes & Séries (Powered by Supabase)

![Tecnologias](https://img.shields.io/badge/React-2026-blue?logo=react)
![Tecnologias](https://img.shields.io/badge/Supabase-Backend-3ECF8E?logo=supabase)
![Tecnologias](https://img.shields.io/badge/TypeScript-Logic-3178C6?logo=typescript)
![Tecnologias](https://img.shields.io/badge/Tailwind-UI-06B6D4?logo=tailwindcss)

O **App Mango** é uma plataforma inovadora para entusiastas do cinema e da TV, focada em oferecer uma experiência fluida de descoberta e gerenciamento de conteúdo. Utilizando a infraestrutura do **Supabase**, a aplicação garante sincronização em tempo real e alta performance para o usuário final.

## 🚀 Recursos Principais

* **Catálogo Inteligente**: Navegação intuitiva por categorias, tendências e lançamentos.
* **Gestão de Favoritos**: Salve suas produções preferidas em sua conta pessoal com persistência de dados.
* **Pesquisa Avançada**: Filtros otimizados para encontrar títulos por gênero, ano e avaliação.
* **Autenticação Segura**: Gerenciamento de usuários via Supabase Auth (E-mail/Senha ou Social).
* **Avaliações e Críticas**: Espaço para os usuários deixarem notas e opiniões sobre as obras.

## 🛠️ Tecnologias Utilizadas

A stack foi escolhida para proporcionar escalabilidade e uma experiência de desenvolvimento ágil:

* **Frontend**: React 18 com **TypeScript** para maior segurança no código.
* **Backend as a Service (BaaS)**: **Supabase** para banco de dados PostgreSQL e Autenticação.
* **Estilização**: Tailwind CSS e Shadcn/UI para uma interface moderna e responsiva.
* **Gerenciamento de Estado**: TanStack Query (React Query) para sincronização eficiente com o banco.

## 📋 Como Executar o Projeto

1.  **Clone o repositório**:
    ```bash
    git clone [https://github.com/ViniciusDev00/App-Mango.git](https://github.com/ViniciusDev00/App-Mango.git)
    ```
2.  **Instale as dependências**:
    ```bash
    npm install
    ```
3.  **Configuração do Supabase**:
    * Crie um projeto no [Supabase](https://supabase.com/).
    * Crie um arquivo `.env` na raiz com suas credenciais:
        ```env
        VITE_SUPABASE_URL=sua_url_aqui
        VITE_SUPABASE_PUBLISHABLE_KEY=sua_chave_aqui
        ```
4.  **Inicie a aplicação**:
    ```bash
    npm run dev
    ```

## 🏗️ Estrutura do Projeto

* `/src/pages`: Páginas da aplicação (Home, Login, Detalhes).
* `/src/components`: Componentes de interface e UI.
* `/src/integrations`: Configuração do cliente Supabase e definições de tipos.
* `/src/hooks`: Hooks personalizados para gerenciamento de dados e notificações.

---
**Desenvolvido por Vinicius Biancolini** © 2026 Mango Entertainment - Transformando o Cinema Digital v1.0.0
