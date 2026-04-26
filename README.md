# pablogolobaro.github.io

Личный сайт. Опубликован на [pablogolobaro.github.io](https://pablogolobaro.github.io/).

## Стек

Чистый HTML и CSS в одном файле, без сборки и зависимостей. Шрифты — Google Fonts (Fraunces, Inter Tight, JetBrains Mono).

## Структура

```
.
├── index.html     — страница целиком
├── favicon.svg    — иконка вкладки
└── photo.jpg      — портрет
```

## Локальный просмотр

Открыть `index.html` двойным кликом — этого достаточно. Можно поднять локальный сервер, если хочется:

```bash
python3 -m http.server 8000
```

## Деплой

Автоматически через GitHub Pages. Любой push в `main` публикуется на корневой домен через 30–60 секунд.
