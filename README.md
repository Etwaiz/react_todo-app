# 📝 Todo App with API

![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
![TypeScript](https://img.shields.io/badge/typescript-%23007acc.svg?style=for-the-badge&logo=typescript&logoColor=white)
![Vite](https://img.shields.io/badge/vite-%23646CFF.svg?style=for-the-badge&logo=vite&logoColor=white)
![Sass](https://img.shields.io/badge/Sass-CC6699?style=for-the-badge&logo=sass&logoColor=white)
![Bulma](https://img.shields.io/badge/Bulma-00D1B2?style=for-the-badge&logo=bulma&logoColor=white)

A modern and high-performance task manager built with **React** and **TypeScript**. This project interacts with a real REST API to persist and manage a todo list.

## 🚀 Key Features

- **Full CRUD Support**: Create, Read, Update, and Delete tasks on a remote server.
- **Advanced Filtering**: Filter tasks by status (All, Active, Completed).
- **Bulk Operations**: Toggle all tasks as completed or clear all finished tasks with a single click.
- **Optimistic Updates**: The UI responds instantly while the background request is being processed.
- **Robust Validation**: Includes protection against empty titles and handles network errors gracefully.

## 🛠 Tech Stack

- **Frontend**: React (Hooks, Refs, State Management), TypeScript.
- **Styling**: SCSS (BEM methodology), Bulma CSS Framework.
- **Tooling**: Vite for fast development and bundling.
- **Data Fetching**: RESTful API integration using Fetch.

## 📦 Getting Started

1.  **Clone the repository:**

    ```bash
    git clone https://github.com/Etwaiz/react_todo-app-with-api.git
    ```

2.  **Navigate to the project directory:**

    ```bash
    cd react_todo-app
    ```

3.  **Install dependencies:**

    ```bash
    npm install
    ```

4.  **Configure `USER_ID`:**
    Open `src/api/todos.ts` and set your personal ID to fetch your specific data.

5.  **Run the development server:**
    ```bash
    npm run dev
    ```

## 📐 Project Structure

- `src/api` — API client logic and Fetch wrapper.
- `src/components` — Modular and reusable React components.
- `src/styles` — Global styles and SCSS modules.
- `src/types` — TypeScript interfaces and enums for type safety.

---

Developed with ❤️ by [Etwaiz](https://github.com/Etwaiz).
