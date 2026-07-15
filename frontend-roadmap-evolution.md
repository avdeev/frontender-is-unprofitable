# Эволюция дорожной карты фронтенд-разработчика

> **Связанные документы:** [frontend-evolution-index.md](frontend-evolution-index.md) — навигация и ретроспективный анализ «что не попало в роадмап» | [frontend-profession-evolution.md](frontend-profession-evolution.md) — эволюция профессии (6 эпох, данные опросов)

Анализ изменений `src/data/roadmaps/frontend/frontend.json` и предшествующих файлов на основе истории git-коммитов репозитория (создан 2017-03-15).

## Год — Список требований

### 2017 (март) — начальная версия (Balsamiq-мокап)

**Базовые технологии:**
- HTML, CSS, JavaScript, jQuery
- ES6
- Responsive Web Development

**CSS:**
- Препроцессоры: Sass, Less, Stylus, PostCSS
- Фреймворки: Bootstrap, Foundation, Materialize CSS, Semantic UI, Material UI, Material Design
- Архитектура/методологии: OOCSS, BEM, SMACSS, SUITCSS, Systematic CSS
- Углублённое изучение CSS3: Flexbox, Grids, Transforms, Transitions, Gradients, Rotate, Skew, Scale

**Инструменты:**
- Task Runners: Gulp, Grunt, npm scripts
- Package Manager: npm, Yarn
- Module Loader/Bundler: Webpack, RequireJS/AMD, Browserify

**Фреймворки (на выбор):**
- AngularJS, React, Vue.js, Preact, Inferno, Ember JS

**Тестирование:** Jest, Mocha, Jasmine

**Типизация:** TypeScript, Flow

**Управление состоянием:** Flux, Redux

**Дополнительно:** SVG, D3, Design Patterns, GOF Design Patterns, Regex

---

### 2018 (март) — реструктуризация в пошаговое руководство

**Базовые основы:**
- Internet: How does the internet work, HTTP, Domain Name, Hosting, DNS, Browsers
- HTML: Learn the basics, Writing Semantic HTML, Forms and Validations, Accessibility, SEO Basics
- CSS: Learn the basics, Making Layouts, Responsive Design, Media Queries
- JavaScript: Syntax and basic constructs, Learn DOM Manipulation, Learn Ajax (XHR), ES6+ and modular JavaScript, Understand concepts (hoisting, event bubbling, scope)

**Version Control:** Git (опционально), GitHub

**Package Managers:** npm, Yarn

**CSS:**
- Architecture: BEM, OOCSS, SMACSS, SUITCSS, Atomic
- Preprocessors: Sass (рекомендация), Less, PostCSS, Stylus
- Frameworks: Bootstrap, Materialize CSS, Bulma

**Build Tools / Task Runners:**
- Task Runners: Gulp, npm scripts (Grunt убран)
- Build tools: Webpack, Rollup, Parcel (Browserify и RequireJS/AMD убраны)

**Pick a Framework:** React, Angular (Angular 2+, не AngularJS), Vue.js (AngularJS, Ember JS, Preact, Inferno убраны)

**Управление состоянием:** Redux/MobX, ngrx, Vuex, Rx.js

**Server Side Rendering:** Next.js, Nuxt.js, After.js

**Static Type Checkers:** TypeScript, Flow

**Testing your Apps:** Jest, Mocha, Karma, Protractor, Enzyme

**Progressive WebApps** (новое)

**Performance:** измерение и улучшение производительности приложения

**Linters:** ESLint, JSHint, JSLint, JSCS

**jQuery** — помечен как опциональный

---

### 2019 (выпущен в декабре 2018) — крупная переработка

**Internet:** how browsers work, DNS, HTTP, hosting

**HTML:** Writing Semantic HTML, Forms and Validations, Accessibility, Basic SEO

**CSS (детально):**
- Syntax and Basic Constructs
- Box Model, Display, Positioning, Floats
- Flex Box, CSS Grid, Media Queries
- Making Layouts, Responsive Websites
- Pre-processors: SASS, Less, PostCSS, Stylus
- Frameworks: Bootstrap, Bulma, Materialize CSS, Semantic UI
- Architecture: BEM, OOCSS, SMACSS, SUITCSS
- **CSS in JS (новое):** Styled Components, Radium, Emotion, Glamorous, CSS Modules

**JavaScript:** Basics, Learn DOM Manipulation, Fetch API / Ajax (XHR), ES6+ and modular JavaScript, Understand the concepts (hoisting, event bubbling, scope)

**Package Managers:** npm, yarn

**Module Bundlers / Build Tools:** Webpack, Rollup, Parcel

**Pick a Framework:** React, Angular, Vue.js

**Type Checkers:** TypeScript, Flow

**Testing:** Unit, Integration, Functional; Jest, Mocha, Jasmine, Karma, Protractor, **Cypress, Ava, Chai** (новые), Enzyme

**Server Side Rendering:** Next.js, Nuxt.js, After.js

**Static Site Generators (новое):** GatsbyJS

**Progressive Web Apps (расширено):** Service Workers, Web Sockets, Notifications, Payments, Storage, Device Orientation, Credentials, APIs used in PWAs

**Performance Metrics (новый раздел):** RAIL Model, PRPL Pattern, Calculating/Measuring, Using DevTools, Using Lighthouse

**Linters and Formatters:** ESLint, **Prettier** (новое), JSHint, JSLint, JSCS

**Web Assembly (новое)**

**Desktop Applications (новое):** Electron, Carlo, Proton Native

**Mobile Applications (новое):** React Native, NativeScript

---

### 2023 (январь — миграция в веб-формат roadmap.sh, август — обновление)

Роадмап перенесён с Balsamiq на собственную платформу roadmap.sh. Крупное обновление содержания:

**Internet:** How does the internet work, What is HTTP, What is Domain Name, What is hosting, DNS and how it works, Browsers and how they work

**HTML:** Learn the basics, Writing Semantic HTML, Forms and Validations, Accessibility, SEO Basics

**CSS:** Learn the basics, Making Layouts, Responsive Design (детальные CSS-подтемы убраны ради краткости)

**JavaScript:** Learn the Basics, Learn DOM Manipulation, Fetch API / Ajax (XHR)

**Version Control Systems (новый раздел):** Git, VCS Hosting (GitHub, GitLab, Bitbucket)

**Package Managers:** npm, **pnpm** (новое), yarn

**CSS Architecture:** BEM и др.

**CSS Preprocessors:** Sass, PostCSS

**Writing CSS:** **Tailwind** (Bootstrap/Materialize заменены), Radix UI, Shadcn UI

**Build Tools:** **Vite, esbuild, SWC** (новые), Webpack, Rollup, Parcel

**Pick a Framework (расширен):** React, Vue.js, Angular, **Svelte, Solid JS, Qwik** (новые)

**SSR / Frameworks:** Next.js, Nuxt.js, **Remix, Svelte Kit, Astro** (новые)

**Static Site Generators:** Eleventy, **Hugo, Jekyll** (новые), Vuepress, Astro

**Testing:** Jest, **Cypress, Playwright, Vitest** (новые)

**Type Checkers:** TypeScript (Flow убран)

**GraphQL (новый раздел):** Apollo, Relay Modern

**Web Security Basics (новый раздел):** OWASP Security Risks, CORS, HTTPS, Content Security Policy, Authentication Strategies, JWT/OAuth/SSO/Basic Auth/Session Auth

**Web Components (новое):** Custom Elements, Shadow DOM, HTML Templates

**Browser APIs (новое):** Location, Storage, Notifications, Device Orientation, Payments, Credentials

**PWAs:** Service Workers, Web Sockets, Server Sent Events, Storage, Notifications, Device Orientation, Payments, Credentials

**Performance Metrics:** RAIL Model, PRPL Pattern, Using DevTools, Using Lighthouse, Performance Best Practices

**Desktop Applications:** Electron, **Tauri** (новое, Carlo/Proton Native убраны)

**Mobile Applications:** React Native, **Flutter, Ionic** (новые, NativeScript убран)

**Linters and Formatters:** ESLint, Prettier

---

### 2024 (июнь) — перерисовка в новом редакторе (React Flow формат)

Формат изменён с Balsamiq на React Flow (`nodes`/`edges`). Структура очищена и консолидирована:

**Сохранены:** Internet, HTML, CSS, JavaScript, Version Control Systems, Package Managers (npm, pnpm, yarn), CSS Architecture, CSS Preprocessors, Writing CSS (Tailwind), Build Tools (Vite, esbuild, SWC, Webpack, Rollup, Parcel), Pick a Framework (React, Vue.js, Angular, Svelte, Solid JS, Qwik), SSR (Next.js, Nuxt.js, Svelte Kit, Astro), Static Site Generators (Eleventy, Vuepress), Testing (Jest, Cypress, Playwright, Vitest), Type Checkers (TypeScript), GraphQL (Apollo, Relay Modern), Web Security (OWASP, CORS, HTTPS, CSP, Authentication, JWT/OAuth/SSO), Web Components, Browser APIs, PWAs, Performance Metrics, Desktop Apps (Electron, Tauri), Mobile Apps (React Native, Flutter, Ionic), Linters (ESLint, Prettier)

**Добавлено:** react-router, Fullstack (связанный трек), Browser APIs (выделено отдельно), Measure & Improve Perf.

**Убрано:** Hugo, Jekyll, NativeScript, Remix, Radix UI, Shadcn UI (перенесены в примечание про CSS-in-JS/Panda CSS/Shadcn/Mantine), раздел Task Runners, Universal, Flow, секция про CSS-in-JS/Styled Components (свернута в примечание), многие старые CSS-фреймворки (Bootstrap, Bulma, Materialize, Semantic UI)

---

### 2024–2026 — эволюция через контент (внешнее управление)

После перерисовки 2024-06-23 визуальный JSON (`frontend.json`) **не менялся структурно** — те же 137 нод, те же ID. Эволюция роадмапа продолжилась через **слой контента**, управляемый внешней системой roadmap.sh.

#### Архитектура управления контентом

Контент отделён от структуры и хранится в `src/data/roadmaps/frontend/content/<slug>@<nodeId>.md` (120 файлов). Каждый файл — Markdown с описанием темы и ссылками на ресурсы. Связь с визуальной нодой осуществляется по `nodeId` в имени файла.

Два GitHub Actions workflow обеспечивают **двустороннюю синхронизацию** между репо и внешней базой данных:

- **`sync-content-to-repo.yml`** — тянет контент **из БД → в репо**, создаёт PR `chore: sync content to repo`. Запускается вручную (`workflow_dispatch`) с указанием slug роадмапа.
- **`sync-repo-to-database.yml`** — пушит **из репо → в БД**. Все файлы роадмапа сканируются и отправляются через `npm run sync:repo-to-database`.
- **`cleanup-orphaned-content.yml`** — удаляет content-файлы, nodeId которых отсутствует в текущем JSON (осиротевшие файлы).

Команды синхронизации:
- `npm run sync:content-to-repo -- --roadmap-slug=<slug> --secret=<GH_SYNC_SECRET>`
- `npm run sync:repo-to-database -- --files=<file-list> --secret=<GH_SYNC_SECRET>`

#### Промежуточные обновления существующего контента

- **2024-12-02** — рефакторинг всего роадмапа (`add174a69`)
- **2025-01-21** — добавлены ресурсы для контента тем (`edc7de822`)
- **2025-04-04** — миграция инфраструктуры контента (`deb9aaafc`) — переформатирование всех JSON, без изменения тем
- **2025-05-01–03** — внедрён AI Tutor в темы, Topic Chat, Refactor topic popup
- **2025-05-26** — **полная перезапись текстов** всех content-файлов: сокращение и упрощение описаний (например, текст про Accessibility сокращён с многоэтажного параграфа до двух предложений)
- **2025-09-08** — массовое обновление контента "Frontend roadmaps changes" (`c6feb67d6`) — правки во всех content-файлах
- **2025-05-28** — roadmap chat (`62f31a496`)

#### Волны нового контента (42 «осиротевших» файла — без соответствующих нод в текущем JSON)

Это означает, что **новая версия визуального роадмапа готовится во внешней системе**, но обновлённый JSON с новыми нодами ещё не выгружен в репо. Контент для будущих тем уже синхронизирован.

| Дата добавления | Новые темы (slug) | Направление |
|---|---|---|
| **2025-11** | github-pages | Хостинг |
| **2025-12-22** | Vercel, Netlify, Cloudflare, Railway, Render | **Deployment-платформы** |
| **2025-12-22** | Biome, Bun, Rolldown, TanStack Start | **Новые инструменты сборки** |
| **2025-12-22** | Lighthouse, Cache-Control, Service Workers, Web APIs, DevTools Usage, Performance | **Производительность и DevTools** |
| **2025-12-22** | Design Systems, Type Checkers | Дизайн-системы, типизация |
| **2026-02-05** | AI Agents, AI-Assisted Coding, How LLMs Work, Implementing AI | **AI-фундамент** |
| **2026-02-05** | Anthropic, OpenAI, Gemini | **LLM-провайдеры** |
| **2026-02-05** | Claude Code, Copilot, Cursor, Antigravity | **AI-ассистенты и IDE** |
| **2026-02-05** | MCP (Model Context Protocol), Prompting Techniques, Skills | **AI-инструментарий** |
| **2026-02-05** | Code Reviews, Refactoring, Applications, Learn the Basics, Docs Generation | **AI-влияние на практики разработки** |
| **2026-03-11** | AI vs Traditional Coding, Docs Generation | AI-методология |
| **2026-04-27** | Ionic | Mobile-платформы |

#### Новые направления роадмапа (на основе контентных волн)

**AI-раздел (февраль 2026) — крупнейшее расширение с 2019 года:**
- **AI-фундамент:** AI Agents, AI-Assisted Coding, How LLMs Work, Implementing AI, AI vs Traditional Coding
- **LLM-провайдеры:** Anthropic, OpenAI, Gemini
- **AI-ассистенты и IDE:** Claude Code, GitHub Copilot, Cursor, Antigravity
- **AI-инструментарий:** Model Context Protocol (MCP), Prompting Techniques, Skills, Docs Generation
- **AI-влияние на практики:** Code Reviews (с AI), Refactoring (с AI), Applications, Learn the Basics

**Deployment и хостинг (декабрь 2025):**
- Vercel, Netlify, Cloudflare, Railway, Render, GitHub Pages

**Новые инструменты сборки (декабрь 2025):**
- Biome (замена ESLint+Prettier), Bun (runtime/package manager), Rolldown (новый bundler), TanStack Start (SSR-фреймворк)

**Производительность и DevTools (декабрь 2025):**
- Lighthouse, Cache-Control, Service Workers, Web APIs, DevTools Usage, Performance

**Дизайн-системы (декабрь 2025):**
- Design Systems

#### Очистка и миграция (2026-05-14)

Коммит `3db5d4a5e` "chore: cleanup orphaned content files" удалил 23 content-файла, чьи nodeId соответствовали **старому** JSON. При этом сохранены файлы с **новыми** nodeId (42 файла), что подтверждает подготовку к выпуску новой версии визуального роадмапа.

Удалены старые файлы: accessibility@iJIqi7ngpGHWAqtgdjgxB.md, bem@dRDmS072xeNLX7p_X565w.md, bitbucket@DILBiQp7WWgSZ5hhtDW6A.md, build-tools@i9z0stM4uKu27Cz6NIgNX.md, sass@kukEE5rMSPa4NeNjx21kt.md, webpack@twufEtHgxcRUWAUQ9bXus.md и др.

#### Статус на июль 2026

- Визуальный JSON: 137 нод, 118 уникальных тем — **идентичен версии 2024-06-23**
- Слой контента: 120 файлов, из которых **42 файла** готовят новые темы для следующей версии роадмапа
- Текущий `frontend.md` помечен как "Step by step guide to becoming a frontend developer in 2025"

---

## Ключевые тренды эволюции

1. **Уход от jQuery и старых фреймворков** (2017→2018): jQuery стал опциональным, AngularJS заменён на Angular 2+, убраны Ember/Preact/Inferno.
2. **Модульность и сборка** (2018→2019): Parcel и Rollup вытеснили Browserify/RequireJS/AMD; npm scripts заменили Grunt.
3. **PWA и производительность** (2019): появились целые разделы — PWA, Performance Metrics (RAIL, PRPL, Lighthouse), Web Assembly.
4. **Мультиплатформенность** (2019): добавлены Desktop (Electron) и Mobile (React Native) приложения.
5. **CSS-in-JS и TypeScript** (2019→2023): рост CSS-in-JS (Styled Components), TypeScript стал основным (Flow убран).
6. **Современные инструменты** (2023): Vite, esbuild, SWC, pnpm, Tailwind, Playwright/Vitest — замена классического стека.
7. **Безопасность и GraphQL** (2023): появились целые разделы Web Security и GraphQL.
8. **Web Components** (2023): Custom Elements, Shadow DOM.
9. **Упрощение и консолидация** (2024): убраны избыточные детали CSS, старые фреймворки; фокус на современном стеке.
10. **AI-революция** (2025→2026): подготовка крупнейшего расширения — AI-ассистенты (Claude Code, Copilot, Cursor), LLM-провайдеры (Anthropic, OpenAI, Gemini), MCP, Prompting Techniques, AI Agents. AI становится отдельным направлением в роадмапе фронтенд-разработчика.
11. **Deployment как самостоятельный раздел** (2025): Vercel, Netlify, Cloudflare — платформы деплоя выделяются в отдельную тему.
12. **Разделение структуры и контента** (2024→2026): визуальный JSON застыл, эволюция продолжается через внешний контент-слой с двусторонней синхронизацией БД ↔ репо.

---

## Источники данных по годам

| Год | Коммит       | Файл                                    | Формат                |
|-----|--------------|-----------------------------------------|-----------------------|
| 2017| 665dcdf24    | project-files/frontend-map.json         | Balsamiq JSON         |
| 2018| 306915a40    | project-files/frontend-map.json         | Balsamiq JSON         |
| 2019| b208eaa1b    | project/frontend-map.json               | Balsamiq JSON         |
| 2023| bb7f1f4d6    | src/data/roadmaps/frontend/frontend.json| Balsamiq JSON (копия) |
| 2024| f5fc71aad    | src/data/roadmaps/frontend/frontend.json| React Flow JSON       |
| 2025| 152e2a35c    | src/data/roadmaps/frontend/content/*.md | Перезапись контента   |
| 2025| deb9aaafc    | src/data/roadmaps/frontend/frontend.json| React Flow JSON (миграция формата) |
| 2026| 74e2a7105    | src/data/roadmaps/frontend/content/*.md | Sync content (AI-темы)|
| 2026| 3db5d4a5e    | src/data/roadmaps/frontend/content/*.md | Cleanup orphaned      |
| 2026| 949395506    | src/data/roadmaps/frontend/frontend.json| React Flow JSON       |

### Источники контента (2024–2026)

| Источник | Механизм | Направление |
|---|---|---|
| Внешняя БД roadmap.sh | `sync-content-to-repo.yml` (GitHub Actions) | БД → репо |
| Репозиторий | `sync-repo-to-database.yml` (GitHub Actions) | Репо → БД |
| GitHub Actions bot | `cleanup-orphaned-content.yml` | Удаление осиротевших файлов |

### Структура контента

```
src/data/roadmaps/frontend/
├── frontend.json              # визуальная структура (React Flow, 137 нод)
├── frontend.md                # метаданные и SEO
├── frontend-beginner.json      # beginner-версия
├── migration-mapping.json     # маппинг slug → nodeId
├── faqs.astro                  # FAQ-страница
└── content/                    # 120 markdown-файлов
    ├── accessibility@e-k6EhoxYG9h0x6vWOrDh.md
    ├── ai-assisted-coding@ipcNHz8KbfpE57kNP15hP.md
    └── ... (42 "осиротевших" файла готовят новые темы)
```
