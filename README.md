## Kittygram: 
Проект представляет собой социальную сеть для обмена фотографиями ваших кисок. 
Каждой киске можно дать имя, указать год раждения, цвет и достижения которыми вы особо гордитесь. 
 
## Как запустить: 
1. Сделайте fork депозитория kittygram_final 

2. Создайте файл .env и заполните его своими данными:

```nano
POSTGRES_DB=kittygram
POSTGRES_USER=kittygram_user
POSTGRES_PASSWORD=kittygram_password
DB_HOST=db
DB_PORT=5432
SECRET_KEY=...
DEBUG=... # True/False
ALLOWED_HOSTS=127.0.0.1,localhost
```
 
3. Устанавливаем к Docker утилиту Docker Compose:
```bash
sudo apt update
sudo apt-get install docker-compose-plugin 
```
 
4. В директорию проекта копируем файл `docker-compose.production.yml` и запускаем Docker Compose:
```bash
sudo docker-compose up
```
Проект запущен и доступен по адресу [127.0.0.1:8000](http://127.0.0.1:8000/).


## Технологии: 
 
Backend 
* Django
* Python
* djangorestframework 
* Djoiser 
* Docker
* PostgreSQL
 
Frontend 
* JavaScript 
* React 
 
WSGI сервер 
* Gunicorn 
 
WEB сервер 
* NGINX 
 
## Автор: 
Текутьев Александр 
`https://github.com/Tekut`