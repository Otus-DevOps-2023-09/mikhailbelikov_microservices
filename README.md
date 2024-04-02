# mikhailbelikov_microservices
mikhailbelikov microservices repository

## Docker контейнеры. Docker под капотом.

### Основное задание:
Установлен Docker
Создание docker host
Создание своего образа
Загрузка своего образа на Docker Hub

## Docker образы. Микросервисы.

### Основное задание:
Добавлены микросервисы
Созданы Dockerfile's для микросервисов
Созданы образы
Создали bridge-сеть для контейнеров
Запустили наши контейнеры в этой сети

## Сетевое взаимодействие Docker контейнеров. Docker Compose. Тестирование образов.

### Основное задание:
Работа с сетями в Docker
Использование docker-compose
Установлен docker-compose на локальную машину
Собраны образы приложения reddit с помощью docker-compose
Запущено приложение reddit с помощью dockercompose

## Устройство Gitlab CI. Построение процесса непрерывной интеграции  

### Основное задание:  
В Yandex Cloud разврнута ВМ gitlab-ci-vm с публичным адресом 51.250.8.148
Выполнена установка Docker и Docker Compose на ВМ
Развернут Gitlab на поднятой ВМ
Создан проект в Gitlab  
Подключен удаленный репозиторий GitLab 
Протестированы пайплайны в gitlab-ci

## Введение в мониторинг. Модели и принципы работы систем мониторинга  

### Основное задание: 
Создана ВМ в YC
Инициализировано окружение в Docker
Запущен Prometheus
Создан образ Prometheus
Выполнена установка Prometheus через Docker Compose
Запушены образы в DockerHub
https://hub.docker.com/repository/docker/mikhailbelikov/prometheus/general
https://hub.docker.com/repository/docker/mikhailbelikov/post/general
https://hub.docker.com/repository/docker/mikhailbelikov/comment/general
https://hub.docker.com/repository/docker/mikhailbelikov/ui/general

## Введение в Kubernetes #1   

### Основное задание:  
Создан файл post-deployment.yml в директории kubernetes/reddit
Установлен k8s на двух нодах
Проверены манифесты
Успешный запуск подов

## Применение системы логирования в инфраструктуре на основе Docker     

### Основное задание: 
Создана ВМ в YC
На ВМ выполнена установка Docker
Соазданы Dockerfile's для логировани и fluentd
Создан конфиг для fluentd  
Инициализирован образ fluentd
Выполнен запуск контейнеров
Логи направлены в fluentd
Изучен kibana
Добавлены фильтры и grok-шаблоны
Изучен zipkin
Запущены контейнеры ситемы логирования  
Настроена отправка логов в fluentd  
Изучен инструмент визуализации логов kibana  
Добавлены фильтры  
Добавлены grok-шаблоны  
Запущен и изучен сервис трейсинга zipkin  
Изучена визуализация логов и сбор структурированных логов

## Основные модели безопасности и контроллеры в Kubernetes

### Основное задание:
Локально развернуто окржение для работы с Kubernetes
Для minikube использован Virtualbox
Развернут Kubernetes в Yandex Cloud
Запущен reddit в Kubernetes, скриншот в PR.

