# newtestament-site

Лендинг-страница приложения **«Новый Завет»** (Android) + хранилище релизов.

## Структура

- `index.html` — главная страница (адаптировано из psaltir-site, требует
  финального копирайтинга)
- `privacy.html` — политика конфиденциальности (RU + EN)
- `icon.png` — иконка приложения для favicon и meta-images
- `screenshots/` — скриншоты для лендинга

## Релизы

Production APK и AAB публикуются как
[GitHub Releases](https://github.com/kostya29/newtestament-site/releases) этого
репозитория. Тут же хранится `bibble_seed.db.zip` как асет — его GitHub-лимит на
файлы в репе (100 MB) превышает, а в releases — ок.

## Хостинг

Лендинг можно опубликовать через GitHub Pages: Settings → Pages → branch `main` /
root → Save. После прохождения CI страница будет на
`https://kostya29.github.io/newtestament-site/`.
