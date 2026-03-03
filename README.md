# 🥭 App Mango | Filmes & Séries

![Tecnologias](https://img.shields.io/badge/React-2026-blue?logo=react)
![Tecnologias](https://img.shields.io/badge/Node.js-Backend-green?logo=nodedotjs)
![Tecnologias](https://img.shields.io/badge/MongoDB-Database-47A248?logo=mongodb)
![Tecnologias](https://img.shields.io/badge/JWT-Auth-black?logo=jsonwebtokens)

O **App Mango** é uma plataforma inovadora projetada para entusiastas do cinema e da TV. A aplicação oferece uma experiência fluida para gerenciar, descobrir e avaliar produções, transformando a forma como os usuários interagem com seu catálogo de entretenimento favorito.

## 🚀 Recursos Principais

* **Catálogo Inteligente**: Navegação intuitiva por categorias, tendências e lançamentos de filmes e séries.
* **Pesquisa Avançada**: Motores de busca otimizados com filtros por gênero, ano de lançamento e avaliações da crítica.
* **Personalização (Favoritos)**: Sistema de curadoria individual onde o usuário pode salvar títulos para assistir mais tarde.
* **Comunidade e Críticas**: Espaço dedicado para avaliações detalhadas e notas, permitindo a troca de opiniões entre usuários.
* **Segurança**: Sistema de autenticação robusto para proteger as listas e preferências de cada perfil.

## 🛠️ Tecnologias Utilizadas

O projeto utiliza uma stack moderna focada em performance e escalabilidade:

* **Frontend**: React (ES6+) com foco em componentes reutilizáveis e interface responsiva.
* **Backend**: Node.js com framework Express para uma API RESTful rápida e segura.
* **Banco de Dados**: MongoDB (NoSQL) para armazenamento flexível de metadados de produções e usuários.
* **Autenticação**: JSON Web Tokens (JWT) para controle de sessões e rotas protegidas.

## 📋 Como Executar o Projeto

1.  **Clone o repositório**:
    ```bash
    git clone [https://github.com/ViniciusDev00/App-Mango.git](https://github.com/ViniciusDev00/App-Mango.git)
    ```
2.  **Navegue até o diretório**:
    ```bash
    cd App-Mango
    ```
3.  **Instale as dependências**:
    ```bash
    npm install
    ```
4.  **Configure as variáveis de ambiente**:
    * Crie um arquivo `.env` na raiz e configure sua `MONGO_URI` e `JWT_SECRET`.
5.  **Inicie a aplicação**:
    ```bash
    npm start
    ```

## 🏗️ Estrutura do Projeto

* `/client`: Código fonte do frontend (React).
* `/server`: Lógica do servidor, rotas da API e modelos de dados.
* `/middleware`: Filtros de segurança e validação de tokens JWT.
* `/assets`: Identidade visual e recursos estáticos da aplicação.

---
**Desenvolvido por Vinicius Biancolini** © 2026 Mango Entertainment - Transformando o Cinema Digital v1.0.0
