# Пет-проект ипотечный калькулятор

Стек: HTML, CSS(SCSS), JavaScript, TypeScript, React, Vite

Скриншоты исходников:
- изначальный вид https://disk.yandex.ru/i/Kw8EoecgLniriA
- после расчета калькулятора https://disk.yandex.ru/i/vF046lNKQDzq1A  

Структура проекта:
- src/ — исходные файлы проекта
- src/shared/types — папка с переиспользуемыми типами
- src/shared/ui — папка с переиспользуемыми ui-kit (используются только для отображения, ничего не знают о бизнес-логике)
- src/features — папка с базовым кодом с бизнес-логикой

Важные файлы:
- index.html — HTML-файл страницы
- src/app/main.tsx — точка входа приложения
- src/styles/globals.scss — корневой файл стилей
- src/demo/Demo.tsx — временный файл для демонстраций

## Установка и запуск
Для установки и запуска проекта необходимо выполнить команды

```
npm install
npm run dev
```

или

```
yarn
yarn dev
```
## Сборка

```
npm run build
```

или

```
yarn build
```

