# NGINX, PHP8, POSTGRES, COMPOSER 2 IN DOCKER

Создать конфиг
```bash
cp .env.example .env
```

Собрать
```bash
docker-compose build app
```

Запустить
```bash
docker-compose up -d
```

Пример выполнения команды в контейнере
```bash
docker-compose exec app composer -V
```

Остановить

```bash
docker-compose down
```
