# WebFont Baron Neue

Пакет для установки веб-шрифта: Baron Neue.

## Установка

Чтобы установить пакет, Вы можете воспользоваться командой в CLI:

```bash 
npm install --save https://github.com/getscope/npm-webfont-baron-neue
```

или в файле `package.json` создать свойство `dependencies` и добавить ссылку на github-репозиторий:

```json 
{
    "dependencies": {
        "@getscope/npm-webfont-baron-neue": "github:getscope/npm-webfont-baron-neue"
    }
}
```

и выполнить команду в CLI для обновления установленных зависимостей:

```bash 
npm update
```

## Примеры использования и подключения

```css 
body {
    font-family: 'Baron Neue', sans-serif;
}
```

Для импорта веб-шрифта в SCSS, Вы можете воспользоваться следующими путями:

```scss 
@import "node_modules/@getscope/npm-webfont-baron-neue/src/scss/_400-normal.scss";
@import "node_modules/@getscope/npm-webfont-baron-neue/src/scss/_700-normal.scss";
@import "node_modules/@getscope/npm-webfont-baron-neue/src/scss/_900-normal.scss";
@import "node_modules/@getscope/npm-webfont-baron-neue/src/scss/_all-normal.scss";
```
