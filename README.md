# 🧸 Планирование путешествий с использованием LLM (Travel Planner with LLM) ✈️

<div align="center">
  <img src="https://img.shields.io/badge/Python-3.9+-blue?logo=python" alt="Python">
  <img src="https://img.shields.io/badge/FastAPI-0.68+-green?logo=fastapi" alt="FastAPI">
  <img src="https://img.shields.io/badge/PostgreSQL-13+-blue?logo=postgresql" alt="PostgreSQL">
  <img src="https://img.shields.io/badge/Docker-20.10+-blue?logo=docker" alt="Docker">
</div>

## 📝 Описание проекта
Мобильное приложение для интеллектуального планирования путешествий с использованием языковых моделей. Сервис предоставляет:

✔️ Персонализированные рекомендации по направлениям  
✔️ Умный поиск авиабилетов и отелей  
✔️ Интеграцию с Telegram-ботом для консультаций  
✔️ Удобное управление своими путешествиями  

## 🛠 Технологический стек

### Backend
| Технология | Назначение |
|------------|------------|
| Python 3.9+ | Основной язык |
| FastAPI | Веб-фреймворк |
| PostgreSQL | База данных |
| GigaChat | Языковая модель |
| Docker | Контейнеризация |

### Frontend
| Технология | Назначение |
|------------|------------|
| Kotlin | Мобильное приложение |
| Jetpack Compose | UI компоненты |

## 📚 API Документация

### 🔐 Аутентификация

#### Регистрация пользователя
```http
POST /register
Content-Type: application/json

{
  "username": "string",
  "email": "email@example.com",
  "password": "string"
}
