# Денис Утямишев — Full-Stack Developer

Разрабатываю веб-приложения от интерфейса до API, базы данных и запуска. Основной
фокус — **React, PHP, PostgreSQL и Docker**. Люблю понятную архитектуру, работающие
пользовательские сценарии и решения, которые можно развивать без лишней сложности.

[![Email](https://img.shields.io/badge/Email-zordonlord%40mail.ru-blue)](mailto:zordonlord@mail.ru)
[![GitHub](https://img.shields.io/badge/GitHub-ZordonLord-black?logo=github)](https://github.com/ZordonLord)
[![VK](https://img.shields.io/badge/VK-Profile-4680C2?logo=vk&logoColor=white)](https://vk.com/zordonlord)
[![Website](https://img.shields.io/badge/Site-gexus.ru-orange?logo=google-chrome&logoColor=white)](https://gexus.ru)

Прошёл профессиональную переподготовку и последовательно развиваюсь в full-stack
разработке, тестировании, DevOps-практиках и проектировании REST API.

---

## 🧭 Что я умею

- создавать адаптивные React-интерфейсы и организовывать клиентскую маршрутизацию;
- проектировать REST API на PHP и разделять ответственность между Router, Controller,
  Service и Repository;
- интегрировать внешние сервисы и CRM через REST API и OAuth 2.0;
- проектировать обработку webhook-событий и синхронизацию данных между внешним API
  и локальным хранилищем;
- работать с PostgreSQL/SQLite, кэшированием, пагинацией, нормализацией и поиском дублей;
- контейнеризировать локальную инфраструктуру с Docker Compose;
- поддерживать качество кода через PHPUnit, PHP_CodeSniffer, ESLint и сборку frontend;
- разбираться в задаче целиком: от структуры данных и бизнес-логики до UX и деплоя.

---

## 🚀 Главный проект

### [GexusFilm — киноагрегатор на React и PHP](https://github.com/ZordonLord/GexusFilm)

Full-stack приложение для поиска и выбора фильмов и сериалов. Проект получает данные
из TMDB, сохраняет медиа и TTL-кэш в PostgreSQL и предоставляет единый REST API для
frontend.

**Ключевые возможности:**

- каталоги фильмов и сериалов: trending, popular, now playing, upcoming и другие;
- страницы деталей, сезоны и эпизоды сериалов;
- поиск и discover с фильтрами через PostgreSQL и fallback к TMDB;
- единый Media UI и Axios API-клиент на frontend;
- health-check для PostgreSQL/TMDB-контура.

**Инженерные решения:**

- React 19 + React Router 7 + Vite 8;
- PHP 8.1+, Composer, PSR-4 и собственный параметризованный Router;
- разделение на `Controller → Service → Repository`;
- `ContentSourceInterface` для независимости бизнес-логики от TMDB;
- локальная защита внешнего API: singleflight, rate limiting и circuit breaker;
- PHPUnit, PHP_CodeSniffer, ESLint и Docker Compose для разработки.

> **Статус:** проект активно развивается; базовый каталог, поиск, discover, REST
> маршрутизация и общий Media UI уже работают.

[→ Открыть репозиторий GexusFilm](https://github.com/ZordonLord/GexusFilm)

---

## 📌 Другие проекты

### [Task Manager — React + PHP + SQLite](https://github.com/ZordonLord/taskmanager-react-php-sqlite)

Full-stack приложение для управления задачами с **JWT-авторизацией, REST API,
адаптивным интерфейсом, Docker-деплоем и CI/CD через GitHub Actions**.

### [AmoCRM Client — PHP-интеграция с amoCRM API](https://github.com/ZordonLord/AmoCRMoAuth2)

Прикладной PHP-клиент для amoCRM с **OAuth 2.0, управлением контактами и сделками,
SQLite-синхронизацией, webhook-обработкой и поиском дублей** по системным и пользовательским
полям.

### [LuxFashion — React + TypeScript](https://github.com/ZordonLord/react-js-luxfashion)

Адаптивный frontend интернет-магазина, сверстанный по макету Figma с фокусом на
компонентный подход и пользовательский интерфейс.

### [PhoneBook — Python CRUD](https://github.com/ZordonLord/PhoneBook)

CRUD-приложение с хранением в JSON/CSV, поиском, фильтрацией и импортом/экспортом
данных.

### [PetManager — Java](https://github.com/ZordonLord/PetManager)

Консольное приложение для учёта питомцев с применением **OOP, модульной архитектуры
и UML-диаграмм**.

---

## 🛠 Технологический стек

**Frontend:**
![React](https://img.shields.io/badge/-React-61DAFB?logo=react&logoColor=black)
![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?logo=typescript&logoColor=white)
![HTML5](https://img.shields.io/badge/-HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/-CSS3-1572B6?logo=css3&logoColor=white)

**Backend и API:**
![PHP](https://img.shields.io/badge/-PHP-777BB4?logo=php&logoColor=white)
![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white)
![Java](https://img.shields.io/badge/-Java-007396?logo=java&logoColor=white)
![REST API](https://img.shields.io/badge/-REST%20API-005571)

**Данные и инфраструктура:**
![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-4169E1?logo=postgresql&logoColor=white)
![SQLite](https://img.shields.io/badge/-SQLite-003B57?logo=sqlite&logoColor=white)
![MySQL](https://img.shields.io/badge/-MySQL-4479A1?logo=mysql&logoColor=white)
![Docker](https://img.shields.io/badge/-Docker-2496ED?logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/-Linux-FCC624?logo=linux&logoColor=black)
![Nginx](https://img.shields.io/badge/-Nginx-009639?logo=nginx&logoColor=white)

**Качество и инструменты:** PHPUnit, PHP_CodeSniffer, ESLint, GitHub Actions,
Figma, Postman, VS Code, IntelliJ IDEA.

---

## 📈 GitHub

<div id="stat" align="center">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=ZordonLord&theme=transparent" alt="GitHub profile details" />
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=ZordonLord&theme=transparent" alt="Most used languages" />
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=ZordonLord&theme=transparent" alt="GitHub statistics" />
</div>

---

## 🌐 Дополнительно

Сайт об информационных технологиях: [Gexus.ru](https://gexus.ru/)
