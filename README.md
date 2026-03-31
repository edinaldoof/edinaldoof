<div align="center">

# Edinaldo Filho

**Full Stack Engineer · Systems Architect**

Transformo operações institucionais complexas em plataformas digitais que funcionam em produção.

[![LinkedIn](https://img.shields.io/badge/-edinaldo--filho-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/edinaldo-filho/)
[![Email](https://img.shields.io/badge/-Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:edinaldofilho2021@ufpi.edu.br)

</div>

---

<img align="right" width="280" src="https://github-readme-stats.vercel.app/api?username=edinaldoof&show_icons=true&include_all_commits=true&count_private=true&hide_border=true&hide_title=true&bg_color=00000000&icon_color=2563eb&text_color=555&hide=contribs"/>

### Sobre

Responsável pela TI da **FADEX** — Fundação de Apoio da Universidade Federal do Piauí, Teresina-PI.

Projeto e mantenho sozinho uma plataforma em produção com **12+ aplicações** Next.js que cobre toda a operação da fundação — do controle financeiro à automação bancária com IA.

**Formação**
- MBA Data Science & Analytics — **USP/Esalq**
- Administração — **UFPI**

```
27 repositórios · 200k+ linhas de código · 15+ serviços em produção
```

<br clear="right"/>

---

### Projetos Principais

> A maioria é privado por conter dados institucionais.

<details>
<summary><b>Plataforma FADEX</b> — Monorepo com 12+ apps em produção &nbsp; <code>privado</code></summary>
<br/>

Monorepo **Turborepo** com Next.js 16, React 19, TypeScript strict, Prisma, PostgreSQL + SQL Server. Arquitetura **multi-zones** onde cada módulo é uma app Next.js independente com porta própria, unificadas via proxy no portal central.

| Módulo | O que faz |
|--------|-----------|
| **Portal Central** | SSO Google OAuth, dashboard unificado, proxy multi-zone para todos os módulos |
| **Gestão de Projetos** | Acompanhamento de 100+ projetos acadêmicos, controle de vigência, notificações automáticas por e-mail |
| **Controle Financeiro** | Entradas/saídas com análise por instituição e projeto, exportação Excel/PDF |
| **Ressarcimentos** | Organograma interativo com React Flow, cálculo proporcional, visão por instituição |
| **Extratos BB** | Integração com API do Banco do Brasil, automação de consulta via Chrome remoto + Bridge WebSocket |
| **Credenciamentos** | Workflow completo de credenciamento institucional com validação documental |
| **Faturas NFSe** | Emissão e gestão de notas fiscais de serviço eletrônicas |
| **Disparo de E-mails** | Motor batch com rate limiting adaptativo, templates customizáveis, agendamento, SSE tracking |
| **Viagens** | Extração inteligente de PDFs via Gemini AI, geração de PDF profissional, chatbot de ajuda |
| **Certidões** | Emissão automática de ~30 tipos de certidão via API Infosimples + Google Drive |
| **Protocolos** | Dashboard executivo com 20k+ registros, timeline de tramitação, análise temporal por setor |
| **GED** | Gestão eletrônica de documentos integrada ao Google Drive, API em Go |

**Stack:** Next.js 16 · React 19 · TypeScript · Tailwind v4 · Prisma · PostgreSQL · SQL Server · PM2 · Linux

</details>

<details>
<summary><b>SIGEM</b> — Sistema de Gestão de Emendas Parlamentares &nbsp; <code>privado</code></summary>
<br/>

Plataforma **SaaS multi-tenant** para gestão do ciclo completo de emendas parlamentares municipais — da indicação à prestação de contas. Cada município opera como tenant isolado com banco próprio via subdomínio.

- Workflow de **24 status em 5 fases** com transições validadas
- NUE (Número Único de Emenda) com Módulo 97 ISO 7064
- Portal de Transparência público com dados abertos e dashboards
- Conformidade com CF/88, LC 210/2024, IN TCE-PI 05/2025
- **45 modelos Prisma**, 2.000+ linhas de schema
- Auth com 2FA TOTP, Redis para cache/rate limit, S3 para storage

**Stack:** Next.js 16 · TypeScript · PostgreSQL 16 · Prisma · Redis · S3 · Vitest

</details>

<details>
<summary><b>CatalisaICT</b> — Plataforma de Gestão de Bolsistas e Projetos ICT &nbsp; <code>privado</code></summary>
<br/>

Sistema completo para gestão de programas de bolsas de inovação científica e tecnológica. Dois perfis de acesso: **gestor** e **bolsista**.

- Dashboard com métricas, relatórios e acompanhamento por projeto
- Gestão de bolsistas, pagamentos em lotes, documentos e anexos
- Inbox para comunicação, cronograma com protocolo
- Integração com Google Drive para armazenamento

**Stack:** Next.js · TypeScript · PostgreSQL · Prisma · NextAuth · Google Drive API

</details>

<details>
<summary><b>Telégrafo</b> — Disparo de Mensagens WhatsApp &nbsp; <code>privado</code></summary>
<br/>

Sistema de disparo de mensagens WhatsApp com suporte a múltiplos provedores simultâneos.

- **3 provedores:** Twilio, Evolution API (Baileys), WhatsApp Business Cloud (Meta)
- Agendamento de campanhas, templates, gestão de contatos

**Stack:** Next.js 16 · React 19 · PostgreSQL · Prisma · Tailwind

</details>

<details>
<summary><b>Ralph AI</b> — Agente Supervisor Autônomo &nbsp; <code>privado</code></summary>
<br/>

Agente de IA supervisor que orquestra sub-agentes para manutenção autônoma do monorepo FADEX.

- Circuit breaker, rate limiting proativo, progress tracking
- Detecção de atividade, completude e sub-agentes
- Iteration logger e session lock para controle de concorrência

**Stack:** TypeScript · Node.js

</details>

---

### Projetos Menores

| Projeto | Stack | Descrição |
|---------|-------|-----------|
| **Notas FADEX** | Next.js, Prisma | Gestão de notas fiscais com upload, status automático e integração Google Drive |
| **Processos FADEX** | React, Recharts | Dashboard analítico de protocolos com visualização de 20k+ tramitações |
| **Viagens v1** | React, Firebase, Gemini | Primeira versão do sistema de viagens com extração IA e chatbot |
| **PDF Bank Converter** | Python | Converte relatórios bancários em PDF para dados estruturados |
| **Doc fade1** | Python | Documentação automatizada do banco legado SAGI — 18 queries documentadas |
| **Extratos BB** | Python | Scripts de automação para extração de extratos do Banco do Brasil |
| **Conta Bancária** | React | Componente educacional que explica a composição de contas bancárias |

---

### Stack

<div align="center">

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=fff)
![Next.js](https://img.shields.io/badge/Next.js-000?style=flat-square&logo=nextdotjs)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=000)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=fff)
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=fff)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=fff)
![Tailwind](https://img.shields.io/badge/Tailwind-06B6D4?style=flat-square&logo=tailwindcss&logoColor=fff)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=fff)
![SQL Server](https://img.shields.io/badge/SQL_Server-CC2927?style=flat-square&logo=microsoftsqlserver&logoColor=fff)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=fff)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=000)
![Turborepo](https://img.shields.io/badge/Turborepo-EF4444?style=flat-square&logo=turborepo&logoColor=fff)
![PM2](https://img.shields.io/badge/PM2-2B037A?style=flat-square&logo=pm2)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=fff)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=000)
![AWS S3](https://img.shields.io/badge/S3-569A31?style=flat-square&logo=amazons3&logoColor=fff)
![Gemini](https://img.shields.io/badge/Gemini-8E75B2?style=flat-square&logo=googlegemini&logoColor=fff)
![Claude](https://img.shields.io/badge/Claude-D97757?style=flat-square&logo=anthropic&logoColor=fff)
![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=flat-square&logo=powerbi&logoColor=000)

</div>

---

<div align="center">
  <img height="150" src="https://github-readme-stats.vercel.app/api/top-langs/?username=edinaldoof&layout=compact&langs_count=8&hide_border=true&bg_color=00000000&text_color=555&title_color=2563eb"/>
  &nbsp;&nbsp;
  <img height="150" src="https://github-readme-streak-stats.herokuapp.com/?user=edinaldoof&hide_border=true&background=00000000&ring=2563eb&fire=2563eb&currStreakLabel=555"/>
</div>

<br/>

<div align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=edinaldoof&theme=minimal&area=true&hide_border=true&bg_color=00000000&line=2563eb&point=2563eb" width="92%" />
</div>

<div align="center">
  <br/>
  <img src="https://komarev.com/ghpvc/?username=edinaldoof&color=2563eb&style=flat-square&label=visitors" />
  <br/><br/>
  <sub>A maioria dos repositórios são privados por conterem dados institucionais sensíveis.</sub>
</div>
