# webpack-base

Минимальный шаблон проекта на Webpack для разработки на чистом HTML, CSS и JavaScript.

## 📦 Возможности

- Сборка HTML, CSS и JS с помощью Webpack
- Live-reload через `webpack-dev-server`
- Разделение конфигураций на `dev` и `prod`
- Гибкая структура файлов и папок
- Поддержка структуры для стилей, компонентов и ассетов
- Готов к расширению (SCSS, Babel, ESLint и т.д.)

## 🚀 Скрипты

- `npm start` — запуск дев-сервера
- `npm run build` — сборка проекта в папку `dist`

## 📁 Структура проекта

src/
├── assets/
│ ├── fonts/ # Шрифты
│ └── img/ # Изображения и иконки
│
├── js/
│ ├── components/ # Переиспользуемые компоненты JS
│ ├── controllers/ # Контроллеры для логики
│ ├── modules/ # Отдельные модули
│ └── utils/ # Вспомогательные функции
│
├── styles/
│ ├── base/ # Базовые стили (reset, typography)
│ ├── components/ # Стили для компонентов
│ ├── layout/ # Стили разметки (header, footer, grid)
│ ├── pages/ # Стили для отдельных страниц
│ ├── tokens/ # Переменные, цвета, шрифты
│ └── style.css # Главный CSS-файл (точка входа)
│
├── index.js # Точка входа JS
└── template.html # HTML-шаблон

## 🛠 Зависимости

Установленные зависимости и лоадеры можно посмотреть в `package.json`.

## 📌 Использование

1. Склонировать репозиторий:

git clone https://github.com/Roman-oryol/webpack-base.git

2. Установить зависимости:

npm install

3. Запустить дев-сервер:

npm start

4. Собрать проект:

npm run build
