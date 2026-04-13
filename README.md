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

**Data & Messaging**
![Postgres](https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/redis-%23DD0031.svg?style=for-the-badge&logo=redis&logoColor=white)
![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?style=for-the-badge&logo=rabbitmq&logoColor=white)
![Liquibase](https://img.shields.io/badge/Liquibase-2962FF?style=for-the-badge&logo=liquibase&logoColor=white)

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

#### **UITS Portal — Портал кафедры университета**
Бэкенд для внутреннего портала кафедры УИТС.
* **Стек:** Spring Boot 4, Spring Security, PostgreSQL, Liquibase, JWT, MapStruct.
* **Функционал:** JWT-аутентификация, ролевая авторизация (Admin, Moderator, Teacher), модули новостей и преподавателей.
* **Качество:** Интеграционные тесты (Testcontainers + TestRestTemplate), CI/CD (GitHub Actions).

#### **Nexus Commerce — Микросервисная e-commerce платформа**
Бэкенд из независимых сервисов с event-driven взаимодействием.
* **Стек:** Spring Boot 3, PostgreSQL, MongoDB, Redis, RabbitMQ, Docker Compose.
* **Сервисы:** Product (MongoDB + Redis-кэш + optimistic locking), Inventory (PostgreSQL + JDBC Template), Notification.
* **Тесты:** Testcontainers (MongoDB, Redis, PostgreSQL), MockMvc.

---

### 📫 Connect

* [Telegram](https://t.me/eeffeecct)
* [Email](mailto:timter32@gmail.com)
