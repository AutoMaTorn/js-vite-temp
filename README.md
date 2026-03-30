# Vite JavaScript Template

🚀 Стартовый шаблон для быстрого начала разработки на JavaScript с использованием Vite.

## 📋 Описание

Этот шаблон предоставляет готовую базовую настройку для проектов на чистом JavaScript с использованием современного сборщика Vite. Идеально подходит для быстрого старта новых проектов, прототипирования и обучения.

## ✨ Особенности

- ⚡ **Vite** - быстрый сборщик для современной веб-разработки
- 🎯 **Чистый JavaScript** - без фреймворков, только ванильный JS
- 🎨 **Sass/SCSS поддержка** - готовые стили с препроцессором
- 📱 **Адаптивная верстка** - мобильная версия включена
- 🔧 **Простая конфигурация** - минимальная настройка для начала работы

## 🚀 Быстрый старт

### Предварительные требования

Убедитесь, что у вас установлены:
- [Node.js](https://nodejs.org/) (версия 14 или выше)
- [npm](https://www.npmjs.com/) или [yarn](https://yarnpkg.com/)

### Установка

1. **Клонируйте репозиторий**
```bash
git clone https://github.com/AutoMaTorn/js-vite-temp.git
cd js-vite-temp
```
Установите зависимости

```bash
npm install
```
Запустите сервер разработки

```bash
npm run dev
```
Откройте в браузере

```text
http://localhost:5173
```
📁 Структура проекта
```text
js-vite-temp/
├── src/
│   ├── scss/
│   │   ├── style.scss      # Главный файл стилей
│   │   └── variables.scss  # Переменные Sass
│   ├── js/
│   │   └── main.js         # Главный JavaScript файл
│   └── index.html          # Главный HTML файл
├── package.json
├── vite.config.js          # Конфигурация Vite
└── README.md
```

🛠 Доступные команды
```bash
# Запуск сервера разработки
npm run dev

# Сборка для production
npm run build

# Просмотр собранной версии
npm run preview

# Линтинг кода
npm run lint
```

🎨 Стилизация
Проект использует Sass/SCSS для стилей. Основные файлы:

src/scss/variables.scss - переменные цветов, шрифтов и размеров

src/scss/style.scss - основные стили проекта

Пример использования переменных:

```scss
// В variables.scss
$primary-color: #646cff;
$font-family: Inter, system-ui, Avenir, Helvetica, Arial, sans-serif;

// В style.scss
@use './variables.scss' as *;

body {
  font-family: $font-family;
  color: $primary-color;
}
```

📱 Адаптивность
Шаблон включает базовую адаптивную верстку с медиа-запросами:


```scss
// Мобильные устройства
@media (max-width: 768px) {
  .container {
    padding: 0 1rem;
  }
}
```

🔧 Конфигурация Vite
Основные настройки в vite.config.js:


```javascript
import { defineConfig } from 'vite'

export default defineConfig({
  server: {
    host: 'localhost',
    port: 5173,
    open: true // автоматически открывать браузер
  }
})
```

📦 Производственная сборка
Для создания production-сборки выполните:

```bash
npm run build
```
👨‍💻 Автор
AutoMaTorn - GitHub
Команде Vite за отличный инструмент сборки

## Сообществу JavaScript за вдохновение

