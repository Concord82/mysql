# Docker MySQL Server + phpmyadmin

состоит из двух контейнеров с mariadb и phpmyadmin

Порты:
- 3306 - mysql Server
- 8080 - phpmyadmin

### Старт контейнера в режиме демона

    docker compose up -d

### Останов контейнера 

    docker compose down

### phpmyadmin
В поле имя сервера указываем имя контейнера с сервером базы данных. 

Сейчас указываем db. При необходимости сменить имя в docker-compose.yml в строке 

    container_name: db

### Файлы базы данных 

В директории склонированного репозитория создать каталог mariadb

    mkdir mariadb

При необходимости настроить бэкап файлов. 