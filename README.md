<h1 align="center">Olá, eu sou o Jonnas Figueiredo </h1>

<p align="center">
  <b>QA Automation Engineer · SDET</b> · Brasil<br>
  Construo frameworks de automação confiáveis, pipelines de qualidade e ferramentas de IA aplicada a QA.
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/jonnas-figueiredo-576a14181">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn">
  </a>
  <a href="mailto:jonnas.figueiredo01@hotmail.com">
    <img src="https://img.shields.io/badge/E--mail-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="E-mail">
  </a>
</p>

> 🇺🇸 *English version below — [jump to English](#-english-version)*

---



## 🚀 Projetos em destaque

### 🛒 [ShopGuard](https://github.com/JonnasFigueiredo/ShopGuard) — Framework E2E para e-commerce
`Playwright` `TypeScript` `GitHub Actions` `Allure`

Framework de testes end-to-end production-grade com **5 tipos de teste em um repositório**: funcional, mobile, regressão visual, acessibilidade (WCAG 2.1 AA) e API.

- Page Object Model com composição de componentes e fixtures customizadas (login único via `storageState`)
- 8 projetos no Playwright config: 3 browsers desktop, 2 viewports mobile, API e setup
- CI com matriz de **6 shards paralelos** + ESLint type-aware que proíbe `waitForTimeout`
- [📊 Relatório Allure ao vivo](https://jonnasfigueiredo.github.io/ShopGuard/) publicado no GitHub Pages a cada push

### 💰 [Midas](https://github.com/JonnasFigueiredo/Midas) — API financeira + Quality Engineering stack
`Java 21` `Spring Boot` `MySQL` `Docker` `Playwright` `SQL`

API de contas e transações totalmente containerizada, validada por **dois caminhos independentes**: contrato HTTP e estado real do banco — sem mock em nenhuma camada.

- 45 testes de API/integração contra ambiente Docker (compose + healthchecks encadeados)
- Invariantes contábeis validadas via SQL direto: partida dobrada, saldo nunca negativo
- Testes de concorrência reais: DEBITs paralelos e optimistic locking (ETag/If-Match) sob corrida
- Convenções de API enterprise estilo SAP BTP: envelope de erro com `traceId`, paginação `$top/$skip`, 11 códigos de erro semânticos

### 🔥 [Hefesto](https://github.com/JonnasFigueiredo/hefesto) — Console de QA com IA (open source)
`Java` `Spring Boot` `React` `TypeScript` `WebSocket` `SQLite`

Interface web que elimina a costura manual entre ferramentas no dia a dia do QA: conecta **múltiplos LLMs** (Claude Code, Copilot, Gemini), integra Jira, gera casos de teste estruturados a partir de manuais e histórias, e produz relatórios PDF com evidências anexadas.

- Agentes especialistas definidos em arquivos `.md` com hot reload (QA Sênior, Tech Writer, Arquiteto...)
- Extração automática de casos `TC-NNN` em cards interativos com evidências por caso
- Camada de adapters plugável — adicionar um modelo é implementar uma interface

### ⚖️ [Aletheia](https://github.com/JonnasFigueiredo/Aletheia) — Framework Java de avaliação de LLMs
`Java 17` `JUnit` `Maven` `CI`

LLMs são não-determinísticos — como testá-los? Aletheia roda **evals determinísticos em CI**: cliente mock sem custo de API, baseline versionado e gate que **quebra o build quando a qualidade regride**.

- 9 evaluators componíveis: JSON schema, similaridade semântica, rubric judge, faithfulness, safety, latency/cost budget
- Provider-agnostic: OpenAI, Anthropic, DeepSeek, Ollama — troca via 2 variáveis de ambiente

---

## 🛠️ Habilidades

**Automação de testes UI/E2E** — Playwright (multi-project, fixtures, sharding, regressão visual, a11y com axe-core), Selenium, Page Object Model com composição, estratégia de tags (`@smoke`, `@critical`, `@regression`)

**Testes de API e integração** — REST Assured, Postman, contratos HTTP + validação de estado via SQL, testes de concorrência (optimistic locking, corridas reais), invariantes de domínio, testes contra ambientes containerizados sem mock

**Linguagens** — Java (17/21) e TypeScript (strict mode), com SQL para validação de dados

**Backend e infraestrutura de teste** — Spring Boot 3, MySQL, Docker multi-stage + Compose, Flyway, OpenAPI/Swagger

**CI/CD e qualidade de código** — GitHub Actions (matrizes com sharding, cache, deploy de relatórios no Pages), Allure, ESLint type-aware, Husky + commitlint + Conventional Commits

**IA aplicada a QA** — avaliação de LLMs em CI (baselines, evals determinísticos, LLM-as-judge), agentes especialistas para geração de casos de teste, integração de LLMs em fluxos de trabalho de QA

<p>
  <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" alt="Java">
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript">
  <img src="https://img.shields.io/badge/Playwright-2EAD33?style=for-the-badge&logo=playwright&logoColor=white" alt="Playwright">
  <img src="https://img.shields.io/badge/Selenium-43B02A?style=for-the-badge&logo=selenium&logoColor=white" alt="Selenium">
  <img src="https://img.shields.io/badge/JUnit5-25A162?style=for-the-badge&logo=junit5&logoColor=white" alt="JUnit5">
  <img src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white" alt="Spring Boot">
</p>
<p>
  <img src="https://img.shields.io/badge/REST_Assured-007ACC?style=for-the-badge&logo=java&logoColor=white" alt="REST Assured">
  <img src="https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white" alt="Postman">
  <img src="https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white" alt="SQL">
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker">
  <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white" alt="GitHub Actions">
  <img src="https://img.shields.io/badge/Allure-FF4088?style=for-the-badge&logo=qameta&logoColor=white" alt="Allure">
</p>

---

<details>
<summary><h2>🇺🇸 English version</h2></summary>

### About me

I'm a quality engineer focused on **automation that scales**: Page Objects with composition, custom fixtures, mock-free testing against containerized environments, and CI pipelines that block regressions before merge. Lately I've been exploring the intersection of **AI and software quality** — both using LLMs to accelerate QA work and testing the quality of LLMs themselves.

### Featured projects

**[ShopGuard](https://github.com/JonnasFigueiredo/ShopGuard)** — Production-grade E2E framework for e-commerce with five test flavors in one repo (functional, mobile, visual regression, WCAG 2.1 AA accessibility, API). Playwright + TypeScript strict, 8-project config, 6-shard parallel CI matrix, [live Allure report](https://jonnasfigueiredo.github.io/ShopGuard/) on GitHub Pages.

**[Midas](https://github.com/JonnasFigueiredo/Midas)** — Fully containerized financial API (accounts and transactions) validated through two independent paths: HTTP contract and actual database state — no mocks anywhere. 45 integration tests, accounting invariants verified via direct SQL, real concurrency races (optimistic locking with ETag/If-Match), SAP BTP-style API conventions.

**[Hefesto](https://github.com/JonnasFigueiredo/hefesto)** — Open-source AI-powered QA console. Connects multiple LLMs (Claude Code, Copilot, Gemini), integrates Jira, generates structured test cases from manuals and user stories, and produces PDF reports with attached evidence. Specialist agents defined as hot-reloadable `.md` files; pluggable LLM adapter layer.

**[Aletheia](https://github.com/JonnasFigueiredo/Aletheia)** — Deterministic, provider-agnostic Java framework for testing LLM quality in CI. Zero-cost mock client, committed baseline snapshots, and a quality gate that breaks the build on regression. Nine composable evaluators including JSON schema, semantic similarity, rubric judge, faithfulness, and safety.

### Skills

**UI/E2E test automation** — Playwright (multi-project, fixtures, sharding, visual regression, a11y with axe-core), Selenium, Page Object Model with composition, tag-based strategy.<br>
**API & integration testing** — REST Assured, Postman, HTTP contracts + SQL state validation, real concurrency testing, mock-free testing against containerized environments.<br>
**Languages** — Java (8/17/21), TypeScript (strict), SQL.<br>
**Backend & test infrastructure** — Spring Boot 3, MySQL, Docker multi-stage + Compose, Flyway, OpenAPI.<br>
**CI/CD & code quality** — GitHub Actions (sharded matrices, caching, Pages deploys), Allure, type-aware ESLint, Husky + commitlint + Conventional Commits.<br>
**AI applied to QA** — LLM evaluation in CI (baselines, deterministic evals, LLM-as-judge), specialist agents for test case generation, LLM integration into QA workflows.

</details>
