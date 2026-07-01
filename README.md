# Gabinete Digital

Sistema de Apoio à Decisão para Gestores Públicos — versão inicial do repositório.

Visão geral

O Gabinete Digital é um SaaS pensado para Diretores de Administração e Planejamento dos Institutos Federais. Este repositório contém uma estrutura inicial em monorepo com foco no frontend Next.js 15 + TypeScript + TailwindCSS e uma arquitetura limpa, além de scaffolding para backend, banco de dados e documentação.

Estrutura

- frontend/: aplicação Next.js 15 (App Router) com TypeScript, Tailwind e Supabase.
- backend/: espaço para serviços backend (placeholder).
- database/: schema, seed e migrations iniciais.
- docs/: documentação do produto, roadmap, API e banco de dados.
- design/: tokens e arquivos de design (placeholder).
- scripts/: scripts utilitários (inicialização, deploy, etc.).

Como iniciar (desenvolvimento local)

1. Clone o repositório.
2. Copie os arquivos de ambiente de exemplo:

   cd frontend
   cp .env.local.example .env.local

3. Instale dependências:

   npm install

4. Execute em modo de desenvolvimento:

   npm run dev

Configurações importantes

- Autenticação: o scaffold usa Supabase para autenticação via OAuth (Google). Configure as variáveis de ambiente no frontend/.env.local.
- Deploy: pensado para Cloudflare Pages; veja os arquivos de CI/CD e a documentação em docs/.

Licença

MIT — veja o arquivo LICENSE para detalhes.
