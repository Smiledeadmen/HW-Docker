Перейти в каталог 2-task. 
Собираем образ:
```bash
docker build -t django-crud:1 .
```
Запускаем контейнер с Django:
```bash
docker run -it --name dj-crud -p 8000:8000 django-crud:1
```
Проверяем:
```bash
curl localhost:8000/api/v1/
```