# Automated Systems Support Engineer

Этот репозиторий содержит домашние задания и практические работы, выполненные в рамках курса по подготовке инженеров поддержки автоматизированных систем. Работы охватывают такие темы, как Linux, сети, Docker, Jenkins, Kubernetes, мониторинг и Kafka.

## 🖥️ Содержание

### 📁 Linux

- Развертывание CentOS Stream на VirtualBox
- Работа с пользователями, SSH, файловой системой
- Регулярные выражения и grep
- Bash-скрипт для генерации директории по годам/месяцам/датам
- Настройка cron-задач
- Работа с сигналами процессов (`kill`, `PID`)
- Диагностика системы (CPU, RAM, диск, сеть) под нагрузкой

### 🌐 Networks

- Теория OSI, работа с MAC/IP
- Конфигурация сетей в Cisco Packet Tracer
- Классификация IP-адресов
- Маскирование и расчет сети/broadcast/хостов
- Анализ трафика с помощью Wireshark
- Работа с API Яндекс.Погоды (curl, JSON)

### 🐳 Docker

- Запуск контейнеров: `nginx` (front) и собственного приложения (back)
- Использование `Dockerfile` и `--build-arg`
- Сетевое взаимодействие контейнеров
- Конфигурация `default.conf` для nginx
- Итог: доступ к приложению по адресу `http://localhost:8080` с ответом "Hello, Sber!"

### 🔧 Jenkins

- Установка Jenkins, запуск простого `job`
- Подключение агента
- Создание pipeline со сборкой из Git
- Плагины Jenkins
- CI/CD: выгоды, назначение
- Ansible-плейбук

### ☸ Kubernetes

- Установка Kubernetes и сетевого плагина
- Установка Istio, Kiali
- Разворачивание PostgreSQL, Drupal, yaml-файлов через Jenkins
- Дебаг yaml, namespace quota
- Пояснения: ресурсы vs лимиты

### 📊 Monitoring

- Установка и настройка FluentD
- Установка Zabbix, агента
- Настройка Prometheus + Node Exporter
- Интеграция с Grafana и создание дашбордов (CPU, RAM, Network)
- Описание прикладных метрик
- Сравнение Pull vs Push моделей сбора логов и метрик

### 📡 Kafka

- Установка и запуск Apache Kafka
- Создание топиков
- Чтение и запись сообщений через `kafka-console-producer` и `consumer`

## 📎 Структура репозитория
```text
linux/         - Задания по Linux
networks/      - Задания по сетям (Pocket Tracer, IP, Wireshark и др.)
docker/        - Работа с Docker: nginx + custom app
jenkins/       - Установка Jenkins, pipeline, CI/CD
kubernetes/    - Задания по Kubernetes и Istio
monitoring/    - FluentD, Prometheus, Grafana, Zabbix
kafka/         - Kafka: топики, producer/consumer
README.md      - Этот файл
```

## 📌 Требования

- VirtualBox
- Docker & Docker Compose
- Jenkins
- Minikube или другой Kubernetes кластер
- Kafka & Zookeeper
- Grafana, Prometheus
- FluentD, Zabbix

## ⚙️ Установка и запуск

> Инструкции по установке и запуску каждого компонента можно найти в соответствующих подкаталогах.

## 🧾 Автор

Разработано студентом в рамках курса подготовки инженеров поддержки автоматизированных систем.

---



