# Jonnas Figueiredo

QA Automation Engineer, Brazil. Three years in Quality Assurance,
the last one building automation in Java and bringing AI into the day-to-day testing
work. I started on manual QA and moved into automation as the test suites grew — these
days most of what I do is framework code, API checks and CI pipelines, plus internal
talks on automation and AI for the team.

I'm aiming at QA Automation / SDET and AI QA roles.

### How I approach testing

A few things I've settled on after breaking enough suites:

- Flaky tests are bugs, not noise. I'd rather delete a test than let it lie.
- No fixed waits. Web-first assertions and explicit conditions over `waitForTimeout`.
- Page Objects should compose, not copy — shared components get injected, not duplicated.
- A test that nobody can read at 6pm on a Friday is a test that rots. Clarity first.
- AI is a power tool for scaffolding and data, not an excuse to skip thinking about coverage.

### Projects

**[ShopGuard](https://github.com/JonnasFigueiredo/ShopGuard)** — End-to-end framework
on Playwright + TypeScript (strict). 29 specs running across 5 browsers (Chromium,
Firefox, WebKit, Pixel 7, iPhone 14) and split into functional, mobile, visual,
accessibility (WCAG 2.1 AA) and API suites. Page Object Model with composition, custom
fixtures, a 6-shard GitHub Actions matrix, and Allure reports auto-published to Pages.
ESLint is set up to ban fixed waits and enforce web-first assertions.

**[hefesto](https://github.com/JonnasFigueiredo/hefesto)** — Open-source QA console that
puts AI inside the testing loop. Connects multiple LLMs, pulls context from Jira,
generates structured test cases from manuals and user stories, lets you attach evidence
per case, and exports a PDF report ready for the ticket. Specialist "agents" are plain
Markdown files; backend in Java + Spring Boot, frontend in React, local SQLite.

### Tools I reach for

Automation: Java, TypeScript, Playwright, Selenium, RestAssured, JUnit
Backend & data: Spring Boot, SQL
Workflow: GitHub Actions, Jira, Postman, Git, Allure
AI in the loop: Claude, Copilot, Cursor

### Currently

Deepening framework design and API/contract testing, and exploring how to evaluate
LLM outputs reliably (the messy part of AI QA).

### Contact

LinkedIn: [jonnas-figueiredo](https://www.linkedin.com/in/jonnas-figueiredo-576a14181/) ·
Email: jonnas.figueiredo01@hotmail.com
