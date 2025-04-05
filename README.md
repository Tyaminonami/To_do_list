#  To-Do List (ASP.NET Core MVC)

**To-Do List** — веб-приложение для управления задачами, реализованное на C# с использованием ASP.NET Core MVC и PostgreSQL.

---

##  Используемые технологии

- **C# / .NET 9**
- **ASP.NET Core MVC**
- **Entity Framework Core**
- **PostgreSQL**
- **Razor Views**
- **JSON** (импорт / экспорт)
- **HttpClient** + внешние API:
  - [Open-Meteo](https://open-meteo.com/)
  - [Alpha Vantage](https://www.alphavantage.co/) 

---

##  Основные возможности

- Добавление, редактирование, удаление задач
- Выполнение задач с переносом в архив
- Полное удаление задач из архива
- Фильтрация задач по тегам
- Импорт / экспорт задач и архива в JSON
- Отображение курса валют (USD → RUB)
- Отображение текущей температуры (Тверь и Баку)

---

##  Структура базы данных

- TaskItems — активные задачи  
- CompletedTasks — выполненные задачи (архив)
