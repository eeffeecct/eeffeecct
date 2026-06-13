# Hi there, I'm Timofey 👋

### 🚀 Java Backend Developer | Student at MSTU STANKIN

Студент кафедры прикладной информатики. Строю production-сервисы на Java/Spring — от платёжных интеграций до микросервисной архитектуры.

---

### 🛠 Tech Stack

**Core & Frameworks**
![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white)
![Spring](https://img.shields.io/badge/spring-%236DB33F.svg?style=for-the-badge&logo=spring&logoColor=white)
![Spring Boot](https://img.shields.io/badge/spring_boot-%236DB33F.svg?style=for-the-badge&logo=springboot&logoColor=white)
![Spring Security](https://img.shields.io/badge/Spring%20Security-6DB33F?style=for-the-badge&logo=springsecurity&logoColor=white)
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=white)

**Data & Messaging**
![Postgres](https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/redis-%23DD0031.svg?style=for-the-badge&logo=redis&logoColor=white)
![MinIO](https://img.shields.io/badge/MinIO-C72E49?style=for-the-badge&logo=minio&logoColor=white)
![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?style=for-the-badge&logo=rabbitmq&logoColor=white)
![Liquibase](https://img.shields.io/badge/Liquibase-2962FF?style=for-the-badge&logo=liquibase&logoColor=white)
![pgvector](https://img.shields.io/badge/pgvector-316192?style=for-the-badge&logo=postgresql&logoColor=white)

**DevOps & Tools**
![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white)
![Caddy](https://img.shields.io/badge/Caddy-1F88C0?style=for-the-badge&logo=caddy&logoColor=white)
![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)
![Maven](https://img.shields.io/badge/Maven-C71A36?style=for-the-badge&logo=apachemaven&logoColor=white)
![Gradle](https://img.shields.io/badge/Gradle-02303A.svg?style=for-the-badge&logo=Gradle&logoColor=white)

---

### 🔭 Projects

#### **Orchestra VPN — Коммерческий VPN-сервис**
Telegram-бот для продажи VPN-подписок. Полный цикл: оплата → выдача ключа → фискализация — без ручных действий.
* **Стек:** Spring Boot 3, PostgreSQL, WebClient, Telegram Bot API, YooKassa API, Marzban API, API «Мой налог».
* **Инфраструктура:** 4 VPN-ноды (NL/DE/UK/US), Caddy reverse proxy + auto-TLS, CI/CD (GitHub Actions → GHCR → SSH deploy), Uptime Kuma мониторинг.
* **Безопасность:** Ре-верификация webhook через API, идемпотентная обработка платежей, optimistic locking.

#### **ArtVizor — AI-сервис анализа изображений**
Микросервисный backend: по загруженной картине определяет художественный стиль, палитру из 5 цветов и находит 6 похожих работ.
* **Стек:** Spring Boot, Spring Security (JWT), PostgreSQL + pgvector, RabbitMQ, MinIO (S3), Python (ML-воркер), Docker Compose.
* **Архитектура:** REST API + ML-воркер с асинхронным взаимодействием через RabbitMQ; векторный поиск похожих на pgvector (cosine + HNSW) по базе 56k картин; изображения в MinIO через presigned URL.
* **ML & Деплой:** классификатор стиля CLIP + MLP (75% Top-1 / 95% Top-3, 27 стилей); CI/CD (GitHub Actions → GHCR → SSH-деплой на VPS).
  
#### **UITS Portal — Портал кафедры университета**
Бэкенд для внутреннего портала кафедры УИТС.
* **Стек:** Spring Boot 4, Spring Security, PostgreSQL, Liquibase, JWT, MapStruct.
* **Функционал:** JWT-аутентификация, ролевая авторизация (Admin, Moderator, Teacher), модули новостей и преподавателей.
* **Качество:** Интеграционные тесты (Testcontainers + TestRestTemplate), CI/CD (GitHub Actions).

---

### 📫 Connect

* [Telegram](https://t.me/eeffeecct)
* [Email](mailto:timter32@gmail.com)
