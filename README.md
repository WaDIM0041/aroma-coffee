# Aroma — Кофейня

Одностраничный сайт уютной кофейни в центре Москвы. Спешелти кофе, авторские десерты и атмосфера тепла.

![Tech](https://img.shields.io/badge/HTML-5-orange) ![CSS](https://img.shields.io/badge/CSS-3-blue) ![JS](https://img.shields.io/badge/JavaScript-Vanilla-yellow) ![License](https://img.shields.io/badge/License-MIT-green)

## Возможности

- Полностью адаптивная вёрстка (desktop / tablet / mobile)
- Меню с фильтрацией по категориям (кофе, чай, десерты, еда)
- Форма бронирования столика с валидацией (данные хранятся в localStorage браузера)
- Проверка существующей брони по номеру телефона
- Анимации: прелоадер, частицы в hero, счётчики статистики, reveal-эффекты
- Аккордеон FAQ, тосты, кнопка «наверх», прогресс чтения

## Быстрый старт

Сайт — чистый HTML/CSS/JS без сборки и зависимостей. Достаточно открыть `index.html` в браузере или поднять любой статический сервер:

```bash
# Python
python3 -m http.server 8080

# Node.js
npx serve .
```

Откройте `http://localhost:8080`.

## Развертывание на GitHub Pages

Сайт подготовлен для публикации через GitHub Pages. Есть два варианта:

### Вариант 1 — автоматически через GitHub Actions

В репозитории уже есть workflow [`.github/workflows/pages.yml`](.github/workflows/pages.yml). При пуше в ветку `main` сайт автоматически соберётся и опубликуется на GitHub Pages.

1. Загрузите репозиторий на GitHub.
2. Откройте **Settings → Pages → Source** и выберите **GitHub Actions**.
3. Пуш в `main` — сайт станет доступен по адресу `https://<username>.github.io/<repo>/`.

### Вариант 2 — развертывание из ветки

1. Загрузите репозиторий на GitHub.
2. В **Settings → Pages → Source** выберите `Deploy from a branch`, ветку `main` и папку `/ (root)`.
3. Сайт появится по адресу `https://<username>.github.io/<repo>/`.

## Структура проекта

```
├── index.html              # Одностраничный сайт (HTML + CSS + JS)
├── DESIGN-HANDOFF.md       # Техническое описание экспортированного прототипа
├── DESIGN-MANIFEST.json    # Манифест исходных файлов прототипа
├── .github/workflows/
│   └── pages.yml           # Workflow автоматического развертывания на GitHub Pages
├── LICENSE
└── README.md
```

## Лицензия

Проект распространяется под лицензией [MIT](LICENSE).
