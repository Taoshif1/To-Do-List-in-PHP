# Simple To-Do List Web Application (PHP, MySQL)

[![Passion Project](https://img.shields.io/badge/Passion-Project-brightgreen.svg?style=flat-square)](https://github.com/YOUR_GITHUB_USERNAME/YOUR_REPO_NAME)
[![Learning Completed](https://img.shields.io/badge/Learning-Completed-success.svg?style=flat-square)](https://github.com/YOUR_GITHUB_USERNAME/YOUR_REPO_NAME)
[![Dedicated Learner](https://img.shields.io/badge/Dedicated-Learner-ff69b4.svg?style=flat-square)](https://github.com/YOUR_GITHUB_USERNAME/YOUR_REPO_NAME)

Welcome to my very first **CRUD-based Todo List Web App**—a simple yet powerful project built with **PHP** and **MySQL** on the backend and **HTML/CSS** on the frontend. This was more than just a basic web app for me—this was a challenge, a learning experience and proof that I'm growing every single day as a developer.

## 💡 About the Project

This Todo List app allows you to:

* **Create:** Add new tasks to their list.
* **Read:** View all their current tasks, with completed tasks visually distinguished.
* **Update:** Mark tasks as "completed," which visually strikes them out.
* **Delete:** Remove tasks from their list entirely.
* **Persistence:** All tasks are stored in a MySQL database, ensuring they persist across sessions.

All tasks are stored in a **MySQL database**, and the app dynamically updates the UI based on the current task status. Simple, clean and fully functional.

## 🔧 Tech Stack

- **Frontend**: HTML, CSS  
- **Backend**: PHP  
- **Database**: MySQL  
- **Local Server**: XAMPP

## 🌱 What I Learned

Building this wasn’t just about code—it was about mindset. I’m not just coding. I’m **building a future**—one project at a time.

I had to:
- Deal with confusing PHP syntax and also some keywords
- Understand how GET and POST methods work
- Write clean SQL queries
- Use PHP with MySQLi for database integration
- Handle form submissions and page redirects smoothly
- Learn the beauty of `while` loops for dynamically rendering content

## 🤝 Areas for Future Improvement

While this application is functional, there are several areas I plan to explore for future enhancements:

* **User Authentication:** Implementing user accounts so each user has their own to-do list.
* **Task Editing:** Allowing users to modify existing tasks.
* **Due Dates and Priorities:** Adding the ability to set deadlines and priority levels for tasks.
* **Improved Styling:** Enhancing the user interface and experience with more advanced CSS.
* **Error Handling:** Implementing more robust error handling and user feedback.

## 🔧 Setup Instructions

To run this application locally, you will need a web server environment with PHP and MySQL installed (e.g., XAMPP, WAMP, MAMP).

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/YOUR_GITHUB_USERNAME/YOUR_REPO_NAME.git](https://www.google.com/search?q=https://github.com/YOUR_GITHUB_USERNAME/YOUR_REPO_NAME.git)
    ```
2.  **Set up the MySQL database:**
    * Create a new database named `todolist` in your MySQL server.
    * Run the following SQL query to create the `tasks` table:
        ```sql
        CREATE TABLE tasks (
            id INT AUTO_INCREMENT PRIMARY KEY,
            task VARCHAR(255) NOT NULL,
            status ENUM('pending', 'completed') DEFAULT 'pending'
        );
        ```
3.  **Place the `index.php` and `style.css` files** in the document root of your web server (e.g., `htdocs` in XAMPP).
4.  **Access the application** through your web browser by navigating to `http://localhost/YOUR_REPO_DIRECTORY/` (replace `YOUR_REPO_DIRECTORY` if necessary).

## 😤 Acknowledgements

A big thank you to the online communities, tutorials, and documentation that have been invaluable resources in my learning journey.


## 📸 Screenshots
*completed task*

![image](https://github.com/user-attachments/assets/db1d78c8-cd99-4d76-bd3d-5714dc32b376)
![image](https://github.com/user-attachments/assets/7d550b8d-4a04-4295-a2cf-b33608ac4c96)

*deleted task*

![image](https://github.com/user-attachments/assets/02f4bbd8-46cf-4932-af9f-f85a939f2cda)
![image](https://github.com/user-attachments/assets/a07064ca-d8b7-4702-9f79-7c3aa8e3d370)

 [I added some tasks in the middle]







