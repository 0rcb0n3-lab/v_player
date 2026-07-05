# v-player

Видеоплеер на основе библиотеки Playable.


## Скриншот
<img width="829" height="698" alt="image" src="https://github.com/user-attachments/assets/81febe9a-c67c-4487-aeb6-a6c71acbb537" />



Видеплеер можно посмотреть по ссылке:  

[https://0rcb0n3-lab.github.io/v_player/](https://0rcb0n3-lab.github.io/v_player/)

## Возможности

- Воспроизведение и пауза видео
- Включение/выключение звука
- Полноэкранный режим
- Адаптация под размер окна
- Кнопки с иконками Font Awesome
- Тень вокруг плеера

## Перед запуском

**Проверить версию Python:**

```bash
python --version
```

- Должна быть версия 3.10 или выше.

- Склонируйте репозиторий
- Откройте файл `index.html.`

```
Структура проекта

v-player/
├── index.html        # Главная страница
├── player.js         # Скрипт плеера (библиотека Playable)
└── static/
    └── favicon.svg   # Иконка сайта
```

Что использовалось:   

[Font Awesome 4.7.0](https://fontawesome.com/v4/get-started/) — иконки для кнопок

## Разработка

Для локальной разработки используется livereload для автоматического обновления страницы при изменении файлов:

```bash
livereload player
```

## Цель проекта

Код написан в образовательных целях на курсе [dvmn.org](https://dvmn.org/) по веб-разработке.
