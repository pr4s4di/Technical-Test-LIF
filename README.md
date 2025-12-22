# Technical Test: Todo App with Authentication

## 📋 Overview
Hello! Thank you for your interest in the **Fullstack Engineer** position. 

In this test, we do not limit which libraries or state management solutions you must use.

**Goal:** Create a simple Todo List application that features Login functionality and persistent data CRUD.

## 📱 Functional Requirements

### 1. Authentication (Login)
* Simple Login page (Email & Password).
* Input validation (e.g., valid email format, password cannot be empty).
* After a successful login, persist the user session (token/session) in local storage so the user does not need to log in again when the app is restarted.
* *Note:* You may use Firebase Auth or a Mock API that supports login simulation (such as [Reqres.in](https://reqres.in/) or [MockAPI.io](https://mockapi.io/)).

### 2. Todo Dashboard (CRUD)
Once logged in, the user is redirected to the main page displaying their Todo list.
* **Create:** User can add a new task.
* **Read:** Display the list of tasks.
* **Update:** User can edit a task or mark it as "Completed".
* **Delete:** User can delete a task.

### 3. Data Persistence
* All Todo data must be stored on a persistence storage.
* Data must be isolated per user (User A must not see User B's todos).

## 🛠 Technical Freedom
You are **free** to use any tech stack you are proficient in or prefer:

* **State Management:** BLoC, Riverpod, Provider, GetX, MobX, etc.
* **Networking:** Dio, Http, Chopper, Retrofit, etc.
* **Architecture:** Clean Architecture, MVVM, MVP, MVC.
* **UI Library:** Material, Cupertino, or Shadcn/Custom.

## ➕ Bonus (Optional for Fullstack Role)
Since this role also involves **Golang** in the future, it is a plus if you include a text file named `API_DESIGN.md` containing:
* A brief design of the JSON Request/Response structure if you were to build the Backend.
* A simple database schema design for this User + Todo case.

## 📦 Submission
1.  Upload your code to a public repository (GitHub/GitLab).
2.  Include a `README.md` file in your repository with instructions on how to run the app.
3.  Send the repository link to us.

---
*Happy Coding!*
