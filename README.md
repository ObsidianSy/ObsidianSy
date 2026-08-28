## Wesley Siqueira

Desenvolvedor full-stack, TypeScript no cliente e no servidor.

Construo sistemas de operação para empresas: as telas, a API, o modelo de
dados e o deploy. O tipo de software em que o requisito principal não é a
interface bonita, e sim o número certo na tela e o pedido que não se perde.

Franca, São Paulo.

### Projetos

**[Cotaí](https://github.com/ObsidianSy/Cota-)** — plataforma B2B de cotação de peças automotivas via WhatsApp

O mecânico manda "pastilha de freio Onix 2018" no WhatsApp. O sistema
interpreta a mensagem, identifica a peça e o veículo, dispara para as lojas
da região, agrega as respostas e devolve as opções para ele escolher. Sem
aplicativo para instalar de nenhum dos lados.

Monorepo com NestJS e React, PostgreSQL com Prisma, filas em BullMQ, tempo
real com Socket.IO. Cerca de 46 mil linhas, 56 suítes de teste, integração
contínua e migrations versionadas. Está em produção.

É o projeto onde os problemas foram mais difíceis: concorrência entre lojas
respondendo a mesma cotação, idempotência de webhook, isolamento entre
inquilinos e recuperação de estado quando o processo cai no meio.

**[Import Manager](https://github.com/ObsidianSy/system-import)** — gestão de operação de importação

Fornecedores, acompanhamento de importações, produtos, estoque, pedidos e
relatórios em um só lugar, no lugar das planilhas que divergem entre si.
Cerca de 25 mil linhas, com API tipada de ponta a ponta via tRPC e banco
versionado por migrations.

### Stack

Cliente
React, TypeScript, Vite, TailwindCSS, shadcn/ui, TanStack Query, Zustand

Servidor
Node, NestJS, Express, tRPC, Prisma, Drizzle, PostgreSQL, Redis, BullMQ, Socket.IO

Infra
Docker, S3, integração contínua no GitHub Actions

### Contato
- E-mail: Deltagarr@gmail.com
- LinkedIn: www.linkedin.com/in/wesley-siqueira-engineer
