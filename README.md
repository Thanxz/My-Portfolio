# Готовый сайт-портфолио

Это простой статический сайт: его можно бесплатно разместить на GitHub Pages или Cloudflare Pages.

## Как редактировать

Откройте `index.html` и замените:

- `Ваше имя`
- тексты в блоках «Обо мне», «Услуги», «Работы»
- контакты: email, Telegram, Instagram
- инициалы `ВИ` в карточке
- названия проектов

Основные цвета и внешний вид лежат в `assets/styles.css`.

## Как опубликовать на GitHub Pages

1. Создайте репозиторий на GitHub.
2. Загрузите в него файлы из этой папки: `index.html`, папку `assets`, `README.md`.
3. Откройте Settings → Pages.
4. В Source выберите Deploy from a branch.
5. Выберите ветку `main` и папку `/root`.
6. Сохраните и дождитесь ссылки.

## Как опубликовать на Cloudflare Pages

1. Загрузите эти файлы в репозиторий GitHub.
2. В Cloudflare откройте Workers & Pages → Create → Pages.
3. Подключите GitHub-репозиторий.
4. Build command оставьте пустым.
5. Output directory: `/` или оставьте пустым для статического сайта.
6. Нажмите Deploy.

## Структура

```text
portfolio_site/
├── index.html
├── README.md
└── assets/
    ├── styles.css
    ├── script.js
    └── favicon.svg
```
