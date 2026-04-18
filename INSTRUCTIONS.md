1) Для запуска проекта необходимо сначала запустить Docker Compose:
```shell
docker compose up --build
```

2) После этого Вам необходимо зайти в DBeaver и подключиться к базе данных, для этого нажмите на New Database Connection
3) Выбрать PostgreSQL
4) В Connection settings в Main настраиваем в соответствии с docker-compose.yml:
        Authentication: Username/password
        Database: lab1db
        Username: lab1db_owner
        Password: lab1db_password
5) Нажать Finish
6) После подключения зайти lab1db -> Databases -> lab1db -> Schemas -> public -> Tables
