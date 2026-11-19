## Opa! Eu sou o Eduardo Ramos, mais conhecido como DuXis 👋

**Desenvolvedor Backend com foco em Python e IA.** Há 3 anos na [Nube](https://www.nube.com.br/), onde comecei no estágio e hoje atuo como Analista e Desenvolvedor de Sistemas: APIs, banco de dados, busca com Elasticsearch e integrações de pagamento.

Fora do trabalho, construo e coloco no ar meus próprios sistemas. 👇

---

### 🚀 Projetos

> A maior parte do código é privada. Aqui está o que cada projeto faz e como foi construído.

#### 🤖 Central de Atendimento com IA (SaaS multi-tenant)
Caixa de entrada única para WhatsApp, Telegram, e-mail e webchat, com CRM, automações, SLA e um assistente de IA que responde sozinho e passa a conversa para um atendente quando precisa.
- Assistente com **LLM local (Ollama)** e **RAG** sobre a base de conhecimento de cada empresa (embeddings com **pgvector**)
- **Multi-tenant com Row-Level Security** no PostgreSQL, com teste automatizado garantindo que um cliente nunca vê dado de outro
- Monólito modular com fronteiras verificadas automaticamente, event sourcing nas conversas, 2FA, auditoria e 400+ testes

`Python` `FastAPI` `SQLAlchemy async` `PostgreSQL` `pgvector` `Ollama` `React` `Docker`

#### 🔥 [ChamaPromo](https://chamapromo.com.br): plataforma multi-tenant de promoções
Capta ofertas de mais de 10 lojas, pontua e verifica cada uma e publica automaticamente em Telegram, WhatsApp, Discord e X, com regras por canal e links de afiliado por parceiro. Projeto em dupla; fiquei com a arquitetura multi-tenant, a integração com WhatsApp, o deploy em Docker e a segurança (credenciais cifradas, correção de SSRF e força bruta, proteção contra race condition e DDoS).

`Python` `FastAPI` `PostgreSQL` `Next.js` `Docker` `Nginx`

#### 🎮 [DUXISmon](https://duxismon.com.br): jogo integrado ao chat da Twitch
Jogo de capturar e evoluir monstros pelo chat das minhas lives, com site próprio: login OAuth da Twitch, batalhas por turnos em tempo real via WebSocket e ranking Elo. Roda em Docker numa VPS Linux, exposto via Cloudflare Tunnel, com 400+ testes.

`Python` `WebSocket` `OAuth` `Docker` `Cloudflare` `pytest`

#### ✂️ CorteJá: agendamento para barbearias
Clientes encontram barbearias e marcam horário; barbeiros gerenciam agenda, clientes, serviços e financeiro num painel. Autenticação JWT própria e pagamentos com Mercado Pago.

`Next.js` `TypeScript` `Prisma` `PostgreSQL`

---

### 🛠️ Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Elasticsearch](https://img.shields.io/badge/Elasticsearch-005571?style=for-the-badge&logo=elasticsearch&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![LLMs](https://img.shields.io/badge/LLMs_%26_RAG-412991?style=for-the-badge&logo=openai&logoColor=white)

---

### 📫 Contato

<a href="https://www.linkedin.com/in/devduxis/" target="_blank"><img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white"></a>
<a href="mailto:eduardoramos45r@gmail.com"><img src="https://img.shields.io/badge/-Gmail-%23333?style=for-the-badge&logo=gmail&logoColor=white"></a>
<a href="https://www.instagram.com/_duxis/" target="_blank"><img src="https://img.shields.io/badge/-Instagram-%23E4405F?style=for-the-badge&logo=instagram&logoColor=white"></a>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/DuXisXl/DuXisXl/output/github-contribution-grid-snake-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/DuXisXl/DuXisXl/output/github-contribution-grid-snake.svg">
  <img alt="github contribution grid snake animation" src="https://raw.githubusercontent.com/DuXisXl/DuXisXl/output/github-contribution-grid-snake.svg">
</picture>
