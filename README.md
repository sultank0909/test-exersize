# test-exersize
Тестовое задание для вакансии DevOps
Для начала я создал Dockerfile(который я приложил), с помощью которого я создал простой образ Java.
Далее я его запушил на DockerHub https://hub.docker.com/repository/docker/sultank0909/jdk/general
Уже в файле sultan.yaml указал название образа, при помощи которого поднимается контейнер и он становится доступен на IP адресе http://34.71.57.198/
Я решил немного модернизировать ваше задание и поднял свой кластер из трех Nodes в Google Cloud Platform.
Прилагаю файл sultan.yaml, который описывает всю структуру по вашему заданию.
В этом файле создается Deployment, далее HPA(autoscaling), который при определенной повышенной нагрузке СРU и RAM начинает создавать дополнительные реплики Pods c 2 до 6 штук. При уменьшении нагрузки НРА начинает снижать кол-во Pods до изначального кол-ва - 2 штук. 


P.S. Постарался расписать максимально кратко и понятно. Надеюсь у вас появятся вопросы и мы с вами побеседуем более детально.
Мои контакты: 
tg - sultank0909
Email - Kubanychbekuulusultan@gmail.com
