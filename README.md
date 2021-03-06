# Проект «newspaper-grid-layout»

[Демо проекта](https://denyshutsal.github.io/newspaper-grid-layout/)

---

## Установка

Требуются установленный [git](https://git-scm.com/) и [Node.js (LTS)](https://nodejs.org/en/).

1. Клонировать репозиторий.
2. Установить зависимости проекта: `npm i` (может быть долго, особенно на Windows).

---

## Команды

`npm i` - установка зависимостей.

`npm start` или `gulp` - запустить сборку, сервер и слежение за файлами.

`npm run build` - финальная сборка проекта.

`npm run deploy` - опубликовать собранный проект на `GitHub Pages` в ветку `gh-pages` удаленного репозитория.

`npm run test` - общее тестирование проекта.

`npm run test:style` - тестирование стилей.

`npm run test:js` - тестирование скриптов.

Остальные команды описаны в файле `gulpfile.js`

Предполагается, что все команды выполняются в bash (для OSX и Linux это самый обычный встроенный терминал, для Windows это, к примеру, Git Bash). В Windows установку пакетов (npm i) нужно выполять в терминале, запущенном от имени администратора.

---

Настроены прекоммит хуки.

---

## Структура проекта

```bash
├── build/            # каталог сборки проекта (генерируется автоматически)
├── source/           # каталог файлов проекта
│   ├── fonts/        # каталог шрифтов
│   ├── img/          # каталог растровых и векторных изображений
│   ├── js/           # каталог скриптов
│   ├── sass/         # каталог стилей
│   └── index.html    # файл разметки страницы
│   └── *.html        # дополнительные страницы разметки
│   └── .htaccess     # файл дополнительной конфигурации веб-сервера
├── .editorconfig     # файл конфигурации настроек редактора
├── .eslintrc.json    # файл конфигурации eslint
├── .eslintignore     # файл исключений eslint
├── .gitattributes    # файл атрибутов git
├── .gitignore        # файл исключений git
├── .prettierrc       # файл конфигурации prettier
├── .prettierignore   # файл исключений prettier
├── .stylelintrc.json # файл конфигурации stylelint
├── .stylelintignore  # файл исключений stylelint
├── gulpfile.js       # конфигурация gulp-сборщика проекта
├── package.json      # файл конфигурация npm зависимостей и настроек проекта
├── package-lock.json # автоматически генерируется при изменениях в node_modules, либо package.json
├── README.md         # документация проекта
```
