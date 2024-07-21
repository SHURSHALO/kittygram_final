# Kittygram

Это веб-приложение, позволяющее пользователям зарегистрироваться и делиться фотографиями своих любимых котов.

### Клонируйте репозиторий:
git clone git@github.com:SHURSHALO/kittygram_final.git

### Установите Docker и Docker Compose:
Убедитесь, что на вашем компьютере установлены Docker и Docker Compose. 
Если их у вас нет, вы можете скачать и установить их с https://www.docker.com/get-started/

### Соберите Docker-образы:
Запустите команду для сборки Docker-образов вашего проекта, предполагая, что ваш файл docker-compose.yml находится в корневой директории проекта:

docker compose up -d

Затем в выполните миграции в той же директории проекта

docker compose exec backend python manage.py migrate


### Ваши сервисы будут доступны по адресу http://localhost:9000

