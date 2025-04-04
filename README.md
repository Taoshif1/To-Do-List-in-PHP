# Simple To-Do List Web Application (PHP, MySQL)

[![Passion Project](https://img.shields.io/badge/Passion-Project-brightgreen.svg?style=flat-square)](https://github.com/YOUR_GITHUB_USERNAME/YOUR_REPO_NAME)
[![Learning Completed](https://img.shields.io/badge/Learning-Completed-success.svg?style=flat-square)](https://github.com/YOUR_GITHUB_USERNAME/YOUR_REPO_NAME)
[![Dedicated Learner](https://img.shields.io/badge/Dedicated-Learner-ff69b4.svg?style=flat-square)](https://github.com/YOUR_GITHUB_USERNAME/YOUR_REPO_NAME)

Welcome to my very first **CRUD-based Todo List Web App**—a simple yet powerful project built with **PHP** and **MySQL** on the backend, and **HTML/CSS** on the frontend. This was more than just a basic web app for me—this was a challenge, a learning experience, and proof that I'm growing every single day as a developer.

## 💡 About the Project

This Todo List app allows you to:

* **Create:** Add new tasks to their list.
* **Read:** View all their current tasks, with completed tasks visually distinguished.
* **Update:** Mark tasks as "completed," which visually strikes them out.
* **Delete:** Remove tasks from their list entirely.
* **Persistence:** All tasks are stored in a MySQL database, ensuring they persist across sessions.


All tasks are stored in a **MySQL database**, and the app dynamically updates the UI based on the current task status. Simple, clean, and fully functional.

## 🔧 Tech Stack

- **Frontend**: HTML, CSS  
- **Backend**: PHP  
- **Database**: MySQL  
- **Local Server**: XAMPP

## 🌱 What I Learned

Building this wasn’t just about code—it was about mindset.

I had to:
- Deal with confusing PHP syntax (trust me, those semicolons tried to break me 😤)
- Understand how GET and POST methods work
- Write clean SQL queries
- Use PHP with MySQLi for database integration
- Handle form submissions and page redirects smoothly
- Learn the beauty of `while` loops for dynamically rendering content

## Areas for Future Improvement

While this application is functional, there are several areas I plan to explore for future enhancements:

* **User Authentication:** Implementing user accounts so each user has their own to-do list.
* **Task Editing:** Allowing users to modify existing tasks.
* **Due Dates and Priorities:** Adding the ability to set deadlines and priority levels for tasks.
* **Improved Styling:** Enhancing the user interface and experience with more advanced CSS.
* **Error Handling:** Implementing more robust error handling and user feedback.

## Acknowledgements

A big thank you to the online communities, tutorials, and documentation that have been invaluable resources in my learning journey.


## 🤝 My Developer Mindset

This app represents my **dedication**, **consistency**, and **fire to learn**. I know I have a long way to go, but this is a **solid step forward**. Every bug fixed and every feature added makes me a better programmer.

I’m not just coding.  
I’m **building a future**—one project at a time.

## 📸 Screenshots

> (Add screenshots here if you want later)

## Setup Instructions

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



## 📂 File Structure


