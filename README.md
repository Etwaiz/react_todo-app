# 📝 Todo App with API

![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
![TypeScript](https://img.shields.io/badge/typescript-%23007acc.svg?style=for-the-badge&logo=typescript&logoColor=white)
![Vite](https://img.shields.io/badge/vite-%23646CFF.svg?style=for-the-badge&logo=vite&logoColor=white)
![Sass](https://img.shields.io/badge/Sass-CC6699?style=for-the-badge&logo=sass&logoColor=white)
![Bulma](https://img.shields.io/badge/Bulma-00D1B2?style=for-the-badge&logo=bulma&logoColor=white)

Сучасний та швидкий менеджер завдань, побудований на **React** та **TypeScript**. Проект взаємодіє з реальним REST API для збереження та управління списком справ.

## 🚀 Основні можливості

- **Повний цикл CRUD**: створення, читання, оновлення та видалення завдань на сервері.
- **Фільтрація**: перегляд усіх завдань, тільки активних або вже завершених.
- **Масові дії**: можливість позначити всі завдання як виконані або видалити всі завершені одним кліком.
- **Оптимістичне оновлення**: інтерфейс реагує миттєво, поки запит йде на сервер.
- **Валідація**: захист від порожніх назв та обробка помилок мережі.

## 🛠 Технологічний стек

- **Frontend**: React (Hooks, Context/Props), TypeScript.
- **Стилізація**: SCSS (БЕМ), Bulma CSS Framework.
- **Збірка**: Vite.
- **API**: RESTful API для віддаленого зберігання даних.

## 📦 Як запустити проект

1.  **Клонуйте репозиторій:**

    ```bash
    git clone [https://github.com/Etwaiz/react_todo-app-with-api.git](https://github.com/Etwaiz/react_todo-app-with-api.git)
    ```

2.  **Перейдіть у папку проекту:**

    ```bash
    cd react_todo-app-with-api
    ```

3.  **Встановіть залежності:**

    ```bash
    npm install
    ```

4.  **Налаштуйте `USER_ID`:**
    Відкрийте файл `src/api/todos.ts` та вкажіть ваш персональний ID.

5.  **Запустіть сервер для розробки:**
    ```bash
    npm run dev
    ```

## 📐 Структура проекту

- `src/api` — клієнт для роботи з мережевими запитами (Fetch).
- `src/components` — перевикористовувані React-компоненти.
- `src/styles` — SCSS модулі та глобальні стилі.
- `src/types` — описи інтерфейсів та типів TypeScript.

---

Розроблено [Etwaiz](https://github.com/Etwaiz).
