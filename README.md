## Отличия между командами git pull и git fetch

Команда `git fetch` получает изменения с сервера и сохраняет их в каталог `refs/remotes/`. Это действие (fetch) не влияет на локальные ветки и текущие изменения, просто изменения с удаленного сервера скачиваются в директорию локального репозитария.

> Локальный репозитарий - это структурированное хранилище изменений проекта. В нем хранятся копии изменений, которые получены с удаленного сервера, или производились локально и были закоммичены.

![Схема](https://raw.github.com/xintrea/mytetra_syncro/master/base/14357584259soun9chuj/image1548152635tqvctg3eeo.png)

А что же делает команда `git merge`? Она вливает (применяет) все полученные новые изменения к текущей ветке, в которой происходит работа.

`git pull` — это, по сути, команда `git fetch`, после которой сразу же следует `git merge`.

![Схема](https://raw.github.com/xintrea/mytetra_syncro/master/base/14357584259soun9chuj/image1548152747dpzmnyxma8.png)

**Источники информации:**

- Это [ссыль](https://texterra.ru/blog/ischerpyvayushchaya-shpargalka-po-sintaksisu-razmetki-markdown-na-zametku-avtoram-veb-razrabotchikam.html?ysclid=l9a8jnmpof627443430 "Агентство TexTerra") на полезный сайт по разметке.

- Это [ссыль](https://webhamster.ru/mytetrashare/index/mtb0/143575842521lohpnj4q "В чем разница между Fetch и Pull") про отличия от методов

![Прикольная картинка](https://miro.medium.com/max/720/0*NyhBptaCdlTqAMnn.png)
