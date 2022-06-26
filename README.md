# JDG (Jednoosobowa działalność gospodarcza)  — ИП в Польше

[Перейти на сайт](https://sobolevbel.github.io/jdg/)

Для сборки сайта из `markdown` файлов используется генератор статических сайтов [MkDocs](https://www.mkdocs.org/).
С синтаксисом markdown можно ознакомиться [здесь](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax).

## Как поучаствовать в проекте

1. Форкните проект, создайте новую ветку и начинайте работу.
2. Когда работа будет готова — проверьте локально что сайт собирается и запушьте ветку в репозиторий.
3. Создайте Pull Request в master.

## Процесс работы

### Нормальный способ
Для локальной сборки сайта необходимо установить:

- python 3+
- mkdocs

Для установки зависимостей проекта используйте команду `pip install -r requirements.txt`

Запустить проект:

`mkdocs serve`

### Docker-way 🙃

Нужны:
- docker
- docker-compose

А дальше запускаете:

`docker-compose up --build`

### Obsidian
Или можете просто установить Obsidian и в нём редактировать и сразу видеть отрендеренный Markdown.

```
  ,-.       _,---._ __  / \
 /  )    .-'       `./ /   \
(  (   ,'            `/    /|
 \  `-"             \'\   / |
  `.              ,  \ \ /  |
   /`.          ,'-`----Y   |
  (            ;        |   '
  |  ,-.    ,-'         |  /
  |  | (   |            | /
  )  |  \  `.___________|/
  `--'   `--'
```
