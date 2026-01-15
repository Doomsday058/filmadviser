<p align="center">
  <img src="./assets/5195439896238619788.jpg" alt="Interface Preview" width="800px">
</p>

<div align="center">

# Интеллектуальный киносервис "FilmAdviser"

_React-клиент для экосистемы поиска фильмов с интеграцией AI-аналитики и рекомендаций._

</div>

<p align="center">
    <img src="https://img.shields.io/badge/status-live-success?style=for-the-badge" alt="Status">
    <img src="https://img.shields.io/github/last-commit/Doomsday058/online-cinema-frontend?style=for-the-badge" alt="Last Commit">
    <img src="https://img.shields.io/github/languages/top/Doomsday058/online-cinema-frontend?style=for-the-badge" alt="Top Language">
</p>

---

### ➡️ **[Открыть Live Demo](https://doomsday058.github.io/online-cinema-frontend/)**

---

### 🏛️ Архитектура системы

Frontend выступает точкой входа для микросервисной архитектуры, объединяя классический REST API и ML-сервисы:

| Сервис | Роль в системе | Репозиторий |
| :--- | :--- | :--- |
| 🎨 **Frontend (React)** | Клиентское SPA-приложение с реактивным интерфейсом и роутингом. | _(текущий)_ |
| ⚙️ **Backend (Node.js)** | Основной API: авторизация (JWT), профиль пользователя, работа с БД. | **[Перейти](https://github.com/Doomsday058/online-cinema-backend)** |
| 🧠 **AI-Backend (Python)** | ML-сервис: семантический поиск и движок рекомендаций (RAG/LLM). | **[Перейти](https://github.com/Doomsday058/online-cinema-flask)** |

---

### 🚀 Ключевой функционал

| Фича | Техническая реализация |
| :--- | :--- |
| **🤖 Smart Recommendations** | Формирование динамической ленты на основе весового анализа жанров и актеров из избранного. |
| **✍️ AI-Reviewer** | Генерация контекстных рецензий через GPT. Тональность отзыва адаптируется под рейтинг фильма. |
| **🔍 NLP Search** | Обработка поисковых запросов на естественном языке (например: *"триллеры 90-х"*). |
| **🔐 Auth & Profile** | Безопасная авторизация, управление сессиями и синхронизация избранного между устройствами. |
| **📱 Responsive UI** | Адаптивная верстка (Mobile First) для корректной работы на любых экранах. |

---

### 🛠️ Технологический стек

<p>
    <img src="https://img.shields.io/badge/React-18.2-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React" />
    <img src="https://img.shields.io/badge/TypeScript-Strict-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript" />
    <img src="https://img.shields.io/badge/React_Router-v6-CA4245?style=for-the-badge&logo=react-router&logoColor=white" alt="React Router" />
    <img src="https://img.shields.io/badge/Axios-HTTP-5A29E4?style=for-the-badge&logo=axios&logoColor=white" alt="Axios" />
    <img src="https://img.shields.io/badge/Sass-Modules-CC6699?style=for-the-badge&logo=sass&logoColor=white" alt="SCSS" />
</p>

---

<details>
<summary>▶️ 📦  <strong>Инструкции по локальному запуску</strong></summary>

<br>

1.  **Клонирование репозитория:**
    ```bash
    git clone [https://github.com/Doomsday058/online-cinema-frontend.git](https://github.com/Doomsday058/online-cinema-frontend.git)
    cd online-cinema-frontend
    ```

2.  **Установка зависимостей:**
    ```bash
    npm install
    # или npm ci для строгой установки версий
    ```

3.  **Конфигурация окружения:**
    Создайте файл `.env` в корне проекта (см. `.env.example`):
    ```env
    # Основной бэкенд (Auth, DB)
    REACT_APP_NODE_API_URL=https://...
    
    # Python микросервис (AI Features)
    REACT_APP_PYTHON_AI_URL=https://...
    ```

4.  **Запуск в режиме разработки:**
    ```bash
    npm start
    ```

5.  **Сборка и деплой (GH Pages):**
    ```bash
    npm run deploy
    ```

</details>
