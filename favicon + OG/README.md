# Фавиконки

Обрати внимание: в самом маленьком размере 16x16 картинка визуально **отличается**

![demo_svg-favicon-sizes.png](..%2Fdemo%2Fdemo_svg-favicon-sizes.png)

## Подключение

Пробуем этот вариант, если не заводится — основной:

1. Кладём папку `favicon` так, чтобы её содержимое было доступно в корне сайта
2. Вставляем этот код в `<head>` страниц:

```html
<link rel="apple-touch-icon" sizes="180x180" href="/apple-touch-icon.png">
<link rel="icon" type="image/svg+xml" sizes="any" href="/favicon.svg">
<link rel="icon" href="/favicon.ico">
<link rel="manifest" href="/site.webmanifest">
```

# Open Graph теги

Обновляем только картинку. Новая `og.png`, имеет тот же размер, что и старая (лежит по адресу https://cdn1.tu-tu.ru/images2/logo/og_2018.png)

Для того, чтобы превью обновилось в телеграме, используй бота [@webpagebot](https://telegram.me/webpagebot)