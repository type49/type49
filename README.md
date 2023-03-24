###  Features
- Разработка программ на Python для автоматизации бизнес-процессов
- Создание пользовательских интерфейсов с использованием PyQT
- Улучшение и оптимизация существующего кода


------------


#### Стажер-программист, 49 Inc. (2018 - 2023)
- Написание кода на Python для малых проектов
- Создание десктопных приложений

------------


### Skills
Языки программирования: Python, HTML, CSS

Библиотеки и фреймворки: PyQT, Django, aiogram

Инструменты: Git, PyCharm, SQL

Дизайн: Photoshop 

------------


### Education
Техник-программист, ЦАТЭК (2014-2016)

------------
### Проекты
- [Программа](https://github.com/type49/spiritape "Программа") для работы с заметками с расширенным функционалом. 
- [Библиотека](https://github.com/type49/youtube-search-with-api "Библиотека") для расширенного поиска YouTube с обходом его ограничений в количестве выдаваемых данных.

------------


### Контакты
Email: underalmaty@gmail.com

GitHub: https://github.com/type49

Telegram: @undermaty


- uses: Platane/type49
  with:
    # github user name to read the contribution graph from (**required**)
    # using action context var `github.repository_owner` or specified user
    github_user_name: ${{ github.repository_owner }}

    # list of files to generate.
    # one file per line. Each output can be customized with options as query string.
    #
    #  supported options:
    #  - palette:     A preset of color, one of [github, github-dark, github-light]
    #  - color_snake: Color of the snake
    #  - color_dots:  Coma separated list of dots color.
    #                 The first one is 0 contribution, then it goes from the low contribution to the highest.
    #                 Exactly 5 colors are expected.
    outputs: |
      dist/github-snake.svg
      dist/github-snake-dark.svg?palette=github-dark
      dist/ocean.gif?color_snake=orange&color_dots=#bfd6f6,#8dbdff,#64a1f4,#4b91f1,#3c7dd9
