# Шаблонизатор [PugJS](https://pugjs.org/)
---
Cкачиваем шаблонизатор
```shell
npm install pug
```

Устанавливаем PugJS
```shell
npm install --save pug
```
==Проверить==\посмотреть версию PugJS
```shell
pug -V
```

Устанавливаем pug-cli в
```shell
npm install --save-dev pug-cli
```
==Проверить==\посмотреть версию pug-cli
```shell
pug -V
```

Можно запустить напрямую
```shell
pug index.pug --out dist --watch
```
Можно добавить npm-scritps в конфиг
```package.json
"scripts": {
    "build:pug": "npx pug --watch --pretty index.pug --out ./"
}
```
и запускать через него
```shell
npm run build:pug
