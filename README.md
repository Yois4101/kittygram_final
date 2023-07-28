# [Kittygram](https://yois-cat.ddns.net)

![workflow](https://github.com/Yois4101/kittygram_final/actions/workflows/main.yml/badge.svg)

Наш *Kittygram* позволяет вам размещать фотографии своих любимых котов - серых, рыжих, пушитых и вовсе лысых!

И не только фотографии, но и отмечать их достижения - "поймал мышку", "убежал от собаки" или просто "весь день мурлыкал"!

## Вы также можете , используя наш код, запустить свой сайт

Для этого нужно выполнить несколько простых шагов:

- установить на сервер [docker](https://www.docker.com/)
- скопировать на сервер файл `docker-compose.production.yml`
- изменить в нём  строку `- 9000:80` на `- 80:80`
- запустить сайт командой `docker compose up`

Сайт будет доступен по адресу `http://<ваш IP>/`

## Построено на технологиях

- Python 3.9
- Django 3.2
- DjangoRestFrameWork 3.12
- React
- Docker

## Авторы

- [Yois4101](https://github.com/Yois4101)
- [dcuba](https://github.com/dcuba)
