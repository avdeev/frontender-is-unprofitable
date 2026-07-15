# Эволюция профессии фронтенд-разработчика (2008–2026)

> **Связанные документы:** [frontend-evolution-index.md](frontend-evolution-index.md) — навигация и ретроспективный анализ «что не попало в роадмап» | [frontend-roadmap-evolution.md](frontend-roadmap-evolution.md) — год-за-годом структура роадмапа (2017–2026)

> Анализ построен на данных [developer-roadmap](https://github.com/kamranahmedse/developer-roadmap) (коммиты 2017–2026), опросах State of JS (2016–2024) и Stack Overflow Developer Survey (2019–2024), а также на таймлайне ключевых релизов. Количественные данные — из опросов; структурные изменения — из роадмапа.

---

## Содержание

1. [Введение: как появилась профессия](#1-введение-как-появилась-профессия)
2. [Шесть эпох фронтенд-профессии](#2-шесть-эпох-фронтенд-профессии)
   - [Эпоха 1. Вебмастер / jQuery (~2008–2013)](#эпоха-1-вебмастер--jquery-20082013)
   - [Эпоха 2. Войны фреймворков и рождение SPA (2013–2016)](#эпоха-2-войны-фреймворков-и-рождение-spa-20132016)
   - [Эпоха 3. JavaScript Fatigue / взрыв тулинга (2016–2019)](#эпоха-3-javascript-fatigue--взрыв-тулинга-20162019)
   - [Эпоха 4. Зрелость и TypeScript-доминирование (2020–2022)](#эпоха-4-зрелость-и-typescript-доминирование-20202022)
   - [Эпоха 5. Консолидация и смена стека (2023–2024)](#эпоха-5-консолидация-и-смена-стека-20232024)
   - [Эпоха 6. AI-революция (2025–2026)](#эпоха-6-ai-революция-20252026)
3. [Год-за-годом: навыки в фокусе](#3-год-за-годом-навыки-в-фокусе)
4. [Три перелома профессии](#4-три-перелома-профессии)
5. [Количественные данные опросов](#5-количественные-данные-опросов)
6. [Паттерны эволюции](#6-паттерны-эволюции)
7. [Источники](#7-источники)

---

## 1. Введение: как появилась профессия

До ~2008 года «делать веб» не было отдельной инженерной профессией. Был **вебмастер** — человек, который одновременно проектировал, верстал (HTML/CSS), программировал (JavaScript, PHP, Perl), настраивал сервер и отвечал за SEO. JavaScript воспринимался как инструмент для «оживления» страниц: валидация форм, выпадающие меню, простые анимации. jQuery (2006) стандартизировал DOM-манипуляцию и AJAX, но не изменил суть — фронтенд оставался дополнением к серверной разработке.

**Выделение «фронтенд-разработчика» как отдельной роли** произошло в 2008–2013 годах под влиянием трёх факторов:

1. **Рост сложности клиента.** AJAX-приложения (Gmail, Google Maps, Twitter) показали, что UI может быть таким же сложным, как сервер. Появились первые SPA-фреймворки (AngularJS 2010, Backbone 2010, Ember 2011).
2. **Node.js и npm (2009).** JavaScript вышел на сервер, что породило экосистему переиспользуемых модулей и инструмент сборки. Фронтенд-разработчик получил собственный toolchain.
3. **React (2013).** Компонентная модель и виртуальный DOM окончательно отделили «frontend engineering» от «HTML-вёрстки». После React «фронтенд-разработчик» стал означать инженера, а не верстальщика.

Stack Overflow Developer Survey подтверждает: к 2019 году **32.8%** респондентов идентифицировали себя как front-end developers (multi-select), а full-stack — 51.9%. К 2022 году front-end снизился до 25.96% — не потому, что роль исчезла, а потому что **граница между front-end и full-stack размылась**: фронтенд-разработчик теперь обязан знать и серверную часть (SSR, API routes, Next.js).

---

## 2. Шесть эпох фронтенд-профессии

### Эпоха 1. Вебмастер / jQuery (~2008–2013)

#### Контекст

Веб-разработка — одна дисциплина. «Фронтенд» означает HTML/CSS + jQuery. Серверная часть доминирует (PHP, Ruby on Rails, Django). JavaScript — вспомогательный язык, часто презираемый «настоящими» программистами. Браузеры фрагментированы (IE6/7/8, Firefox, начало Chrome); кросс-браузерная совместимость — ключевая боль.

#### Ключевые технологии

- **jQuery (2006)** — де-факто стандарт; к 2013 используется на >50% топ-сайтов. Решает: DOM-манипуляция, AJAX, кросс-браузерность, анимации.
- **AngularJS (2010)** — первый крупный SPA-фреймворк (Google). MVW-архитектура, two-way binding, dependency injection.
- **Backbone.js (2010)** — MVP-фреймворк, популярен с Underscore.js и RequireJS.
- **Bootstrap (2011)** — CSS-фреймворк от Twitter, стандартизирует адаптивную вёрстку.
- **Node.js (2009)** + **npm (2010)** — серверный JS и пакетный менеджер, основа будущей экосистемы.
- **Less (2009), Sass (2010)** — CSS-препроцессоры (переменные, nesting, mixins).
- **Grunt (2012)** — первый популярный task runner для сборки фронтенда.

#### Навыки в фокусе (год-за-годом)

| Год | Ключевые навыки | Что определяло «хорошего» разработчика |
|---|---|---|
| 2008 | HTML4/XHTML, CSS2.1, JavaScript (ES3), Photoshop → HTML | Кросс-браузерная вёрстка (IE6 hacks), tableless layout |
| 2009 | jQuery 1.3+, AJAX, JSON, Sass | DOM-манипуляция без jQuery (знание raw API ценилось) |
| 2010 | AngularJS, Backbone, HTML5, CSS3 (media queries) | Понимание SPA-архитектуры, MVC/MVP |
| 2011 | Bootstrap, Node.js, npm, CoffeeScript | Адаптивная вёрстка, первые build-инструменты |
| 2012 | Grunt, Bower, LESS, RequireJS/AMD | Автоматизация сборки, модульность |
| 2013 | React (OSS), jQuery 2.0, Bower → npm | Компонентное мышление, знание React — нишевый навык |

#### Переломные события

- **2009, JSConf EU** — Ryan Dahl представляет Node.js. JavaScript выходит за пределы браузера.
- **2010** — AngularJS выпущен Google. Первый SPA-фреймворк от крупной корпорации.
- **2013, 29 мая** — **React open-sourced на JSConf US** (Jordan Walke, Facebook). Компонентная модель + виртуальный DOM. Это поворотный момент, после которого «фронтенд-разработка» начинает превращаться в инженерную дисциплину.

#### Цитата из эпохи

> *"JavaScript: The World's Most Misunderstood Programming Language"* — Douglas Crockford (2001), всё ещё актуально. JavaScript долго считался «игрушечным» языком; статус «настоящего» языка он получает только с приходом Node.js и React.

---

### Эпоха 2. Войны фреймворков и рождение SPA (2013–2016)

#### Контекст

React (2013), Vue (2014) и Angular 2 (2016) формируют три конкурирующие философии. Фронтенд-разработчик становится самостоятельной ролью. Появляются первые специализации: «React-разработчик», «Angular-разработчик». npm-экосистема взрывается. Начинается переход от «вёрстки» к «инженерии».

#### Ключевые технологии

- **React (2013)** — компонентная модель, виртуальный DOM, JSX, однонаправленный поток данных. К 2016 — доминирующий фреймворк.
- **Vue.js (2014, Evan You)** — «прогрессивный фреймворк»: берёт лучшее из React (компоненты, виртуальный DOM) и Angular (templates). Vue 2.0 (2016) добавляет SSR.
- **Angular 2 (2016, сентябрь)** — полная переработка AngularJS на TypeScript. **Несовместима** с AngularJS; миграция стоит дорого. Это событие раскалывает Angular-сообщество и толкает многих к React/Vue.
- **TypeScript (2012, Microsoft)** — начинает набирать ранних сторонников; Angular 2 делает TypeScript нормой в Angular-экосистеме.
- **Webpack (2012, Tobias Koppers)** — вытесняет Grunt/Gulp как bundler. К 2016 — де-факто стандарт.
- **Babel (2014, Sebastian McKenzie)** — транспайлер ES6+ → ES5, позволяет писать современный JS до поддержки браузерами.
- **Redux (2015, Dan Abramov)** — state management для React; становится стандартом к 2016.
- **React Native (2015)** — фронтенд-разработчик может теперь делать и мобильные приложения.
- **CSS Modules (2015)** и **Styled Components (2016)** — изоляция стилей на уровне компонентов.

#### Навыки в фокусе (год-за-годом)

| Год | Ключевые навыки | Что определяло «хорошего» разработчика |
|---|---|---|
| 2013 | React 0.3, JSX, Babel, Webpack, ES6 (стрелки, классы) | Понимание виртуального DOM, однонаправленный поток данных |
| 2014 | Vue.js 0.x, Redux, Flux, React Router, npm → Bower умирает | State management (Redux/Flux), архитектура SPA |
| 2015 | React Native, Webpack 2, ES6 (полная поддержка Babel), Immutable.js | Изоморфные/универсальные приложения (SSR), мобильная разработка |
| 2016 | Angular 2 (TypeScript), Vue 2.0, CSS Modules, Styled Components | Выбор фреймворка = идеологический; TypeScript в Angular-экосистеме |

#### Переломные события

- **2013, 29 мая** — React open-sourced. Начало компонентной эры.
- **2014, февраль** — Vue.js анонсирован. Третий путь между React и Angular.
- **2015, март** — React Native open-sourced. Фронтенд-разработчик = мультиплатформенный разработчик.
- **2016, сентябрь** — **Angular 2 выпущен, несовместим с AngularJS.** Это самый разрушительный миграционный момент в истории фронтенда: годы AngularJS-кода требовали переписывания. Многие команды мигрируют на React/Vue.

#### Данные опросов

Stack Overflow 2019 (ретроспектива): *"больше разработчиков используют React.js, чем Angular — переключение по сравнению с прошлым годом."* Это первая точка, где React обгоняет Angular.

---

### Эпоха 3. JavaScript Fatigue / взрыв тулинга (2016–2019)

#### Контекст

Самый бурный период в истории фронтенда. Каждую неделю — новый bundler, новый state-менеджер, новый CSS-фреймворк. Появляется термин **«JavaScript fatigue»** (усталость от JavaScript) — разработчики жалуются на невозможность угнаться за инструментами. Роадмап developer-roadmap именно в этот период (2017–2019) фиксирует наибольшие структурные изменения: +разделы PWA, Performance, Desktop, Mobile, Web Assembly.

#### Ключевые технологии

- **Webpack 2→4 (2017–2018)** — становится невероятно мощным, но и невероятно сложным в конфигурации. Создаёт рынок для альтернатив (Parcel, Rollup).
- **Parcel (2017)** — bundler с нулевой конфигурацией, попытка убить «Webpack config hell».
- **Rollup (2015, Rich Harris)** — ES-модули, tree-shaking; стандарт для библиотек.
- **TypeScript** — выходит за пределы Angular; к 2019 используется с React/Vue. Stack Overflow 2019: **21.2%** разработчиков используют TS.
- **Next.js (2016, Zeit/Vercel)** — SSR-фреймворк для React. Делает универсальные приложения доступными.
- **Gatsby (2015)** — статический генератор сайтов на React; Jamstack-движение.
- **PWA (2015, Google)** — Service Workers, manifest, offline-first. К 2018 — отдельный раздел в роадмапе.
- **CSS-in-JS** — Styled Components (2016), Emotion (2017). Изоляция стилей через JavaScript.
- **GraphQL (2015, Facebook)** + **Apollo (2016)** — альтернатива REST для клиент-серверного взаимодействия.
- **React Fiber (2017)** — переписанный reconciler, основа для concurrent features.
- **React Hooks (2018, октябрь; релиз 2019, февраль)** — функция-компоненты становятся стандартом; классы уходят.

#### Навыки в фокусе (год-за-годом)

| Год | Ключевые навыки | Что определяло «хорошего» разработчика | Роадмап: что добавилось |
|---|---|---|---|
| 2016 | Webpack 2, Redux, Next.js, Styled Components, Babel | Настройка Webpack-конфига (ценилось высоко), SSR | — |
| 2017 | React Fiber, Parcel, PWA, Service Workers, GraphQL | Progressive Web Apps, Apollo/GraphQL, мониторинг производительности | Роадмап 2017: 119 тем, первый полноценный Balsamiq-роадмап |
| 2018 | React 16.3 (Context API), Babel 7, Rollup, PWA mainstream | Разделение Presentational/Container → Hooks, Webpack 4 | Роадмап 2018: jQuery → опциональный, +pnpm, +React Router |
| 2019 | **React Hooks (16.8)**, TypeScript mainstream, Next.js 9, Apollo, Web Assembly | Функциональные компоненты + Hooks (классы — «старый стиль»), SSR, PWA, Performance Metrics (RAIL, Lighthouse) | Роадмап 2019: +PWA, +Performance, +Desktop (Electron), +Mobile (React Native), +Web Assembly; Grunt→npm scripts, Browserify→Parcel/Rollup |

#### Переломные события

- **2016–2017** — **«JavaScript Fatigue»** становится культурным феноменом. Эссе Jose Aguinaga *"How it feels to learn JavaScript in 2016"* (35k upvotes на Medium) — символ эпохи. State of JS 2023 ещё ссылается на *"the dreaded JavaScript fatigue"*.
- **2017, апрель** — React Fiber (React 16). Самая глубокая переработка reconciler'а в истории React.
- **2018, октябрь** — **React Hooks announced на React Conf.** Классовые компоненты объявлены устаревшими. Это меняет паттерны написания кода на годы вперёд.
- **2019, февраль** — React 16.8 (Hooks stable). Function components становятся стандартом.

#### Данные опросов

- **Stack Overflow 2019:** jQuery — **48.7%** (#1 веб-фреймворк), React — 31.3%, Angular — 30.7%. TypeScript — 21.2%. Front-end как роль — 32.8%.
- **State of JS 2016–2019 (ретроспектива):** React, Vue, Angular — тройка лидеров; Svelte — новичок с высоким интересом.

#### Роадмап: что показывает

Роадмап 2017→2019 — самый большой структурный скачок за всю историю:
- **+4 новых раздела:** PWA, Performance Metrics, Desktop Apps (Electron), Mobile Apps (React Native)
- **Умерли:** Grunt (→npm scripts), Browserify/RequireJS/AMD (→Parcel/Rollup), Gulp
- **jQuery** — ещё есть, но помечен как опциональный
- Мультиплатформенность: фронтенд-разработчик теперь делает и десктоп, и мобильные приложения

---

### Эпоха 4. Зрелость и TypeScript-доминирование (2020–2022)

#### Контекст

Буря утихает. Инструменты стабилизируются. React безоговорочно доминирует. TypeScript становится нормой, а не опцией. Next.js превращается из «нишевого SSR-фреймворка» в стандарт. Появляются React Server Components — самое большое изменение в React-модели с 2013 года.

#### Ключевые технологии

- **TypeScript** — стремительный рост. Stack Overflow: 21.2% (2019) → 30.19% (2021) → **34.83% (2022)**. Среди профессионалов — 40%. TypeScript перестаёт быть «опцией для энтерпрайза» и становится де-фолтным выбором.
- **React 17 (октябрь 2020)** — «No New Features», но фундамент для gradual upgrades.
- **React Server Components (декабрь 2020)** — RFC от Facebook. Серверные компоненты без hydration overhead. Концептуальный сдвиг: граница между клиентом и сервером размывается окончательно.
- **Next.js 11→12→13 (2021–2022)** — Next.js 13 (октябрь 2022) представляет **App Router** с RSC, самый крупный shift в Next.js.
- **Vue 3.0 (сентябрь 2020)** — Composition API, Proxy-based reactivity. Но миграция с Vue 2 идёт медленно.
- **Vite (2020, Evan You)** — новый bundler на esbuild. К 2022 — растущая альтернатива Webpack.
- **Playwright (2020, Microsoft)** — end-to-end тестирование, вытесняет Cypress в новых проектах.
- **Vitest (2021, Anthony Fu)** — Vite-native тест-раннер, альтернатива Jest.
- **Tailwind CSS (2020+)** — utility-first подход набирает массовое принятие.
- **Jamstack / Headless CMS** — Contentful, Sanity, Strapi. Разделение контента и презентации.
- **Copilot (июнь 2021)** — GitHub Copilot в technical preview. Первый массовый AI-ассистент для кода, но пока нишевый.

#### Навыки в фокусе (год-за-годом)

| Год | Ключевые навыки | Что определяло «хорошего» разработчика | Данные опросов |
|---|---|---|---|
| 2020 | React 17, Vue 3, Vite 2.0, Playwright, PWA mainstream, Jamstack | SSR/SSG, headless CMS, E2E-тестирование, знание Vite — нишевое | SO: TS 30.19% (#7) |
| 2021 | **React обгоняет jQuery**, Next.js 11, Copilot preview, Tailwind рост | Svelte «most loved» (SO 2021); React — «most wanted» 5-й год | **SO 2021: React 40.14% > jQuery 34.42%** — символический конец jQuery-эры |
| 2022 | **React 18 (concurrent, Suspense SSR)**, Next.js 13 App Router (beta), RSC, Vite mainstream, Vitest | React Server Components — концептуальный сдвиг; concurrent rendering | SO 2022: TS 34.83% (#5); React 42.62%; jQuery 28.57% |

#### Переломные события

- **2020, 18 сентября** — Vue 3.0 выпущен. Composition API — самый большой шаг Vue с 2.0, но сообщество медлит с миграцией.
- **2020, октябрь** — React 17. «No New Features», но закладывает фундамент для RSC и gradual upgrades.
- **2020, декабрь** — **React Server Components** представлены. RFC и демо. Концепция: компоненты, которые рендерятся на сервере, но интегрированы с клиентом без hydration overhead. Это определяет архитектуру React на 2023–2026.
- **2021** — **React surpasses jQuery в Stack Overflow Survey.** Символический момент: «React-эра» официально становится доминирующей. Copilot preview.
- **2022, 29 марта** — **React 18** (concurrent renderer, automatic batching, Suspense SSR). Самый крупный релиз React с 2017.
- **2022, 21 октября** — Next.js 13 + App Router (beta). RSC в продакшене. Переписывает ментальную модель Next.js.
- **2022, 30 ноября** — **ChatGPT** запущен. Это событие определит следующую эпоху, но в 2022 оно ещё не влияет на роадмапы.

#### Роадмап: что показывает

Роадмап в этот период (2020–2022) **не обновлялся структурно** — фронтенд-карта оставалась в Balsamiq-формате 2019 года. Но контент-файлы обновлялись. Роадмап «отстаёт» от реального состояния индустрии на 1–2 года — это нормально, т.к. отражает устойчивый консенсус, а не хайп.

---

### Эпоха 5. Консолидация и смена стека (2023–2024)

#### Контекст

Новая волна инструментов зрелости: Vite вытесняет Webpack, Tailwind доминирует, Svelte/Solid/Qwik предлагают альтернативы React. Роадмап 2023–2024 фиксирует «чистку» — удаляются старые технологии, фокус на современном стеке. Парадокс State of JS 2024: *"top three frontend frameworks all launched over a decade ago"* (React 2013, Vue 2014, Angular 2010/2016) — при всей смене инструментов, базовый стек стабилизировался.

#### Ключевые технологии

- **Vite** — к 2024 сравнялся с Webpack в использовании на работе (69.3% vs 69.5%, State of JS 2024). Победа над Webpack-конфиг-хеллом.
- **esbuild, SWC** — Rust/Go-написанные транспайлеры, на порядки быстрее Babel. Основа Vite, Next.js, Turbopack.
- **Tailwind CSS** — 74.8% в State of CSS 2024. Bootstrap (53.6%) всё ещё используется, но в legacy-проектах.
- **Svelte 4/5 (2023–2024)** — Svelte: Runes (2024) — реактивность без компилятора. State of JS 2023: Svelte #1 по удовлетворённости. Stack Overflow 2024: 73% использовавших хотят продолжать.
- **SolidJS (2021, Ryan Carniato)** — fine-grained reactivity, ближайший «наследник React» по модели. State of JS 2024: 2.7% — нишевый, но высокий интерес.
- **Qwik (2022, Miško Hevery — создатель AngularJS)** — resumability вместо hydration. Радикальная переосмысление SSR.
- **Astro (2022)** — islands architecture. State of JS 2024: 12.7% — быстрый рост.
- **Next.js 13.4 (май 2023)** — App Router stable. RSC в продакшене.
- **React 19 (декабрь 2024)** — Actions, официальный Server Components, улучшенный SSG.
- **Vitest** — State of JS 2024: 34.2%, #1 по interest/retention/positivity. Vitest обходит Jest по настроению разработчиков.
- **Playwright** — State of JS 2024: 31.5%, обход Cypress (30.9%).

#### Навыки в фокусе (год-за-годом)

| Год | Ключевые навыки | Что определяло «хорошего» разработчика | Данные опросов |
|---|---|---|---|
| 2023 | Next.js 13 App Router (stable), RSC, Svelte 4, Astro, SolidJS, Qwik | React Server Components — мейнстрим; понимание когда НЕ React (Svelte/Solid/Qwik); edge runtime | SO 2023: TS 38.87%; AI section debuts, 70% используют/планируют AI |
| 2024 | **React 19**, Vite ≈ Webpack, Tailwind 4, Vitest, Biome, TanStack Start | Vite как де-фолт; TypeScript как норма; RSC-архитектура; AI-ассистенты (Copilot/Cursor) в повседневной работе | State of JS 2024: Vite 69.3% ≈ Webpack 69.5%; Tailwind 74.8%; Svelte 73% retention; SO 2024: 62% используют AI |

#### Переломные события

- **2023, март** — Claude (Anthropic) выпущен. Конкуренция ChatGPT.
- **2023, Cursor** — AI IDE выпущен. Становится вирусным среди разработчиков в 2024.
- **2023, 25 ноября** — **MCP (Model Context Protocol)** анонсирован Anthropic. Стандартизация AI-агентов ↔ инструментов. В 2025–2026 MCP входит в роадмап.
- **2024, 5 декабря** — **React 19** выпущен. Actions, Server Components официально, улучшенный SSG.

#### Роадмап: что показывает

Роадмап 2024 (перерисовка 2024-06-23 в React Flow):
- **Убраны:** Hugo, Jekyll, NativeScript, Remix, Radix UI, Shadcn UI, Task Runners, Universal, Flow, CSS-in-JS (свернут в примечание), Bootstrap/Bulma/Materialize/Semantic UI
- **Добавлено:** react-router, Fullstack, Browser APIs (отдельно), Measure & Improve Perf
- Фокус: современный стек, без исторического багажа

Парадокс State of JS 2024: при всей смене инструментов, **топ-3 фреймворка (React 2013, Vue 2014, Angular 2010) старше десятилетия**. Профессия «консолидировалась» на уровне фундамента, но инструменты вокруг продолжают меняться.

---

### Эпоха 6. AI-революция (2025–2026)

#### Контекст

AI-ассистенты переходят из «нишевого инструмента» в **базовый навык**. Stack Overflow 2024: **62%** разработчиков используют AI (рост с 44% в 2023). Роадмап developer-roadmap готовит крупнейшее расширение с 2019 года: 42 новых content-файла, из которых 17 — AI-темы. AI-раздел становится самостоятельным направлением в роадмапе фронтенд-разработчика — впервые новый «крупный раздел» с 2019 года (PWA/Performance/Desktop/Mobile).

#### Ключевые технологии

- **GitHub Copilot** — к 2024 ubiquitous в корпоративной разработке.
- **Claude Code (2024, Anthropic)** — CLI AI-ассистент, агентственный режим.
- **Cursor (2023, Anysphere)** — AI-native IDE на базе VS Code. К 2025 — самый быстрорастущий AI-инструмент среди разработчиков.
- **Antigravity (2025, Google)** — AI IDE от Google, конкурент Cursor.
- **Model Context Protocol (MCP, ноябрь 2024, Anthropic)** — стандарт для интеграции AI-агентов с внешними инструментами. Аналог того, чем React Router был для routing — стандартизация нового слоя абстракции.
- **LLM-провайдеры** — Anthropic (Claude), OpenAI (GPT-4/5), Google (Gemini). Фронтенд-разработчик теперь должен понимать различия между моделями, их стоимости и ограничения.
- **AI-влияние на практики:**
  - **Code Reviews** — AI-генерация и анализ PR.
  - **Refactoring** — AI-предложения по рефакторингу.
  - **Docs Generation** — автоматическая генерация документации.
  - **Prompting Techniques** — новый навык: как формулировать запросы к LLM.
- **Bun (2024+)** — JavaScript runtime + package manager + bundler, альтернатива Node.js.
- **Rolldown (2024+)** — Rust-based bundler от Vite-команды, замена Rollup.
- **Biome (2024+)** — Rust-based линтер+форматер, замена ESLint+Prettier.
- **TanStack Start (2024+)** — новый SSR-фреймворк от TanStack.

#### Навыки в фокусе (год-за-годом)

| Год | Ключевые навыки | Что определяло «хорошего» разработчика | Роадмап |
|---|---|---|---|
| 2025 | Cursor/Claude Code в повседневной работе, MCP, prompting, AI-assisted refactoring | AI как усилитель продуктивности; понимание, когда доверять AI, а когда нет; prompting techniques | Роадмап: 42 новых content-файла готовят AI-раздел, deployment, новые build tools |
| 2026 | AI Agents, AI vs Traditional Coding, Docs Generation, Skills (MCP), Code Reviews с AI | AI-агенты как часть workflow; разделение «AI-first» и «traditional» подходов; MCP-интеграция | Визуальный JSON ещё не обновлён (137 нод с 2024-06-23), но контент-слой готовит новую версию |

#### Переломные события

- **2022, 30 ноября** — ChatGPT. Точка отсчёта AI-эры для разработки.
- **2023, март** — Claude. Cursor. AI-инструменты становятся специфичными для кода.
- **2024, 25 ноября** — **MCP анонсирован.** Стандартизация AI-агентов. В роадмап 2026 — как отдельная тема.
- **2025** — Cursor и Claude Code ubiquitous. AI-ассистент становится базовым навыком, как Git.
- **2025, октябрь / 2026, 24 февраля** — React передан в React Foundation под Linux Foundation. Meta освобождает React от корпоративного контроля — признак зрелости экосистемы.

#### Роадмап: что показывает

Роадмап 2025–2026 готовит **крупнейшее расширение с 2019 года**:
- **AI-раздел** (17 тем): AI Agents, AI-Assisted Coding, How LLMs Work, Implementing AI, AI vs Traditional Coding, Anthropic, OpenAI, Gemini, Claude Code, Copilot, Cursor, Antigravity, MCP, Prompting Techniques, Skills, Code Reviews, Refactoring, Docs Generation
- **Deployment-раздел** (6 тем): Vercel, Netlify, Cloudflare, Railway, Render, GitHub Pages
- **Новые build tools** (4 темы): Biome, Bun, Rolldown, TanStack Start
- **Performance/DevTools** (6 тем): Lighthouse, Cache-Control, Service Workers, Web APIs, DevTools Usage, Performance

#### Что это значит для профессии

AI меняет не только инструменты, но и **определение фронтенд-разработчика**:
- Раньше: «человек, который пишет код на React/Vue/Angular»
- Сейчас: «человек, который проектирует UI-системмы, промптит AI для генерации кода, ревьюит AI-вывод, интегрирует LLM-возможности в продукты»

Навык «писать код вручную» не исчезает, но становится одним из нескольких способов достижения результата, а не единственным. Появляется новый навык: **когда доверять AI, а когда — нет.**

---

## 3. Год-за-годом: навыки в фокусе

Сводная таблица навыков, которые были критически важны для фронтенд-разработчика по годам. «⚡» — пик важности навыка в этот год.

| Год | Фреймворк | Bundler | Язык | CSS | State | Тесты | AI | Hosting |
|---|---|---|---|---|---|---|---|---|
| 2008 | jQuery ⚡ | — | ES3 | CSS2.1 | — | — | — | shared |
| 2009 | jQuery ⚡ | — | ES3 | Sass ⚡ | — | — | — | shared |
| 2010 | AngularJS ⚡, Backbone | — | ES5 | Sass, Less | — | — | — | shared |
| 2011 | jQuery, Bootstrap | Grunt ⚡ | CoffeeScript | Bootstrap ⚡ | — | — | — | shared |
| 2012 | jQuery, Backbone | Grunt, Bower | ES6 (draft) | Less, Sass | — | — | — | shared |
| 2013 | **React ⚡**, AngularJS | Webpack ⚡ | ES6, Babel ⚡ | Sass | — | — | — | shared |
| 2014 | React, Vue ⚡, AngularJS | Webpack, Babel | ES6, TypeScript ⚡ | Sass, CSS Modules | Flux ⚡ | — | — | Heroku |
| 2015 | React, Angular, Vue | Webpack 2, Babel | ES6, TS | CSS Modules ⚡ | Redux ⚡ | — | — | Heroku, AWS |
| 2016 | React ⚡, Angular 2 ⚡, Vue 2 | Webpack 2 | ES6, TS | CSS Modules, Styled Components ⚡ | Redux | — | — | AWS, Heroku |
| 2017 | React, Vue, Angular | Webpack 3, Parcel ⚡ | TS, ES6 | Styled Components | Redux, MobX | Jest ⚡ | — | AWS |
| 2018 | React, Vue, Angular | Webpack 4, Parcel | TS ⚡ | Styled Components, Tailwind ⚡ | Redux, Context API | Jest, Cypress ⚡ | — | AWS, Netlify ⚡ |
| 2019 | **React Hooks ⚡**, Vue, Angular | Webpack 4, Rollup | **TS (mainstream)** ⚡ | Tailwind, CSS Modules | Redux, Hooks | Jest, Cypress | — | AWS, Netlify, Vercel ⚡ |
| 2020 | React 17, Vue 3 | Webpack 5, Vite ⚡ | TS | Tailwind ⚡, CSS-in-JS | Redux Toolkit | Jest, Playwright ⚡ | — | Vercel ⚡, Netlify |
| 2021 | **React > jQuery ⚡**, Svelte ⚡ | Webpack, Vite | TS ⚡ | Tailwind ⚡ | Redux Toolkit, Zustand | Jest, Playwright, Vitest ⚡ | Copilot (preview) | Vercel ⚡, Netlify |
| 2022 | React 18, Next.js 13 ⚡ | Webpack, Vite | TS 35% | Tailwind ⚡, CSS Modules | Redux Toolkit, Zustand, Jotai | Vitest, Playwright | ChatGPT ⚡ | Vercel ⚡, Cloudflare |
| 2023 | Next.js App Router ⚡, Svelte ⚡, Astro, Solid, Qwik | **Vite ≈ Webpack** ⚡ | TS 39% | Tailwind ⚡, CSS Modules | Zustand, Jotai ⚡ | **Vitest ⚡**, Playwright | **AI (Copilot/Cursor/Claude) ⚡** | Vercel, Cloudflare ⚡ |
| 2024 | React 19 ⚡, Svelte 5, Astro | **Vite ≈ Webpack** | TS 38.5% | **Tailwind 74.8%** ⚡ | Zustand, Jotai | Vitest, Playwright | **62% используют AI** ⚡ | Vercel, Cloudflare ⚡ |
| 2025 | React 19, Cursor/Code ⚡ | Vite, Bun ⚡, Rolldown ⚡ | TS | Tailwind, CSS Modules | Zustand, Jotai | Vitest, Playwright | **AI базовый навык** ⚡ | Vercel, Cloudflare, Railway |
| 2026 | + AI Agents, MCP ⚡ | Biome ⚡, Bun | TS | Tailwind | Zustand, Jotai | Vitest, Playwright | **AI-раздел в роадмапе** ⚡ | Vercel, Cloudflare, Railway |

---

## 4. Три перелома профессии

Профессия фронтенд-разработчика пережила много изменений, но только три события фундаментально меняли её определение.

### Перелом 1: React (2013) — рождение «фронтенд-инженера»

**До:** фронтенд-разработчик = верстальщик + jQuery-программист. Главный навык — кросс-браузерная вёрстка, знание CSS-хаков, DOM-манипуляция. «Инженерией» фронтенд не считался.

**После:** React ввёл три концепции, которые переопределили профессию:
1. **Компонентная модель** — UI состоит из переиспользуемых компонентов с инкапсулированным состоянием. Не «страницы», а «компоненты».
2. **Виртуальный DOM** — декларативный подход. Разработчик описывает, *что* должно быть на экране, а не *как* это сделать. Концептуальный сдвиг от императивного (jQuery) к декларативному.
3. **Однонаправленный поток данных** — предсказуемость state. Убрал «two-way binding hell» AngularJS.

**Почему это перелом:** после React «фронтенд-разработчик» стал означать инженера, а не верстальщика. React внедрил в фронтенд понятия, которые раньше были только в серверной разработке: компонентная архитектура, неизменяемость (immutability), однонаправленный поток данных. React Native (2015) расширил роль на мобильные платформы.

**Подтверждение в опросах:** Stack Overflow 2019 — React (31.3%) обгоняет Angular (30.7%); 2021 — React (40.14%) обгоняет jQuery (34.42%). jQuery — символ «до-React-эры» — уходит.

### Перелом 2: JavaScript Fatigue (2016–2017) — тулинг как профессия

**До:** bundler был утилитой. State management — личным делом. Тестирование — опциональным. «Хороший фронтендер» знал фреймворк и CSS.

**После:** взрыв npm-экосистемы (Webpack, Babel, TypeScript, Redux, CSS-in-JS, PWA, Service Workers, Next.js) сделал **тулинг отдельной областью экспертизы**. Появился навык «архитектура фронтенд-приложения» — выбор bundler'а, state-менеджера, CSS-подхода, SSR-стратегии.

**Почему это перелом:**
- Объём знаний, необходимых фронтенд-разработчику, вырос в разы. Роадмап 2017→2019 добавил 4 новых раздела (PWA, Performance, Desktop, Mobile) — крупнейшее расширение до 2025 года.
- Появился навык «удерживать темп с инструментами» (keep up with tools) — который не существовал раньше, потому что инструментов было мало.
- Термин **«JavaScript fatigue»** стал культурным символом. Jose Aguinaga's эссе *"How it feels to learn JavaScript in 2016"* (35k upvotes) — символ эпохи.
- React Hooks (2018–2019) — последний крупный паттерн-сдвиг этой эпохи: классы → функции.

**Подтверждение в опросах:** State of JS стартовал именно в 2016 — потому что экосистема стала слишком сложной, и сообществу понадобился систематический обзор. Stack Overflow 2019: front-end как роль — 32.8% респондентов.

### Перелом 3: AI-волна (2022–2025) — переопределение «разработчика»

**До:** фронтенд-разработчик пишет код. Инструменты (IDE, линтеры) — вспомогательные. Productivity определяется скоростью набора и знанием API.

**После:** AI-ассистенты (Copilot, Cursor, Claude Code) делают генерацию кода, рефакторинг, code review, docs generation — рутинной частью workflow. Stack Overflow 2024: **62%** разработчиков используют AI, рост с 44% в 2023. Роадмап developer-roadmap готовит **17 AI-тем** в новом разделе — крупнейшее расширение с 2019 года.

**Почему это перелом:**
- Меняется **определение навыка**. «Писать код» — больше не единственный способ создать функциональность. Появляется навык «промптить AI», «ревьюить AI-вывод», «понимать, когда AI ошибается».
- Меняется **структура работы**. Раньше: 80% времени — написание кода, 20% — ревью/дизайн. Сейчас: 30% — промптинг/генерация, 40% — ревью/коррекция, 30% — архитектура/дизайн.
- **MCP (2024)** — стандартизация AI-агентов, аналогично тому, как React Router стандартизировал routing. Это указывает, что AI — не «наложенная сверху фича», а **новый слой абстракции** в профессии.
- AI-раздел в роадмапе (2026) — **первый новый крупный раздел с 2019 года**. С 2019 по 2025 профессия «консолидировалась» (Vite, Tailwind, TS), но не росла качественно. AI — первое качественное расширение.

**Подтверждение в опросах:** Stack Overflow 2023 — AI section debuts, 70% используют/планируют. 2024 — 62% используют (рост +18pp за год). 70% профессиональных разработчиков **не считают** AI угрозой для работы.

---

## 5. Количественные данные опросов

### 5.1 State of JS: Фронтенд-фреймворки

#### State of JS 2023 — "Used it" (среди ~21,600 JS-респондентов)

| Фреймворк | Использовали | Слышали | Никогда не слышали |
|---|---|---|---|
| React | **84.4%** | 15.5% | ~0% |
| Vue.js | **50.1%** | 49.5% | ~0.4% |
| Angular | **45.8%** | 53.9% | ~0.3% |
| Svelte | **25.8%** | 70.5% | 3.7% |
| Preact | **13.7%** | 70.0% | 16.3% |

*Источник: [2023.stateofjs.com](https://2023.stateofjs.com/en-US/libraries/front-end-frameworks/)*

#### State of JS 2024 — "Used at work" (из 12,802 профессиональных респондентов)

| Фреймворк | Count | % "at work" |
|---|---|---|
| **React** | 8,548 | **66.8%** |
| Vue.js | 3,976 | 31.1% |
| Angular | 3,642 | 28.4% |
| Svelte | 1,409 | 11.0% |
| Lit | 557 | 4.4% |
| Preact | 490 | 3.8% |
| Alpine.js | 389 | 3.0% |
| Solid | 345 | 2.7% |
| HTMX | 316 | 2.5% |
| Qwik | 130 | 1.0% |

*Источник: [2024.stateofjs.com](https://2024.stateofjs.com/en-US/libraries/front-end-frameworks/)*

> **Комментарий State of JS 2024:** *"Top three frontend frameworks were all launched over a decade ago."* (React 2013, Vue 2014, Angular 2010/2016)

### 5.2 Stack Overflow: Веб-фреймворки (год-за-годом, % использования)

| Фреймворк | 2019 | 2021 | 2022 | 2023 | 2024 |
|---|---|---|---|---|---|
| jQuery | **48.7%** (#1) | 34.42% | 28.57% | 21.98% | 21.4% |
| React.js | 31.3% | **40.14%** (#1) | 42.62% | 40.58% | 39.5% |
| Angular | 30.7% | 22.96% | 20.39% | 17.46% | 17.1% |
| Vue.js | 15.2% | 18.97% | 18.82% | 16.38% | 15.4% |
| Next.js | n/a | n/a | 13.52% | 16.67% | 17.9% |
| Svelte | n/a | 2.75% | 4.58% | 6.62% | 6.5% |
| Express | 19.7% | 23.82% | 22.99% | 19.28% | 17.8% |
| Node.js | n/a | n/a | **47.12%** (#1) | **42.65%** (#1) | **40.8%** (#1) |

> **Момент обгона (Stack Overflow 2021):** *"React.js surpassed jQuery as the most commonly used web framework."* — символический конец jQuery-эры.

### 5.3 TypeScript: рост (Stack Overflow, % использования)

| Год | JavaScript | TypeScript | Ранг TS | Проф. разработчики TS |
|---|---|---|---|---|
| 2019 | 67.8% | **21.2%** | ~10-й | 23.5% |
| 2021 | 64.96% | **30.19%** | 7-й | 36.42% |
| 2022 | 65.36% | **34.83%** | 5-й | 40.08% |
| 2023 | 63.61% | **38.87%** | 5-й | 43.75% |
| 2024 | 62.3% | **38.5%** | 5-й | **43.4%** |

> TypeScript вырос с 21% (2019) до 43% среди профессионалов (2024) — удвоение за 5 лет. В 2022 вошёл в топ-5 языков Stack Overflow.

### 5.4 State of JS 2024: Build tools ("Used at work", 11,409 респондентов)

| Tool | Count | % "at work" |
|---|---|---|
| **webpack** | 7,927 | **69.5%** |
| **Vite** | 7,909 | **69.3%** |
| esbuild | 4,112 | 36.0% |
| tsc CLI | 3,051 | 26.7% |
| Rollup | 2,889 | 25.3% |
| SWC | 1,613 | 14.1% |
| Turbopack | 1,191 | 10.4% |
| Parcel | 818 | 7.2% |
| Biome | 573 | 5.0% |
| Bun (write-in) | 35 | — |

> **Vite сравнялся с Webpack в 2024** (69.3% vs 69.5%). Учитывая рост Vite и стагнацию Webpack, в 2025–2026 Vite, вероятно, обгонит.

### 5.5 State of JS 2024: Meta-frameworks ("Used at work", 11,538 респондентов)

| Meta-framework | Count | % "at work" |
|---|---|---|
| **Next.js** | 5,147 | **44.6%** |
| Nuxt | 1,883 | 16.3% |
| Astro | 1,461 | 12.7% |
| SvelteKit | 1,015 | 8.8% |
| Remix | 720 | 6.2% |
| Gatsby | 618 | 5.4% |
| None | 3,801 | 33.0% |

### 5.6 State of CSS 2024: CSS-подходы

#### CSS-фреймворки (4,890 респондентов)

| Framework | % |
|---|---|
| **Tailwind CSS** | **74.8%** |
| Bootstrap | 53.6% |
| Ant Design | 13.2% |
| Materialize CSS | 12.6% |
| Bulma | 9.1% |

#### CSS-in-JS (3,458 респондентов)

| Library | % |
|---|---|
| **CSS Modules** | **61.1%** |
| Styled Components | 59.1% |
| Emotion | 25.3% |
| Styled JSX | 19.5% |
| vanilla-extract | 6.8% |

#### Препроцессоры (6,897 респондентов)

| Tool | % |
|---|---|
| **Sass/SCSS** | **67.5%** |
| PostCSS | 38.0% |
| Less | 10.5% |
| None | 19.1% |

### 5.7 State of JS 2024: Тестирование ("Used at work", 11,667 респондентов)

| Tool | Count | % "at work" |
|---|---|---|
| Jest | 7,262 | **62.2%** |
| Storybook | 4,660 | 39.9% |
| **Vitest** | 3,986 | **34.2%** |
| Playwright | 3,674 | 31.5% |
| Cypress | 3,603 | 30.9% |
| Testing Library | 2,970 | 25.5% |
| Mocha | 2,082 | 17.8% |
| Selenium | 1,130 | 9.7% |

> **Vitest** — #1 по interest/retention/positivity, обходит Jest по настроению, хотя Jest всё ещё лидирует по raw usage.

### 5.8 Stack Overflow 2024: Хостинг/Cloud платформы

| Platform | % | Platform | % |
|---|---|---|---|
| AWS | 48.0% | Heroku | 8.2% |
| Microsoft Azure | 27.8% | **Netlify** | 7.0% |
| Google Cloud | 25.1% | VMware | 6.6% |
| **Cloudflare** | 15.1% | Hetzner | 5.0% |
| Firebase | 13.9% | Supabase | 3.8% |
| **Vercel** | 11.9% | Render | 2.8% |
| Digital Ocean | 11.7% | Fly.io | 2.6% |

### 5.9 Stack Overflow: AI-инструменты

| Metric | 2023 | 2024 |
|---|---|---|
| Используют или планируют AI | 70% | 76% |
| **Сейчас используют** | 44% | **62%** |
| ChatGPT (most used) | 79% want to keep | **74%** want to keep |
| AI — угроза работе? (проф. разработчики) | — | **70% говорят "нет"** |

### 5.10 Stack Overflow: Роль "Front-end Developer" (% респондентов)

| Год | Front-end | Full-stack | Back-end | Метод опроса |
|---|---|---|---|---|
| 2019 | **32.8%** | 51.9% | 50.0% | multi-select |
| 2021 | 27.42% | 49.47% | 43.73% | multi-select |
| 2022 | 25.96% | 46.82% | 43.38% | multi-select |
| 2023 | 6.6% | 33.48% | 17.88% | **single-select** (primary role) |

> **Внимание:** 2023 изменил метод (multi → single select), поэтому 6.6% **несравнимо** с предыдущими годами. Тренд 2019→2022 (multi-select): front-end снижается с 33% до 26%, потому что **граница front-end ↔ full-stack размывается** — фронтенд-разработчик теперь обязан знать SSR, API routes, edge functions.

---

## 6. Паттерны эволюции

### 6.1 Что остаётся неизменным (фундамент)

- **HTML, CSS, JavaScript** — основа основ с 1990-х. Ни одна эпоха не убрала их из роадмапа.
- **Кросс-браузерность** — изменилась форма (IE6 hacks → Autoprefixer → Polyfills), но не суть.
- **DOM-манипуляция** — абстрагирована (React), но понимание DOM остаётся важным.
- **Семантическая разметка и доступность** — в роадмапе с 2017, не исчезают.
- **HTTP/сеть** — Fetch API заменил XMLHttpRequest, но концепции те же.

### 6.2 Что циклично возвращается

- **SSR → SSG → SSR → RSC.** Серверный рендеринг умирал (2010-е — SPA), вернулся (Next.js 2016+, Nuxt), мутировал (React Server Components 2020+). Цикл: сервер → клиент → сервер.
- **Изоляция стилей.** CSS → Sass (nesting) → CSS Modules (JS-импорты) → Styled Components (CSS-in-JS) → Tailwind (utility classes, «изоляция через неизбыточность»). Проблема та же, решения разные.
- **Компиляторы.** CoffeeScript (2010) → Babel (2014) → TypeScript (2012+) → SWC/esbuild (2020+). Каждый раз: «нужно компилировать JS в JS», причина меняется (синтаксис → совместимость → типы → скорость).
- **«Конфиг-хелл» → «zero-config».** Grunt (много конфига) → Webpack (ещё больше конфига) → Parcel (zero-config, 2017) → Vite (sensible defaults, 2020). Цикл повторяется каждые 5–7 лет.
- **Бандлеры на Rust/Go.** npm (JS) → Webpack (JS) → esbuild (Go, 2020) → SWC (Rust, 2020) → Rolldown (Rust, 2024) → Biome (Rust, 2024). «Перепишем тулинг на системном языке» — повторяющийся паттерн.

### 6.3 Что исчезает навсегда

- **jQuery** — в роадмапе 2017→2018 (опциональный), 2024 (удалён). Stack Overflow: 48.7% (2019) → 21.4% (2024). Доминирующая библиотека 2006–2016 ушла за 8 лет.
- **AngularJS** — несоответствие Angular 2 (2016) убило его. Stack Overflow 2024: 6.8% (legacy).
- **CoffeeScript** — был #1-альтернативой JS в 2011–2013, исчез с приходом ES6+Babel.
- **Bower** — package manager для фронтенда (2012–2015), убит npm.
- **Grunt, Gulp** — task runners, убиты npm scripts + bundlers.
- **Flow (type checker)** — альтернатива TypeScript от Facebook, исчез к 2020 (TypeScript победил).
- **Browserify, RequireJS, AMD** — модульные системы до ES modules.
- **Bootstrap, Bulma, Materialize, Semantic UI** — CSS-фреймворки «компонентного» типа, убиты Tailwind (utility-first).

### 6.4 Что ускоряет/замедляет эволюцию

- **Ускорители:** крупные корпорации (Facebook/Meta → React, Google → Angular, Vercel → Next.js), независимые авторы-визионеры (Evan You → Vue/Vite, Rich Harris → Svelte/Rollup), новыми техническими ограничениями (mobile performance → PWA, server cost → SSR/RSC).
- **Замедлители:** консервативные enterprise-кодстайлы (jQuery жив в enterprise до сих пор), IE-поддержка (до 2022), браузерные войны (фрагментация замедляла стандарты), cost-of-migration (AngularJS → Angular 2 — разрушительный пример).

---

## 7. Источники

### 7.1 Роадмап developer-roadmap (git-история)

| Год | Коммит | Файл | Формат |
|---|---|---|---|
| 2017 | 665dcdf24 | project-files/frontend-map.json | Balsamiq JSON |
| 2018 | 306915a40 | project-files/frontend-map.json | Balsamiq JSON |
| 2019 | b208eaa1b | project/frontend-map.json | Balsamiq JSON |
| 2023 | bb7f1f4d6 | src/data/roadmaps/frontend/frontend.json | Balsamiq JSON (копия) |
| 2024 | f5fc71aad | src/data/roadmaps/frontend/frontend.json | React Flow JSON |
| 2025 | 152e2a35c | src/data/roadmaps/frontend/content/*.md | Перезапись контента |
| 2026 | 74e2a7105 | src/data/roadmaps/frontend/content/*.md | Sync content (AI-темы) |
| 2026 | 3db5d4a5e | src/data/roadmaps/frontend/content/*.md | Cleanup orphaned |
| 2026 | 949395506 | src/data/roadmaps/frontend/frontend.json | React Flow JSON |

### 7.2 State of JS / State of CSS

- [State of JS 2023 — Frontend frameworks](https://2023.stateofjs.com/en-US/libraries/front-end-frameworks/) — "Used it" % (React 84.4, Vue 50.1, Angular 45.8, Svelte 25.8)
- [State of JS 2024 — Frontend frameworks](https://2024.stateofjs.com/en-US/libraries/front-end-frameworks/) — "Used at work" counts, happiness 3.8/4
- [State of JS 2024 — Meta-frameworks](https://2024.stateofjs.com/en-US/libraries/meta-frameworks/) — Next.js 44.6%, Nuxt 16.3%, Astro 12.7%
- [State of JS 2024 — Build tools](https://2024.stateofjs.com/en-US/libraries/build_tools/) — Vite 69.3% ≈ Webpack 69.5%
- [State of JS 2024 — Testing](https://2024.stateofjs.com/en-US/libraries/testing/) — Jest 62.2%, Vitest 34.2%, Playwright 31.5%
- [State of CSS 2024 — Tools](https://2024.stateofcss.com/en-US/tools/) — Tailwind 74.8%, Sass 67.5%, CSS Modules 61.1%
- [State of JS 2023 intro](https://2023.stateofjs.com/en-US/) — "JavaScript fatigue" cultural reference

### 7.3 Stack Overflow Developer Survey

- [SO 2019](https://survey.stackoverflow.co/2019) — jQuery 48.7% #1, React 31.3%, TS 21.2%, front-end 32.8%
- [SO 2021](https://survey.stackoverflow.co/2021/) — React 40.14% > jQuery 34.42% (обгон), Svelte most loved
- [SO 2022](https://survey.stackoverflow.co/2022) — TS 34.83% #5, React 42.62%, jQuery 28.57%
- [SO 2023](https://survey.stackoverflow.co/2023) — AI section debuts, 70% use/plan AI, TS 38.87%
- [SO 2024 — Technology](https://survey.stackoverflow.co/2024/technology/) — TS 38.5%, Svelte 73% retention, 62% use AI, Vercel 11.9%
- [SO 2024 — Overview](https://survey.stackoverflow.co/2024/) — 65,437 respondents, methodology

### 7.4 Таймлайн релизов

- [React (Wikipedia)](https://en.wikipedia.org/wiki/React_(JavaScript_library)) — OSS 2013-05-29, Fiber/React 16 2017, Hooks 16.8 2019-02-06, RSC Dec 2020, React 19 2024-12-05, React Foundation 2025
- [Vue.js (Wikipedia)](https://en.wikipedia.org/wiki/Vue.js) — First commit July 2013, public Feb 2014, Vue 1.0 2015-10-27, Vue 2.0 2016-09-30, Vue 3.0 2020-09-18, Vite by Evan You

### 7.5 Дополнительные материалы

- *"How it feels to learn JavaScript in 2016"* — Jose Aguinaga (Medium, 2016) — символ "JavaScript fatigue"
- [State of JS archives](https://stateofjs.com/) — 2016→2024, ежегодные опросы
- [Stack Overflow Survey archive](https://survey.stackoverflow.co/) — 2011→2025

---

*Документ основан на анализе git-истории репозитория developer-roadmap (2017–2026), данных State of JS (2016–2024), State of CSS (2024) и Stack Overflow Developer Survey (2019–2024). Количественные данные — из опросов; структурные изменения — из роадмапа; интерпретации эпох и переломов — авторский анализ.*
