---
title: Docker detached mode
localeTitle: Режим снятия докеров
---
## Режим снятия докеров

Отдельный режим, показанный опцией `--detach` или `-d` , означает, что контейнер Docker работает на заднем плане вашего терминала. Он не получает входной или выходной дисплей.
```
docker run -d IMAGE 
```

Если вы запускаете контейнеры в фоновом режиме, вы можете узнать их данные с помощью `docker ps` а затем снова подключить ваш терминал к его вводу и выводу.

#### Дополнительная информация:

*   [Прикрепите и отсоедините от работающего контейнера | Докеры](https://docs.docker.com/engine/reference/commandline/attach/#examples)
*   [Частный и передний план | Докеры](https://docs.docker.com/engine/reference/run/#detached-vs-foreground)