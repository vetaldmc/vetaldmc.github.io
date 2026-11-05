# TODO

## Завершено
- ✅ Создание базовых страниц EN/UK
- ✅ Резюме (HTML + PDF + печатная версия)
- ✅ Дорожная карта
- ✅ CSS с CSS-переменными и `prefers-color-scheme`
- ✅ Интеграция CheerpJ (код, но не работает без jar)

## P0 — Критические (блокируют качество)

- [ ] **Создать `AI_HANDOFF/`** на диске (эти документы).
- [ ] **TASK-P0-01: Переключатель темы** — кнопка в хедере, `[data-theme]`, `localStorage`.
- [ ] **TASK-P0-02: Мобильное меню** — гамбургер `< 48em`, доступное (aria-expanded, focus trap).
- [ ] **TASK-P0-03: Lazy-load iframe резюме** — `loading="lazy"` на `<iframe class="paper">`.
- [ ] **TASK-P0-04: Исправить путь к jar** — `/app/game/game.jar` → `game/game.jar`.
- [ ] **TASK-P0-05: Lazy-load CheerpJ** — загрузка по кнопке «Play», а не автоматически.

## P1 — Высокий приоритет

- [ ] **TASK-P1-01: Scroll-reveal анимации** — Intersection Observer + CSS, с `prefers-reduced-motion`.
- [ ] **TASK-P1-02: Футер с карточками мессенджеров** — Telegram + Email, с аватарами (нужны изображения или заглушки-инициалы).
- [ ] **TASK-P1-03: Заполнить projects.html** — заменить placeholder-контент (нужна информация от владельца).
- [ ] **TASK-P1-04: Хедер — индикатор прогресса прокрутки** — тонкая полоса.
- [ ] **TASK-P1-05: Убедиться, что game.jar существует** — иначе ISSUE-001 не решить.

## P2 — Средний приоритет

- [ ] **TASK-P2-01: Self-host шрифты** — Manrope `.woff2` локально, убрать Google Fonts.
- [ ] **TASK-P2-02: Проверка контрастности WCAG AA** — `--muted` на `--bg`.
- [ ] **TASK-P2-03: Вынести inline JS** — `game.js` для game.html, `app.js` для общих скриптов.
- [ ] **TASK-P2-04: Добавить `og:image` и meta** — соцсети, SEO.
- [ ] **TASK-P2-05: Проверить UK PDF** — визуально (ISSUE-005).

## P3 — Низкий приоритет

- [ ] **TASK-P3-01: CSP-заголовки** — если хостинг позволяет (Netlify/Cloudflare).
- [ ] **TASK-P3-02: Sitemap.xml + robots.txt** — SEO.
- [ ] **TASK-P3-03: Пересмотреть архитектуру i18n** — при добавлении 3-го языка.
- [ ] **TASK-P3-04: Микроанимации** — hover на `.card`, `.btn`, nav links (лёгкие, CSS-only).

## Отложено
- Рефакторинг на SSG (Astro/Eleventy) — только при росте проекта.