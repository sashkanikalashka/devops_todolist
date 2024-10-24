# ToDo App

Це Docker-залежний ToDo додаток, створений на базі Django.

## Docker Image

Docker-образ доступний за адресою: [nikalasha/todoapp](https://hub.docker.com/r/nikalasha/todoapp)
# у терміналі введіть та скачайте образ
docker pull nikalasha/todoapp:1.0.0

# та запустіть його
docker run -d -p 8080:8080 todoapp:1.0.0

# отримайте доступ до додатку у браузері за адресою
http://localhost:8080
