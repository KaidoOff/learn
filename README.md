# 🌐 Полная дорожная карта: Frontend & Backend (JS → TS + Инструменты)

Этот файл служит как **дорожная карта обучения веб-разработке**: от основ JavaScript до Senior Fullstack с TypeScript, включая фронтенд, бэкенд, базы данных, Postman и инструменты DevOps.

---

## 🟢 Этап 1: Основы JavaScript (Junior Frontend) ⏳

### Модуль 1: Переменные и типы данных ⏳
**Уроки:**
- var, let, const  
- Примитивные типы: number, string, boolean, null, undefined, symbol, bigint  
- Преобразование типов

**Практика (`learn` репозиторий):**
- Hello World  
- Калькулятор чисел  
- README для каждой задачи с описанием и кодом

**Проект:**
- Мини-игра «Угадай число»

---

### Модуль 2: Условия и операторы
**Уроки:**
- Арифметические, логические, сравнения  
- if / else / switch

**Практика (`learn`):**
- Фильтр массива чисел  

**Проект:**
- Фильтр товаров по категории и цене

---

### Модуль 3: Циклы и массивы
**Уроки:**
- for, while, for...of, for...in  
- Массивы: push, pop, shift, unshift  
- Методы массивов: map, filter, reduce, find, some, every

**Практика (`learn`):**
- Скрипт подсчета статистики массива чисел

**Проект:**
- Таблица лидеров игроков с сортировкой и фильтрацией

---

### Модуль 4: Функции и замыкания
**Уроки:**
- Function declaration, function expression, arrow functions  
- Параметры по умолчанию, rest/spread  
- Замыкания (closures)  

**Практика (`learn`):**
- Счетчик с замыканием  
- Функции-хелперы для массива  

**Проект:**
- Мини-библиотека утилит для работы с массивами и строками

---

### Модуль 5: Объекты
**Уроки:**
- Создание объектов и доступ к свойствам  
- Object.keys, Object.values, Object.entries  
- Деструктуризация  

**Практика (`learn`):**
- Конвертер данных объекта  
- Фильтр объектов по ключу/значению  

**Проект:**
- Контактная книга (CRUD в памяти)

---

### Модуль 6: Асинхронность
**Уроки:**
- setTimeout, setInterval  
- Promise: then, catch, finally  
- async/await  
- fetch API  

**Практика (`learn`):**
- Загрузка данных с публичного API (погода, новости)  
- Симуляция задержки функций  

**Проект:**
- Приложение «Погода» с загрузкой данных и отображением

---

## 🔵 Этап 2: Современный фронтенд на JS (Middle Frontend)

### Модуль 1: ES6+
**Уроки:**
- let/const, стрелочные функции, шаблонные строки  
- Spread/rest, деструктуризация  
- Import/export  
- Классы и наследование

**Практика (`learn`):**
- Мини-класс User с методами  
- Модульная организация кода  

---

### Модуль 2: Работа с DOM
**Уроки:**
- querySelector, querySelectorAll, createElement, appendChild  
- События: click, input, submit  
- Манипуляции с классами и стилями

**Практика (`learn`):**
- SPA без фреймворков (таб переключения, модальные окна)  

---

### Модуль 3: Работа с библиотеками
**Уроки:**
- Axios (HTTP-запросы)  
- Lodash (утилиты)  
- Day.js (даты)  

**Практика (`learn`):**
- SPA с API (каталог фильмов)  

---

### Модуль 4: React
**Уроки:**
- JSX, компоненты, props, state  
- useState, useEffect, useContext  
- React Router  
- Работа с формами  
- Подключение API  

**Практика (`learn`):**
- ToDo на React  
- Мини-магазин с корзиной  

**Проект (отдельный репозиторий):**
- SPA блог/каталог товаров  

**Postman:**
- Коллекция для тестирования API проекта (`/postman` в репозитории)

---

## 🟠 Этап 3: Backend на JS (Node.js / Express)

### Модуль 1: Основы Node.js
**Уроки:**
- Модули, fs, path, process  
- Event Loop  
- npm/yarn, package.json

**Практика (`learn`):**
- Скрипты работы с файлами  
- CLI утилиты  

---

### Модуль 2: Express.js
**Уроки:**
- Роуты, middleware  
- REST API  
- CRUD операции  

**Практика (`learn` + Postman):**
- API для заметок  
- API для пользователей (регистрация/логин, JWT)  

**Проект (отдельный репозиторий):**
- Мини-блог с API  

---

### Модуль 3: Базы данных
**Уроки:**
- MongoDB + Mongoose  
- PostgreSQL + pg  
- Основы SQL/NoSQL  
- ORM/ODM  

**Практика (`learn` + JSON для учебных целей):**
- CRUD через JSON / DB  
- Подключение API к облачной БД (MongoDB Atlas / Supabase)  

---

## 🟣 Этап 4: Fullstack JS
- Связка фронт/бэк  
- MVC архитектура  
- Авторизация (JWT, cookies)  
- Загрузка файлов (multer, Cloudinary)  

**Проект (отдельный репозиторий):**
- Мини-магазин fullstack  
- Блог fullstack с авторизацией  

**Postman:**  
- Коллекция API для тестирования (`/postman`)  

---

## 🔹 Этап 5: TypeScript (Frontend)
- Основы TS: типы, интерфейсы, generic  
- Типизация React-компонентов и API  
- Redux/RTK или Zustand с TS  

**Практика (`learn`):**
- ToDo + TS  
- Дашборд на React + TS  

---

## 🔹 Этап 6: TypeScript (Backend)
- Node + TS  
- DTO, интерфейсы  
- TypeORM / Prisma  
- SOLID, ошибки, middleware  

**Проект (отдельный репозиторий):**
- API для блога + TypeScript + PostgreSQL

---

## 🔹 Этап 7: Fullstack TS (Senior)
- Next.js / Nest.js  
- SSR, SSG  
- GraphQL (Apollo)  
- WebSockets  
- Тестирование: Jest, Vitest, Cypress  

**Проект (отдельный репозиторий):**
- Социальная сеть / SaaS платформа fullstack

---

## 🛠️ Этап 8: Инструменты и DevOps
- Git & GitHub (ветки, PR, rebase)  
- Docker / Docker Compose  
- Nginx / Apache  
- CI/CD (GitHub Actions)  
- Linux basics (bash, ssh)  
- Мониторинг: PM2, Sentry, Grafana  

**Практика (`learn` + отдельные репозитории):**
- Деплой fullstack проекта на VPS  
- Настройка автодеплоя  
- Контейнеризация фронта, бэка и БД  

---

## 📌 Советы
- Репозиторий `learn` → маленькие скрипты, мини-проекты, HTML/JS практики, Postman коллекции и JSON базы  
- Реальные проекты → отдельные репозитории с README, скриншотами, ссылками на живые версии (GitHub Pages / Vercel / Render)  
- Маленькие скрипты и учебные проекты показывают **прогресс**  
- Для каждого проекта создавай Postman коллекцию и добавляй её в репозиторий
