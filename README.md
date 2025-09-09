# Django Social Media Project

This is a social media web application built with Python and the Django framework. It allows users to create accounts, share posts with images, and interact with each other's content.

## Features

*   **User Authentication**: Sign up, log in, and log out functionality.
*   **User Profiles**: Each user has a profile with a customizable bio and profile picture.
*   **Create Posts**: Users can create new posts with an image and a caption.
*   **Like Posts**: Users can like and unlike posts.

## Technologies Used

*   **Python**: The core programming language for the back-end.
*   **Django**: A high-level Python web framework for rapid development.
*   **SQLite**: The default database for development.

## Setup and Installation

1.  **Create a Virtual Environment**:
    It is recommended to use a virtual environment to manage project dependencies.

    ```bash
    python -m venv .venv
    source .venv/bin/activate
    ```

2.  **Install Dependencies**:
    The required packages are listed in the `requirements.txt` file.

    ```bash
    pip install -r mysite/requirements.txt
    ```

3.  **Run the Development Server**:
    Start the Django development server to run the application locally.

    ```bash
    python mysite/manage.py runserver
    ```

## Project Structure

*   **`mysite/`**: The main Django project folder.
    *   **`settings.py`**: Contains the project's settings, including database configuration and installed apps.
    *   **`urls.py`**: The main URL configuration for the project.
*   **`userauth/`**: A Django app to handle user authentication and profiles.
    *   **`models.py`**: Defines the `Profile`, `Post`, `LikePost`, and `Followers` models.
    *   **`views.py`**: Contains the logic for handling user requests.
    *   **`urls.py`**: URL patterns for the `userauth` app.
*   **`templates/`**: HTML templates for rendering the front-end.
*   **`static/`**: Static files such as CSS and JavaScript.
