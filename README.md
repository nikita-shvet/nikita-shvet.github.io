# Сайт-визитка Никиты Швецова

Статический сайт на чистом HTML/CSS без внешних зависимостей. Хостинг: GitHub Pages (бесплатно).

```
index.html                      главная: резюме, исследования, продукты, инструменты, контакты
cases/ai-onboarding.html        кейс: AI-ассистент онбординга
cases/personas.html             кейс: 5 профилей ЦА из 18 интервью
cases/subscription-platform.html кейс: подписная платформа HackTheArchitecture
assets/style.css                все стили (светлая и тёмная тема)
assets/photo.jpg                фото
assets/og.jpg                   картинка-превью для Telegram и соцсетей
assets/favicon.svg              иконка вкладки
assets/Nikita_Shvetsov_Product_Manager_CV.pdf  резюме для скачивания
```

## Перед публикацией

1. **Заполните жёлтые блоки «✎ Дополнить»** на страницах кейсов. Найти их: поиск `class="todo` в папке `cases`. Когда заполните блок, удалите весь тег `<span class="todo">…</span>`.
2. **Исправьте PDF-резюме**: в разделе «О себе» указано «LTV +32%», а в опыте — «с 21 до 90 дней». Сайт отдаёт этот PDF на скачивание, поэтому цифры должны совпадать. Новый PDF положите в `assets/` под тем же именем.
3. Если ваш логин на GitHub будет не `nikita-shvetsov`, замените во всех файлах `nikita-shvetsov.github.io` на `ВАШ-ЛОГИН.github.io` (используется в превью для Telegram).

## Публикация на GitHub Pages (≈10 минут)

1. Зарегистрируйтесь на [github.com](https://github.com/signup). Логин станет адресом сайта, поэтому лучше выбрать `nikita-shvetsov`.
2. Нажмите **+ → New repository**. В поле **Repository name** введите ровно `nikita-shvetsov.github.io` (ваш логин + `.github.io`). Выберите **Public** и нажмите **Create repository**.
3. На странице репозитория нажмите **uploading an existing file**. Перетащите **содержимое** папки `site` — файл `index.html` и папки `assets` и `cases`, а не саму папку `site`. Нажмите **Commit changes**.
4. Откройте **Settings → Pages**. В блоке **Build and deployment** выберите **Source: Deploy from a branch**, затем **Branch: main** и папку **/ (root)**. Нажмите **Save**.
5. Через 1–2 минуты сайт откроется по адресу `https://nikita-shvetsov.github.io`.

## Проверка после публикации

- Откройте сайт с телефона через мобильный интернет **без VPN**.
- Отправьте ссылку себе в Telegram и проверьте превью с фото. Если превью не появилось, отправьте ссылку боту @WebpageBot: он обновляет кэш превью.
- Нажмите все кнопки: Telegram, почта, скачивание PDF и ссылки на кейсы.

## Шаг 6 (по желанию): аналитика

1. Создайте бесплатный счётчик на [metrika.yandex.ru](https://metrika.yandex.ru), указав адрес сайта.
2. Скопируйте код счётчика и вставьте его в `<head>` каждой HTML-страницы, на место комментария `<!-- Яндекс.Метрика … -->` (в кейсах вставьте перед `</head>`).
3. Так вы увидите, открывают ли сайт после ваших откликов и до каких разделов дочитывают.

## Как обновлять

Откройте нужный файл в репозитории на github.com, нажмите на карандаш (**Edit**), внесите правки и нажмите **Commit changes**. Через минуту изменения появятся на сайте.

## Свой домен (позже)

Купите домен (например, `shvetsov.ru`) у любого регистратора. В **Settings → Pages → Custom domain** впишите его и настройте DNS по [инструкции GitHub](https://docs.github.com/ru/pages/configuring-a-custom-domain-for-your-github-pages-site). После этого замените адрес в мета-тегах `og:url`, `og:image` и `canonical`.
