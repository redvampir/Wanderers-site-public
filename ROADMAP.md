# ROADMAP — Путь проекта «Странники»

## ✅ Блок 0 — Подготовка
- [x] Установлен Node.js, Git, VS Code
- [x] Созданы два удалённых репозитория (`origin` и `public`)
- [x] Выполнен первый коммит с базовыми настройками

### Модуль 1 - Базовые операции Git
- [x] Что происходит внутри Git
- [x] Настройка перед первым коммитом
- [x] Базовый рабочий цикл
- [x] Игнорирование файлов
- [x] Просмотр истории
- [x] Быстрое «отменить»
- [x] stash: быстро спрятать черновики

### Модуль 2 — ветки и Pull Request
- [x] Понять, зачем нужны ветки и как они связаны с коммитами.
- [x] Научиться работать в отдельной ветке, пушить её на GitHub и открывать Pull Request (PR).
- [x] Слить PR в main, синхронизировать оба репозитория origin (приватный) и public (публичный).

## ✅ Блок 1 — HTML / CSS (UI-каркас)

### Модуль 3 — HTML Core
- [x] Подготовка проекта в VS Code к работе с кириллицей
- [ ] Очистить `src/index.html`
- [ ] Быстро набрать каркас через Emmet
- [ ] Форматировать (Shift+Alt+F)
- [ ] Проверить в Live Server и в W3C Validator
- [ ] Семантическая разметка: `<header>`, `<nav>`, `<main>`, `<footer>`
- [ ] Проверка и исправление `src/index.html`
- [ ] Коммит: `feat(html): add semantic structure…`, PR и метка `module-3-done`
- [ ] HTML Project Structure & Partials

### Модуль 4 — HTML Project Structure & Partials
- [ ] Разделение шаблона на части (header, footer, nav)
- [ ] Настройка подключения через `index.html` или систему шаблонов
- [ ] Создание Issue, ветки `feature/html-partials`, PR

## ⏳ Блок 1 (CSS)
- [ ] CSS Fundamentals: Каскад, специфичность, базовая стилизация, box-model, типографика
- [ ] CSS Layout — Flexbox: Оси, выравнивание, адаптивный navbar
- [ ] CSS Layout — Grid: Grid‑шаблоны, auto‑placement, галерея карточек
- [ ] Responsive & Accessibility: media queries, mobile‑first, aria‑labels, цветовые контрасты
- [ ] Адаптивность и доступность

## ⏳ Блок 2 (JavaScript)
- [ ] JS Basics: Переменные, типы, операторы, строгий режим
- [ ] Functions & Scope: Объявления, стрелочные, замыкания
- [ ] Modules & Project Split: import/export, разбиение кода, баррель‑паттерн, как Vite строит дерево зависимостей
- [ ] Objects & Classes: Прототипы, class, наследование, приватные поля
- [ ] Async JavaScript: Callbacks, Promises, async/await, fetch
- [ ] Browser Storage & Templating: LocalStorage, SessionStorage, template literals, ввод Nunjucks

## ⏳ Блок 3 (Инструменты)
- [ ] Dev Tools & Build Pipeline: Vite конфиг, точка входа main.js/main.tsx, алиасы, Husky pre‑commit
- [ ] Dice Roller: RNG, d20/d6, UI‑анимация, лог бросков

## ⏳ Блок 4 (Бэкенд и React)
- [ ] Node + Express API: REST, CRUD персонажей, MongoDB, JWT
- [ ] React Integration: Vite + React TS, Router, Context, Tailwind + MUI

## ⏳ Блок 5 (Тестирование и доставка)
- [ ] Testing: Jest, React Testing Library, Cypress, GitHub Actions
- [ ] Deploy: Vercel / Render, домен, переменные, Sentry
- [ ] Git Pro Tricks: cherry‑pick, interactive rebase, bisect, submodules

## ⚓ Блок 6 — Будущее (реал-тайм, PWA, WebRTC...)
