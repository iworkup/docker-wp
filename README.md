# Docker WP

Минимальный Docker-шаблон быстрого разворачивания WordPress для разработки тем или плагинов. 

## Образы (images)

- `mysql`
- `wordpress`
- `phpmyadmin`

## Конейнеры (containers)

- `db`
- `wordpress`
- `phpmyadmin`

## Переменные окружения

Переменные указаны в файле `.env`.

`WP_VERSION` - версия WordPress. Пример: `5.9.0-php8.0`

`WP_FILES_LOCAL` - путь к локальному каталогу для установки WordPress. Пример: `./dev/html`

`WP_FILES_CONTAINER` - путь к каталогу для установки WordPress в контейнере. Пример: `/var/www/html`

`DEV_FOLDER_NAME` - название каталога с разрабатываемым компонентом WordPress. Пример: `my-theme`

`DEV_FILES_LOCAL` - путь к локальному каталогу, где лежит каталог с рарабатываемым компонентом WordPress. Пример: `./dev/`

`DEV_FILES_CONTAINER` - путь к каталогу в контейнере, где лежит каталог с рарабатываемым компонентом WordPress. Пример: `/var/www/html/wp-content/themes/`

`MYSQL_VERSION` - Версия MySQL. Пример: `8.0.0`

`MYSQL_FILES_LOCAL` - путь к локальному каталогу с модулем MySQL. Пример: `./dev/mysql`

`MYSQL_FILES_CONTAINER` - путь к каталогу в контейнере с модулем MySQL. Пример: `/var/lib/mysql`

`MYSQL_DB_HOST` - имя хоста базы данных. Должно совпадать с названием сервиса базы данных Пример: `db`

`MYSQL_DB_NAME` - имя базы данных. Пример: `wpdb`

`MYSQL_DB_USER` - имя пользователя базы данных. Пример: `igor`

`MYSQL_DB_PASSWORD` - пароль базы данных. Пример: `password`

`MYSQL_DB_ROOT_PASSWORD` - рут пароль базы данных. Пример: `rootpswd`
