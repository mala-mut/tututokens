# Фавиконки

Обрати внимание: в самом маленьком размере 16x16 картинка визуально **отличается**

![demo_svg-favicon-sizes.png](..%2Fdemo%2Fdemo_svg-favicon-sizes.png)

## Тестовый вариант с SVG-иконкой

Пробуем этот вариант, если не заводится — основной:

1. Кладём папку `svg-favicon` так, чтобы её содержимое было доступно в корне сайта
2. Вставляем этот код в `<head>` страниц:

```html
<link rel="apple-touch-icon" sizes="180x180" href="/apple-touch-icon.png">
<link rel="icon" type="image/svg+xml" href="/favicon.svg">
<link rel="icon" href="/favicon.ico" sizes="any">
<link rel="manifest" href="/site.webmanifest">
<link rel="mask-icon" href="/safari-pinned-tab.svg" color="#5bbad5">
```

Профиты этого метода:
- Иконка меняется в зависимости от темы
- Тестовые файлы весят меньше в полтора раза

![demo_svg-favicon.png](..%2Fdemo%2Fdemo_svg-favicon.png)

Если не получилось, подключаем классику из генератора (ниже). Или напишите мне, если есть желание разобраться 🙂

## Основной вариант

Инструкция [отсюда](https://realfavicongenerator.net/):

1. Extract package `default-favicon` in the root of your web site. If your site is http://www.example.com, you should be able to access a file named http://www.example.com/favicon.ico.
2. Insert the following code in the <head> section of your pages:

```html
<link rel="apple-touch-icon" sizes="180x180" href="/apple-touch-icon.png">
<link rel="icon" type="image/png" sizes="32x32" href="/favicon-32x32.png">
<link rel="icon" type="image/png" sizes="16x16" href="/favicon-16x16.png">
<link rel="manifest" href="/site.webmanifest">
<link rel="mask-icon" href="/safari-pinned-tab.svg" color="#5bbad5">
<meta name="msapplication-TileColor" content="#da532c">
<meta name="theme-color" content="#ffffff">
```

# Open Graph теги

Обновляем только картинку. Новая `og.png`, имеет тот же размер, что и старая (лежит по адресу https://cdn1.tu-tu.ru/images2/logo/og_2018.png)

Для того, чтобы превью обновилось в телеграме, используй бота [@webpagebot](https://telegram.me/webpagebot)