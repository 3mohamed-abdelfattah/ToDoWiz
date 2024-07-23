# ToDoWiz

Welcome to ToDoWiz, your ultimate task management app for tracking tasks, organizing your schedule, and staying productive.

## Table of Contents

- [Features](#features)
- [Screenshots](#screenshots)
- [Contributing](#contributing)

## Features

- **Add Tasks:** Easily add new tasks to your list.
- **Edit Tasks:** Modify details of existing tasks.
- **Add to Favorites:** Mark important tasks as favorites for quick access.
- **Delete Tasks:** Remove tasks that are completed or no longer needed.
- **Manage your tasks efficiently with our simple and flexible interface.**

## Screenshots

<img src="https://github.com/user-attachments/assets/2fbc1c04-d108-422c-a934-49d7f00a5a9a" alt="ToDo App" width="330"/>
<img src="https://github.com/user-attachments/assets/77f3b5e0-bab0-4bce-8240-34ad292f797c" alt="ToDo App" width="330"/>
<img src="https://github.com/user-attachments/assets/0c119875-b84c-4b27-a2fc-540a19550ba9" alt="ToDo App" width="330"/>
<img src="https://github.com/user-attachments/assets/080bdcb1-3a7b-4590-b65a-fc73703491c9" alt="ToDo App" width="330"/>
<img src="https://github.com/user-attachments/assets/4f6edeaf-3ebb-405a-8ffa-bf6e496734ac" alt="ToDo App" width="330"/>
<img src="https://github.com/user-attachments/assets/6d94e0d6-2efd-4eb6-a832-b38a75be9655" alt="ToDo App" width="330"/>

---
## Screenshots from my Environment

 <table align="center">
  <tr>
    <td><img src="https://github.com/user-attachments/assets/d7458e84-26e8-44c1-8890-edd473180830" alt="ToDo Image"  style="border: 5px solid #92E3A9;"/></td>
    <td><img src="https://github.com/user-attachments/assets/a09a073f-8dc1-4e80-a33c-603e31dfaa0a" alt="ToDo Image"  style="border: 5px solid #92E3A9;"/></td>
    <td><img src="https://github.com/user-attachments/assets/d2cd3765-93b1-406c-8c98-542daaeba3da" alt="ToDo Image"  style="border: 5px solid #92E3A9;"/></td>
  </tr>
</table>

---
## Snapshot from my Device



https://github.com/user-attachments/assets/8989a6b7-8dc0-403d-a000-4b3793e8e052



## Contributing

We welcome contributions from the community! To contribute to ToDoWiz, follow these steps:

1. **Fork the repository:**

    Click the "Fork" button on the top right of this page to create a copy of this repository on your GitHub account.

2. **Clone your fork:**

    ```bash
    git clone https://github.com/yourusername/ToDoWiz.git
    cd ToDoWiz
    ```

3. **Create a branch:**

    ```bash
    git checkout -b feature-name
    ```

4. **Make your changes:**

    Implement your changes and commit them.

5. **Push to your fork:**

    ```bash
    git push origin feature-name
    ```

6. **Submit a pull request:**

    Go to the original repository on GitHub and create a new pull request.


<h2 align="center">Thank you for using ToDoWiz!</h2>

---

<h4 align="center">The only way to do great work is to love what you do.</h4>

---

This is a Kotlin Multiplatform project targeting Android, iOS.

* `/composeApp` is for code that will be shared across your Compose Multiplatform applications.
  It contains several subfolders:
  - `commonMain` is for code that’s common for all targets.
  - Other folders are for Kotlin code that will be compiled for only the platform indicated in the folder name.
    For example, if you want to use Apple’s CoreCrypto for the iOS part of your Kotlin app,
    `iosMain` would be the right folder for such calls.

* `/iosApp` contains iOS applications. Even if you’re sharing your UI with Compose Multiplatform, 
  you need this entry point for your iOS app. This is also where you should add SwiftUI code for your project.


Learn more about [Kotlin Multiplatform](https://www.jetbrains.com/help/kotlin-multiplatform-dev/get-started.html)…

