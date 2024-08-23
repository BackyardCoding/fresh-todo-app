# Fresh/Deno Todo App

- [Fresh/Deno Todo App](#freshdeno-todo-app)
  - [🚀 Project Overview](#-project-overview)
    - [✨ Features](#-features)
  - [🛠️ Tech Stack](#️-tech-stack)
  - [📂 Project Structure](#-project-structure)
  - [🔑 Key Files](#-key-files)
  - [🚀 Getting Started](#-getting-started)
    - [Prerequisites](#prerequisites)
    - [Installation](#installation)
  - [🧩 How It Works](#-how-it-works)
    - [Todo Management](#todo-management)
  - [📸 Screenshots](#-screenshots)
    - [Home Page](#home-page)
    - [Adding a Todo](#adding-a-todo)
    - [Todo List](#todo-list)
  - [📝 License](#-license)
  - [🙌 Acknowledgments](#-acknowledgments)
  - [📬 Contact](#-contact)

## 🚀 Project Overview

This is a simple Todo application built with [Fresh](https://fresh.deno.dev/), a Deno framework for creating modern web applications using JavaScript/TypeScript. The project showcases my skills in building full-stack applications with TypeScript, server-side rendering (SSR), and modern front-end development techniques. The hosted application can be viewed under the following [link](https://mdumbuya-fresh-todo-app.deno.dev/).

### ✨ Features

- **Create Todos**: Easily add new tasks to your todo list.
- **Edit Todos**: Modify tasks effortlessly.
- **Delete Todos**: Remove tasks from the list with ease.
- **Responsive Design**: Optimized for both desktop and mobile devices.
- **No External Dependencies**: Fully built using Deno's standard library and the Fresh framework.

## 🛠️ Tech Stack

- **Frontend**: 
  - [Preact](https://preactjs.com/): A lightweight React alternative for building UI components.
  - [Tailwind CSS](https://tailwindcss.com/): A utility-first CSS framework for styling.
  
- **Backend**:
  - [Deno](https://deno.land/): A modern runtime for JavaScript and TypeScript.
  - [Fresh](https://fresh.deno.dev/): A web framework that combines server-side rendering with modern front-end tools.

- **TypeScript**: Strongly typed programming for reliable and maintainable code.

## 📂 Project Structure

```bash
.
├── components
├── deno.json
├── dev.ts
├── fresh.config.ts
├── fresh.gen.ts
├── interfaces
├── islands
├── main.ts
├── node_modules
├── README.md
├── routes
├── static
├── structure.md
└── tailwind.config.ts
```

## 🔑 Key Files

- **`index.tsx`**: The main page of the application that includes the todo form and list.
- **`Todos.tsx`**: The interactive component responsible for managing and displaying todos.
- **`ITodo.ts`**: TypeScript interface defining the structure of a todo item.

## 🚀 Getting Started

### Prerequisites

[Deno](https://deno.land/) installed on your machine.

### Installation

1. **Clone the repository**:

    ```bash
    git clone https://github.com/mdumbuya/todo-fresh-deno.git
    cd todo-fresh-deno
    ```

2. **Run the development server**:

    ```bash
    deno task start
    ```

3. **Open the app in your browser**:

    ```
    http://localhost:8000
    ```

## 🧩 How It Works

### Todo Management

The app uses a simple useState hook in Preact to manage the list of todos. Each todo is represented by a TypeScript interface ITodo, which ensures strong typing throughout the application.
Adding Todos

New todos are added by submitting a form. The inputRef reference is used to capture and clear the input field after submission.
Editing and Deleting Todos

Each todo item is rendered using a Todo component, which has props to handle editing and removing the item. The list is updated efficiently using array methods such as map and filter.
Conditional Rendering

The app conditionally renders the list of todos or a completion message based on whether the todos array is empty.

## 📸 Screenshots
### Home Page
[Home Page](./screenshots/app_without_todos.png)

### Adding a Todo
[Editing a Todo](./screenshots/editing_todo.png)

### Todo List
[Todo List](./screenshots/app_without_todos.png)


## 📝 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 🙌 Acknowledgments

    Fresh Framework
    Preact
    Deno
    Tailwind CSS

Thanks to [@learnbydoing993](https://github.com/learnbydoing993) for this [code](https://github.com/learnbydoing993/fresh-todo).
    

## 📬 Contact

Feel free to reach out if you have any questions or suggestions!

[LinkedIn](www.linkedin/in/mdumbu) 

[Mastodon](https://mastodon.social/@backyardcoding)

    
