# FLL Organizer

Plataforma organizacional para equipes FIRST LEGO League, inspirada em JIRA, Google Keep e Google Agenda.

## Inclui

- Dashboard inicial
- Kanban de tarefas
- Ranking visível no dashboard
- Competidor do Mês
- Pontos por tarefas concluídas
- Níveis
- Notas estilo Keep
- Agenda
- PostgreSQL + Prisma
- Persistência no banco
- APIs de tarefas, notas e eventos
- Layout responsivo
- Seed com dados de exemplo

## Como instalar

1. Instale Node.js 20+.
2. Crie um banco PostgreSQL chamado `fll_organizer`.
3. Copie `.env.example` para `.env` e altere a DATABASE_URL.
4. No terminal, na pasta do projeto:

```bash
npm install
npx prisma generate
npx prisma db push
npm run db:seed
npm run dev
```

5. Abra http://localhost:3000

## GitHub

Envie todos os arquivos e pastas deste projeto para o repositório.
NÃO envie `.env`.

O GitHub armazena o código; o PostgreSQL armazena os dados.
