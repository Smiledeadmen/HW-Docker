Перейти в каталог 1-task. 
Запустить комманду:
```bash
docker run --name=test_nginx -p 7000:80 -d -v /$(PWD)/1-task/my_html:/usr/share/nginx/html nginx
```
Проверяем:
```bash
curl localhost:7000
```
