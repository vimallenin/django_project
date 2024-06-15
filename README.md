# Django Blog Application

A simple blog application built with Django, featuring user authentication, CRUD operations for blog posts, and a responsive Bootstrap-based layout.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Setup](#setup)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [Contact](#contact)

## Introduction

This project is a blog application built with Django, providing a platform for users to create, read, update, and delete blog posts. The application includes user authentication, allowing users to register, log in, and manage their profiles. The interface is designed using Bootstrap for a responsive and modern look.

## Features

- User authentication (register, login, logout)
- Create, read, update, and delete blog posts
- User profile management
- Responsive design using Bootstrap
- Flash messages for user feedback

## Technologies Used

- Django
- Bootstrap 4
- SQLite (default Django database)
- HTML/CSS
- JavaScript (jQuery, Popper.js)

## Setup

To get a local copy up and running, follow these steps:

1. **Clone the repository:**
    ```sh
    git clone https://github.com/your-username/django-blog.git
    ```

2. **Navigate to the project directory:**
    ```sh
    cd django-blog
    ```

3. **Create a virtual environment:**
    ```sh
    python3 -m venv env
    ```

4. **Activate the virtual environment:**
    - On Windows:
      ```sh
      .\env\Scripts\activate
      ```
    - On macOS and Linux:
      ```sh
      source env/bin/activate
      ```

5. **Install the dependencies:**
    ```sh
    pip install -r requirements.txt
    ```

6. **Run the migrations:**
    ```sh
    python manage.py migrate
    ```

7. **Create a superuser:**
    ```sh
    python manage.py createsuperuser
    ```

8. **Run the development server:**
    ```sh
    python manage.py runserver
    ```

9. **Open your browser and navigate to:**
    ```
    http://127.0.0.1:8000
    ```

## Usage

- **Home Page:** Displays all blog posts.
- **About Page:** Information about the blog.
- **New Post:** Logged-in users can create a new blog post.
- **Profile:** Manage user profile and view user's posts.
- **Register/Login:** New users can register, and existing users can log in.


## Contributing

Contributions are welcome! If you have any suggestions or improvements, please feel free to open an issue or submit a pull request.

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Commit your changes (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Open a pull request.

## Contact

Feel free to reach out to me via:

- **LinkedIn:** [Vimal Lenin](https://www.linkedin.com/in/vimal-lenin-18aa46210)
- **GitHub:** [vimallenin](https://github.com/vimallenin)
- **Email:** [vimallenin70@gmail.com](mailto:vimallenin70@gmail.com)


