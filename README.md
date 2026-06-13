<h1 align="center">Hi there, I'm Timofey 👋</h1>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=24&pause=1000&color=6DB33F&center=true&width=520&lines=Java+Backend+Developer;Spring+Boot+%7C+Microservices;Building+production-ready+services" alt="typing" />
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=eeffeecct&style=for-the-badge&color=6DB33F&label=Profile+views" alt="views" />
</p>

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
![pgvector](https://img.shields.io/badge/pgvector-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/redis-%23DD0031.svg?style=for-the-badge&logo=redis&logoColor=white)
![MinIO](https://img.shields.io/badge/MinIO-C72E49?style=for-the-badge&logo=minio&logoColor=white)
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

#### **ArtVizor — AI-сервис анализа изображений**
Микросервисный backend: по загруженной картине определяет художественный стиль, палитру из 5 цветов и находит 6 похожих работ.
* **Стек:** Spring Boot, Spring Security (JWT), PostgreSQL + pgvector, RabbitMQ, MinIO (S3), Python (ML-воркер), Docker Compose.
* **Архитектура:** REST API + ML-воркер с асинхронным взаимодействием через RabbitMQ; векторный поиск похожих на pgvector (cosine + HNSW) по базе 56k картин; изображения в MinIO через presigned URL.
* **ML & Деплой:** классификатор стиля CLIP + MLP (75% Top-1 / 95% Top-3, 27 стилей); CI/CD (GitHub Actions → GHCR → SSH-деплой на VPS).

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

---

### 📊 GitHub Stats

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=eeffeecct&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" alt="stats" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=eeffeecct&layout=compact&theme=tokyonight&hide_border=true&langs_count=8" alt="top langs" />
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com?user=eeffeecct&theme=tokyonight&hide_border=true" alt="streak" />
</p>

---

### 📫 Connect

[![Telegram](https://img.shields.io/badge/Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/eeffeecct)
[![Gmail](https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:timter32@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/eeffeecct)
