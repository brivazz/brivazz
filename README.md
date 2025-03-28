# 📂 Portfolio

## 🔐 Аутентификация и уведомления
- Микросервисы авторизации (OAuth2.0) и системы уведомлений (Email, Web-push) с брокером сообщений RabbitMQ.
  - [Подробнее](https://github.com/brivazz/Auth/tree/main/auth_api)
  - [Система уведомлений](https://github.com/brivazz/notifications/tree/main/components)

## 🔍 Поисковые системы и ETL
- Полнотекстовый поиск на Elasticsearch с обработкой 500+ запросов/сек.
  - [Подробнее](https://github.com/brivazz/Async_API/tree/main/async_api/src/db/elastic)
- ETL-пайплайны для миграции данных между Kafka, Clickhouse и PostgreSQL.
  - [Пример 1](https://github.com/brivazz/ugc_sprint_1/tree/main/kafka_to_clickhouse/src/etl)
  - [Пример 2](https://github.com/brivazz/new_admin_panel_sprint_3/tree/main/etl/postgres_to_es)

## 🚀 Backend-разработка
- Бизнес-логика для высоконагруженных приложений на FastAPI.
  - [Подробнее](https://github.com/brivazz/Async_API/tree/main/async_api/src)
- RESTful API на Django для управления данными.
  - [Подробнее](https://github.com/brivazz/new_admin_panel_sprint_2/blob/main/django_api/app/movies/api/v1/views.py)

## 📊 Распределенные системы и базы данных
- Система хранения данных (Kafka + Clickhouse + MongoDB) для обработки 1M+ событий/день.
  - [Подробнее](https://github.com/brivazz/ugc_sprint_1/tree/main)
- Оптимизация схем реляционных БД.
  - [Подробнее](https://github.com/brivazz/new_admin_panel_sprint_1/blob/main/schema_design/movies_database.ddl)

## 🛠 DevOps & CI/CD
- Автоматизация развертывания сервисов с Docker и Nginx.
  - [Docker Compose](https://github.com/brivazz/ugc_sprint_2/blob/main/docker-compose.yml)
  - [Nginx Configs](https://github.com/brivazz/ugc_sprint_2/tree/main/nginx)
- Настройка CI/CD (GitHub Actions).
  - [CI/CD Pipeline](https://github.com/brivazz/ugc_sprint_2/blob/main/.github/workflows/code-checker.yml)
