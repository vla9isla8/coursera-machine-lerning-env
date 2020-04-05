# Докер образ для поднятия Jupiter и прохождения курса

Образ создан на основе jupyter/scipy-notebook

### Запуск контейнера

```
docker run -p 10000:8888 docker.pkg.github.com/vla9isla8/coursera-machine-lerning-env/jupiter:latest
```

### Старт через docker-compose

Скачайте docker-compose.yml
Укажите локальную деррикторию для хранения блокнотов в services.jupiter.volumes
Далее запускаем наш контейнер:
```
docker-compose up -d
```