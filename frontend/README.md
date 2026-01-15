<p align="center">

  <img src="./assets/5195439896238619788.jpg" alt="Скриншот проекта FilmAdviser" width="800px">

</p>



<div align="center">



# Интеллектуальный киносервис "FilmAdviser"



_Одностраничное веб-приложение (SPA) на React для поиска фильмов, получения AI-рекомендаций и обзоров._



</div>



<p align="center">

    <img src="https://img.shields.io/badge/status-live-success?style=for-the-badge" alt="Статус">

    <img src="https://img.shields.io/github/last-commit/Doomsday058/online-cinema-frontend?style=for-the-badge" alt="Последний коммит">

    <img src="https://img.shields.io/github/languages/top/Doomsday058/online-cinema-frontend?style=for-the-badge" alt="Основной язык">

</p>



---



### ➡️ **[Посмотреть живое демо (Live Demo)](https://doomsday058.github.io/online-cinema-frontend/)**



---



### 🏛️ Архитектура проекта



Этот проект является частью full-stack системы, состоящей из трех независимых сервисов:



| Сервис | Описание | Репозиторий |

| :--- | :--- | :--- |

| 🎨 **Frontend (React)** | Клиентская часть, которую вы видите. | _(текущий)_ |

| ⚙️ **Backend (Node.js)** | Основной API для работы с пользователями и базой данных. | **[Перейти](https://github.com/Doomsday058/online-cinema-backend)** |

| 🧠 **AI-Backend (Python)** | Сервис для генерации рекомендаций и обзоров. | **[Перейти](https://github.com/Doomsday058/online-cinema-flask)** |



---



### 🚀 Основные возможности



| Функция | Описание |

| :--- | :--- |

| **🤖 Персональные рекомендации** | Лента фильмов, подобранная на основе предпочтений пользователя. |

| **✍️ AI-обзоры** | Уникальные обзоры на фильмы, сгенерированные моделью GPT. |

| **🔍 Расширенный поиск** | Возможность поиска по текстовому запросу на естественном языке. |

| **❤️ Авторизация и избранное**| Регистрация, вход и сохранение любимых фильмов в личный список. |

| **📱 Адаптивный дизайн** | Корректное отображение на всех устройствах. |



---



### 🛠️ Технологический стек



<p>

    <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React" />

    <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript" />

    <img src="https://img.shields.io/badge/React_Router-CA4245?style=for-the-badge&logo=react-router&logoColor=white" alt="React Router" />

    <img src="https://img.shields.io/badge/Axios-5A29E4?style=for-the-badge&logo=axios&logoColor=white" alt="Axios" />

    <img src="https://img.shields.io/badge/Sass-CC6699?style=for-the-badge&logo=sass&logoColor=white" alt="SCSS" />

</p>



---



<details>

<summary>▶️ 📦  <strong>Инструкции по установке и запуску</strong></summary>



<br>



1.  **Клонируйте репозиторий:**

    ```bash

    git clone [https://github.com/Doomsday058/online-cinema-frontend.git](https://github.com/Doomsday058/online-cinema-frontend.git)

    cd online-cinema-frontend

    ```



2.  **Установите зависимости:**

    ```bash

    npm install

    ```



3.  **Создайте файл `.env`** в корне проекта и добавьте переменные для подключения к бэкендам:

    ```

    REACT_APP_NODE_API_URL=https://...

    REACT_APP_PYTHON_AI_URL=https://...

    ```



4.  **Запустите приложение для локальной разработки:**

    ```bash

    npm start

    ```



5.  **Для деплоя на GitHub Pages:**

    ```bash

    npm run deploy

    ```



</details>
