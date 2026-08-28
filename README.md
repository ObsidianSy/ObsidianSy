## Wesley Siqueira

Desenvolvedor full-stack, TypeScript no cliente e no servidor.

Construo sistemas de operação para empresas: as telas, a API, o modelo de
dados e o deploy. O tipo de software em que o requisito principal não é a
interface bonita, e sim o número certo na tela e o pedido que não se perde.

Franca, São Paulo.

---

### Cotaí — cotação de peças automotivas por WhatsApp

[![CI](https://github.com/ObsidianSy/Cota-/actions/workflows/ci.yml/badge.svg)](https://github.com/ObsidianSy/Cota-/actions/workflows/ci.yml)

O mecânico manda "pastilha de freio Onix 2018" no WhatsApp. O sistema
interpreta a mensagem, identifica a peça e o veículo, dispara para as lojas
da região, agrega as respostas e devolve as opções para ele escolher. Sem
aplicativo para instalar de nenhum dos lados.

Monorepo com NestJS e React, PostgreSQL com Prisma, filas em BullMQ e tempo
real com Socket.IO. Cerca de 46 mil linhas, 56 suítes de teste, integração
contínua e migrations versionadas. Em produção.

É onde os problemas foram mais difíceis: concorrência entre lojas respondendo
a mesma cotação, idempotência de webhook, isolamento entre inquilinos e
recuperação de estado quando o processo cai no meio.

**[Ver o repositório](https://github.com/ObsidianSy/Cota-)**

### Import Manager — gestão de operação de importação

Fornecedores, acompanhamento de importações, produtos, estoque, pedidos e
relatórios em um só lugar, no lugar das planilhas que divergem entre si.
Cerca de 25 mil linhas, com API tipada de ponta a ponta via tRPC e banco
versionado por migrations.

**[Ver o repositório](https://github.com/ObsidianSy/system-import)**

---

### Stack

**Front-end**
- React, TypeScript, Vite
- TailwindCSS, shadcn/ui
- TanStack Query, Zustand
- PWA, Socket.IO client

**Back-end**
- Node, NestJS, Express
- tRPC, Prisma, Drizzle
- PostgreSQL, Redis, BullMQ
- JWT, Zod

**Infra e ferramentas**
- Docker, Docker Compose
- GitHub Actions
- Turborepo, pnpm workspaces
- S3, Sentry

---

### Contato

- E-mail: SEU-EMAIL-AQUI
- LinkedIn: SEU-LINKEDIN-AQUI
