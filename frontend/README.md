<div align="center">

# 🎬 FilmAdviser Frontend

**Клиентская часть SPA-приложения для интеллектуального поиска фильмов.**
<br>
*Пользовательский интерфейс, объединяющий классический REST API и AI-сервисы.*

<p align="center">
  <img src="https://img.shields.io/badge/React-18.2-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React" />
  <img src="https://img.shields.io/badge/TypeScript-Strict-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/State-Context_API-purple?style=for-the-badge" alt="Context API" />
  <img src="https://img.shields.io/badge/Style-SCSS_Modules-CC6699?style=for-the-badge&logo=sass&logoColor=white" alt="SCSS" />
</p>

[➡️ Открыть демо (GitHub Pages)](https://doomsday058.github.io/online-cinema-frontend/)

<img src="./assets/5195439896238619788.jpg" alt="Interface Preview" width="100%" style="border-radius: 10px; box-shadow: 0px 4px 20px rgba(0,0,0,0.5);">

</div>

---

## 🏛️ Архитектура приложения

Frontend выступает единой точкой входа, агрегируя данные из двух независимых микросервисов.

```mermaid
graph TD
    User((User)) -->|Browser| Client[React Client]
    
    subgraph Services
        Client -->|Auth & User Data| Node[Node.js Backend]
        Client -->|ML Recommendations & NLP| Python[Python AI Service]
    end
    
    Node --> DB[(MongoDB)]
    Python --> TMDB((TMDB API))
    Python --> OpenAI((OpenAI GPT))
