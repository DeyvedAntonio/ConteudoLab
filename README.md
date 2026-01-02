# 📌 ConteúdoLab

## ConteúdoLab — publique melhor, mais rápido e com controle.

## Menu

- [🎯 Objetivo](#-objetivo)
- [📖 Descrição](#-descrição)
- [⚡ Tecnologias Utilizadas](#-tecnologias-utilizadas)
- [🏗️ Arquitetura do Projeto](#arquitetura-do-projeto)
- [🚩 Funcionalidades](#-funcionalidades)
- [🚀 Como Executar o Projeto](#-como-executar-o-projeto)
- [🔐 Variáveis de Ambiente](#-variáveis-de-ambiente)
- [🧪 Testes](#-testes)
- [📌 Status](#-status)
- [👤 Autor](#-autor)

## 🎯 Objetivo
- ConteúdoLab tem como objetivo posicionar‑se como uma solução prática e confiável de gestão de conteúdo para pequenas e médias empresas, agências e criadores, oferecendo uma experiência de publicação rápida, colaborativa e segura que gera resultados de negócio mensuráveis.

### Proposta de valor

- Acelerar a produção de conteúdo: reduzir o tempo entre ideia e publicação com fluxos claros de criação, revisão e publicação.
- Melhorar a colaboração: permitir que equipes trabalhem juntas com controle de permissões e histórico de versões.
- Aumentar a visibilidade digital: entregar conteúdo otimizado para SEO e pronto para múltiplos canais.
- Reduzir custos operacionais: simplificar a gestão de ativos e publicação para equipes sem grande dependência de TI.

### Público‑alvo

- Pequenas e médias empresas que precisam de presença digital consistente.
- Agências de marketing que buscam um painel para gerenciar múltiplos clientes.
- Criadores de conteúdo e times editoriais que valorizam velocidade e controle editorial.

### Resultados comerciais esperados

- Protótipo funcional demonstrável em ambiente público com fluxo completo de criação → publicação.
- Material de apresentação para portfólio: README, demo gravada e casos de uso com métricas (tempo de publicação, número de colaboradores).
- Prova de credibilidade: documentação clara, testes automatizados e um deploy simples que mostre maturidade operacional.

---

## 📖 Descrição
ConteúdoLab é um CMS acoplado desenvolvido em Django pensado como projeto de portfólio para demonstrar habilidades práticas em desenvolvimento web. O sistema oferece um painel administrativo completo e um front‑end integrado, permitindo criar, editar, revisar e publicar conteúdo com workflows colaborativos, controle de permissões e gerenciamento de ativos digitais. O foco do projeto é mostrar domínio em modelagem de dados, segurança web, testes automatizados, deploy com Docker e boas práticas de arquitetura (cache, CDN, storage em nuvem).

---

## ⚡ Tecnologias Utilizadas
- Python 3.13
- Django / Django REST Framework
- PostgreSQL
- Docker / Docker Compose
- HTML / CSS / JavaScript
- Git / GitHub Actions
- Poetry

---

## Arquitetura do Projeto
Como o projeto está organizado.

```
conteudolab/
├── pyproject.toml
├── poetry.lock
├── README.md
├── Dockerfile
├── docker-compose.yml
├── .env.example
├── .github/
│   └── workflows/ci.yml
├── src/
│   ├── manage.py
│   ├── conteudolab/         # project settings
│   │   ├── __init__.py
│   │   ├── settings/
│   │   │   ├── base.py
│   │   │   ├── dev.py
│   │   │   └── prod.py
│   │   ├── urls.py
│   │   └── wsgi.py
│   ├── accounts/
│   ├── content/
│   ├── media/
│   ├── core/
│   └── static/              # coletado em produção
└── tests/
```

---

## 🚩 Funcionalidades

- Cadastro, edição e exclusão de registros
- Autenticação e controle de permissões
- Relatórios e análises de dados
- Exportação de dados (CSV / Excel)
- Dashboard interativo

---

## 🚀 Como Executar o Projeto

Pré-requisitos:

- Docker e Docker Compose OU
- Python 3.13
- PostgreSQL

### Passo a passo
```
git clone https://github.com/DeyvedAntonio/ConteudoLab.git
cd ConteudoLab
docker-compose up --build
```

Acesse: `http://localhost:8000`

---

## 🔐 Variáveis de Ambiente

Crie um arquivo .env com:
```
DEBUG=True
SECRET_KEY=sua-chave
DATABASE_URL=postgres://...
```

---

## 🧪 Testes
``` pytest ```

---

## 📌 Status

🚧 Em desenvolvimento

---

## 👤 Autor

Deyved Antonio

[LinkedIn](https://linkedin.com/in/deyvedantonio)

[Instagram](https://www.instagram.com/anto.niodvd/)



