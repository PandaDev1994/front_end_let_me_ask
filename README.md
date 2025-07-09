# NLW Agents

Projeto desenvolvido durante o evento da Rocketseat.

## Descrição

Aplicação web construída com React, TypeScript e Vite, utilizando TailwindCSS para estilização e React Router para navegação. O projeto segue padrões modernos de componentização e organização de código.

## Principais Bibliotecas Utilizadas

- **React**: Biblioteca principal para construção da interface.
- **TypeScript**: Tipagem estática para maior segurança e produtividade.""
- **Vite**: Ferramenta de build e desenvolvimento rápido.
- **TailwindCSS**: Utilitário para estilização rápida e responsiva.
- **React Router DOM**: Gerenciamento de rotas SPA.
- **@tanstack/react-query**: Gerenciamento de estado assíncrono e cache de dados.
- **Radix UI**: Componentes acessíveis e semânticos.
- **class-variance-authority, clsx, tailwind-merge**: Utilitários para composição de classes CSS.

## Padrões de Projeto

- **Componentização**: Componentes reutilizáveis e desacoplados.
- **Hooks**: Uso de hooks para lógica de estado e efeitos colaterais.
- **Provider Pattern**: Contextos globais como React Query Client.
- **Atomic Design** (inspirado): Separação de componentes de UI e páginas.

## Setup e Configuração

1. **Clone o repositório**

   ```bash
   git clone <url-do-repo>
   cd web
   ```

2. **Instale as dependências**

   ```bash
   npm install
   ```

3. **Rode o projeto em modo desenvolvimento**

   ```bash
   npm run dev
   ```

4. **Build para produção**
   ```bash
   npm run build
   ```

## Estrutura Básica

- `src/pages`: Páginas principais da aplicação.
- `src/components`: Componentes reutilizáveis de UI.
- `src/lib`: Funções utilitárias.
- `src/assets`: Imagens e SVGs.

## Observações

- O projeto utiliza **TailwindCSS** e pode ser customizado via `src/index.css`.
- O roteamento é feito via `react-router-dom`.
- O gerenciamento de dados assíncronos é feito com **React Query**.
