# Домашнее задание к занятию "`«Что такое DevOps. СI/СD»`" - `Османов Ренат`

---

### Задание 1

1. Установите себе jenkins, следуя инструкции из лекции (или любым другим способом из официальной документации). Использовать docker в данном задании нежелательно.
2. Установите на машину с jenkins [golang](https://golang.org/doc/install).
3. Используя свой аккаунт на GitHub, сделайте себе форк [репозитория](https://github.com/netology-code/sdvps-materials.git). В этом же репозитории находится [дополнительный материал для выполнения ДЗ](https://github.com/netology-code/sdvps-materials/blob/main/CICD/8.2-hw.md).
3. Создайте в дженкинсе freestyle проект, подключите получившийся репозиторий к нему и произведите запуск тестов и сборку проекта ```go test .``` и  ```docker build .```
*В качестве ответа пришлите скриншоты с настройками проекта и результатами выполнения сборки*

### Ответ

Описание:
![Описание](https://github.com/racnuzg9u/cicd-hw/blob/main/img/1.1.png)
![Описание](https://github.com/racnuzg9u/cicd-hw/blob/main/img/1.2.png)
![Описание](https://github.com/racnuzg9u/cicd-hw/blob/main/img/1.3.png)



---

### Задание 2

1. Создайте новый проект pipeline.
2. Перепишите сборку из задания 1 на declarative(в виде кода).
*В качестве ответа пришлите скриншоты с настройками проекта и результатами выполнения сборки*

### Ответ
Описание:
![Описание](https://github.com/racnuzg9u/cicd-hw/blob/main/img/2.1.png)
![Описание](https://github.com/racnuzg9u/cicd-hw/blob/main/img/2.2.png)
---

### Задание 3

1. Установите на машину Nexus.
1. Создайте raw-hosted репозиторий.
1. Измените пайплайн таким образом, чтобы вместо docker-образа собирался бинарный go-файл (команду можно скопировать из Dockerfile).
1. Загрузите файл в репозиторий с помощью jenkins
*В качестве ответа пришлите скриншоты с настройками проекта и результатами выполнения сборки*

### Ответ

Описание:
![Описание](https://github.com/racnuzg9u/cicd-hw/blob/main/img/3.1.png)
![Описание](https://github.com/racnuzg9u/cicd-hw/blob/main/img/3.2.png)
![Описание](https://github.com/racnuzg9u/cicd-hw/blob/main/img/3.3.png)