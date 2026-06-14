<h1 align="center">Jonnas Figueiredo</h1>

<p align="center">
  <b>QA Automation Engineer · SDET</b> · Brasil<br>
  Frameworks de automação confiáveis, pipelines de qualidade e IA aplicada a QA.
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/jonnas-figueiredo-576a14181">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn">
  </a>
  <a href="https://www.youtube.com/@JonnasFigo">
    <img src="https://img.shields.io/badge/YouTube-FF0000?style=flat-square&logo=youtube&logoColor=white" alt="YouTube">
  </a>
  <a href="mailto:jonnas.figueiredo01@hotmail.com">
    <img src="https://img.shields.io/badge/E--mail-D14836?style=flat-square&logo=gmail&logoColor=white" alt="E-mail">
  </a>
</p>

<p align="center">🇺🇸 <i>English version below (<a href="#-english-version">jump to English</a>)</i></p>

---

## 🛠️ Stack

<p align="center">
  <img src="https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white" alt="Java">
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript">
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white" alt="SQL">
  <img src="https://img.shields.io/badge/Playwright-2EAD33?style=flat-square&logo=playwright&logoColor=white" alt="Playwright">
  <img src="https://img.shields.io/badge/Appium-662D91?style=flat-square&logo=appium&logoColor=white" alt="Appium">
  <img src="https://img.shields.io/badge/Selenium-43B02A?style=flat-square&logo=selenium&logoColor=white" alt="Selenium">
  <img src="https://img.shields.io/badge/Cucumber-23D96C?style=flat-square&logo=cucumber&logoColor=white" alt="Cucumber">
  <img src="https://img.shields.io/badge/JUnit5-25A162?style=flat-square&logo=junit5&logoColor=white" alt="JUnit5">
  <img src="https://img.shields.io/badge/PyTest-0A9EDC?style=flat-square&logo=pytest&logoColor=white" alt="PyTest">
  <img src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white" alt="Spring Boot">
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" alt="FastAPI">
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker">
  <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white" alt="GitHub Actions">
  <img src="https://img.shields.io/badge/Allure-FF4088?style=flat-square&logo=qameta&logoColor=white" alt="Allure">
</p>

| Área | Tecnologias |
|------|-------------|
| **UI / E2E** | Playwright (multi-project, fixtures, sharding, regressão visual, a11y), Selenium, Page Object Model com composição |
| **Mobile** | Appium 2.x, Android (UiAutomator2) + iOS (XCUITest) cross-platform, gestos `mobile:`, sync só com WebDriverWait |
| **BDD** | Cucumber JVM, Gherkin, JUnit 5 Platform Suite, steps parametrizados |
| **API & integração** | REST Assured, PyTest (FastAPI TestClient), contrato HTTP + validação de estado via SQL, testes de concorrência, sem mock |
| **Linguagens** | Java (8/17/21), TypeScript (strict), Python (3.11+), SQL |
| **Backend & infra** | Spring Boot 3, MySQL, Docker multi-stage + Compose, Flyway, OpenAPI |
| **CI/CD** | GitHub Actions (matrizes com sharding, cache, deploy no Pages), Allure, ESLint type-aware, Husky + commitlint |
| **IA aplicada a QA** | Avaliação de LLMs em CI (baselines, evals determinísticos, LLM-as-judge), testes de RAG, segurança contra prompt injection, agentes para geração de testes |

---

## 👤 Sobre mim

QA Automation Engineer com mais de 3 anos de experiência, com profunda vivência em **desenvolvimento Java** e em **IA**. Construo automação que escala: Page Objects com composição, fixtures customizadas, testes sem mock contra ambientes containerizados e pipelines de CI que bloqueiam regressões antes do merge. Esse domínio dos fundamentos (E2E, mobile, API, integração, dados) me permite explorar a interseção entre **IA e qualidade de software**, tanto usando LLMs para acelerar o trabalho de QA quanto testando a qualidade dos próprios LLMs.

---

## 🚀 Projetos em destaque

🛒 **[ShopGuard](https://github.com/JonnasFigueiredo/ShopGuard)** · `Playwright` `TypeScript` · Framework E2E para e-commerce com 5 tipos de teste num só repo (funcional, mobile, regressão visual, a11y WCAG 2.1 AA e API) e CI com 6 shards paralelos. [📊 Relatório Allure ao vivo](https://jonnasfigueiredo.github.io/ShopGuard/).

📱 **[Hermes](https://github.com/JonnasFigueiredo/Hermes)** · `Java 21` `Appium` `Cucumber` · Framework E2E mobile cross-platform: os mesmos cenários Gherkin rodam em Android (UiAutomator2) e iOS (XCUITest), só os seletores divergem. 21 cenários BDD, reset de estado por cenário, gestos `mobile:` modernos e zero `Thread.sleep`.

💰 **[Midas](https://github.com/JonnasFigueiredo/Midas)** · `Java 21` `Spring Boot` `Docker` · API financeira containerizada validada por dois caminhos independentes (contrato HTTP e estado real do banco, sem mock). Invariantes contábeis via SQL e concorrência real com optimistic locking.

⚒️ **[Hefesto](https://github.com/JonnasFigueiredo/hefesto)** · `Spring Boot` `React` `WebSocket` · Console de QA com IA (open source): conecta múltiplos LLMs, integra Jira, gera casos de teste a partir de manuais/histórias e produz PDFs com evidências.

⚖️ **[Aletheia](https://github.com/JonnasFigueiredo/Aletheia)** · `Java 17` `JUnit` `Maven` · Framework de avaliação de LLMs em CI: cliente mock sem custo de API, baseline versionado e gate que quebra o build quando a qualidade regride. Provider-agnostic.

🐍 **[Pythia](https://github.com/JonnasFigueiredo/Pythia)** · `Python 3.11` `PyTest` `RAG` · Serviço RAG + suíte PyTest que o prova, da métrica de retrieval ao prompt injection, com custo zero de API no CI. 4 camadas de teste 100% determinísticas.

---

<details>
<summary><h2>🇺🇸 English version</h2></summary>

### About me

I'm a quality engineer with 3+ years of experience and a deep hands-on background in **Java development** and **AI**. I build automation that scales: Page Objects with composition, custom fixtures, mock-free testing against containerized environments, and CI pipelines that block regressions before merge. That command of the fundamentals (E2E, mobile, API, integration, data) lets me explore the intersection of **AI and software quality**, both using LLMs to accelerate QA work and testing the quality of LLMs themselves.

### Skills

| Area | Tech |
|------|------|
| **UI / E2E** | Playwright (multi-project, fixtures, sharding, visual regression, a11y), Selenium, Page Object Model with composition |
| **Mobile** | Appium 2.x, Android (UiAutomator2) + iOS (XCUITest) cross-platform, `mobile:` gestures, WebDriverWait-only sync |
| **BDD** | Cucumber JVM, Gherkin, JUnit 5 Platform Suite, parameterized steps |
| **API & integration** | REST Assured, PyTest (FastAPI TestClient), HTTP contract + SQL state validation, concurrency testing, mock-free |
| **Languages** | Java (8/17/21), TypeScript (strict), Python (3.11+), SQL |
| **Backend & infra** | Spring Boot 3, MySQL, Docker multi-stage + Compose, Flyway, OpenAPI |
| **CI/CD** | GitHub Actions (sharded matrices, caching, Pages deploys), Allure, type-aware ESLint, Husky + commitlint |
| **AI applied to QA** | LLM evaluation in CI (baselines, deterministic evals, LLM-as-judge), RAG testing, prompt-injection safety, agents for test generation |

### Featured projects

🛒 **[ShopGuard](https://github.com/JonnasFigueiredo/ShopGuard)** · `Playwright` `TypeScript` · Production-grade E2E framework for e-commerce with five test flavors in one repo (functional, mobile, visual regression, WCAG 2.1 AA, API) and a 6-shard parallel CI matrix. [Live Allure report](https://jonnasfigueiredo.github.io/ShopGuard/).

📱 **[Hermes](https://github.com/JonnasFigueiredo/Hermes)** · `Java 21` `Appium` `Cucumber` · Cross-platform mobile E2E framework: the same Gherkin scenarios run on Android (UiAutomator2) and iOS (XCUITest), only selectors diverge. 21 BDD scenarios, per-scenario state reset, modern `mobile:` gestures, zero `Thread.sleep`.

💰 **[Midas](https://github.com/JonnasFigueiredo/Midas)** · `Java 21` `Spring Boot` `Docker` · Fully containerized financial API validated through two independent paths (HTTP contract and actual DB state, no mocks). Accounting invariants via SQL and real concurrency races with optimistic locking.

⚒️ **[Hefesto](https://github.com/JonnasFigueiredo/hefesto)** · `Spring Boot` `React` `WebSocket` · Open-source AI-powered QA console: connects multiple LLMs, integrates Jira, generates test cases from manuals/user stories and produces PDF reports with evidence.

⚖️ **[Aletheia](https://github.com/JonnasFigueiredo/Aletheia)** · `Java 17` `JUnit` `Maven` · Deterministic, provider-agnostic Java framework for testing LLM quality in CI. Zero-cost mock client, committed baselines, and a quality gate that breaks the build on regression.

🐍 **[Pythia](https://github.com/JonnasFigueiredo/Pythia)** · `Python 3.11` `PyTest` `RAG` · A small RAG service plus the PyTest suite that proves it works, from retrieval metrics to prompt injection, with zero API cost in CI. Four fully deterministic test layers.

</details>
