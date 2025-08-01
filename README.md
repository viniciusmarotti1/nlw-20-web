🤖 Projeto - Agentes Inteligentes na Web
Este projeto demonstra a utilização de agentes inteligentes em uma aplicação web moderna, integrando tecnologias para gerenciamento de estado, interface de usuário e comunicação com backend.

🚀 Tecnologias
React 19.1 – Biblioteca para construção de interfaces de usuário

TypeScript 5.8 – Superset do JavaScript com tipagem estática

Vite 7.0 – Build tool e servidor de desenvolvimento rápido

TailwindCSS 4.1 – Framework CSS utility-first

React Router Dom 7.6 – Biblioteca de roteamento para SPA

TanStack React Query 5.8 – Gerenciamento de estado do servidor e cache

Radix UI – Componentes primitivos acessíveis

Shadcn/ui – Sistema de componentes

Lucide React – Biblioteca de ícones

📂 Padrões de Projeto
Component-based Architecture – Arquitetura baseada em componentes React

File-based Routing – Roteamento baseado em arquivos com React Router

Server State Management – Controle de dados remotos com React Query

Variant-based Components – Componentes com variantes usando CVA

Composition Pattern – Padrão de composição com Radix Slot

Path Aliasing – Alias de caminhos (@/ aponta para src/)

⚙️ Configuração do Projeto
Pré-requisitos
Node.js (versão 18 ou superior)

npm ou yarn

Instalação
Clone o repositório:

bash
Copy
Edit
git clone https://seu-repositorio.git
cd nome-do-projeto
Instale as dependências:

bash
Copy
Edit
npm install
Execute o servidor de desenvolvimento:

bash
Copy
Edit
npm run dev
Acesse a aplicação em http://localhost:5173

📜 Scripts Disponíveis
npm run dev – Inicia o servidor de desenvolvimento

npm run build – Gera a build de produção

npm run preview – Faz o preview da build de produção

🔗 Backend
A aplicação consome uma API que deve estar rodando na porta 3333.
Certifique-se de que o backend esteja configurado e executando antes de iniciar o frontend.

🛠️ Estrutura do Projeto
bash
Copy
Edit
src/
├── components/ui/ # Componentes de interface
├── pages/ # Páginas da aplicação
├── lib/ # Utilitários e configurações
└── app.tsx # Componente raiz
