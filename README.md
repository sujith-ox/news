### News Aggregator App

A simple news aggregator and display application built with **Django**. This project fetches and displays news articles, showcasing a basic, full-stack web application using Django's core features for routing, data handling, and templating.

-----

### ✨ Features

  * **News Display:** Fetches and presents news articles on the homepage.
  * **Built-in Database:** Uses Django's default SQLite database for storing articles.
  * **Intuitive UI:** A clean, responsive user interface for reading articles.
  * **Admin Panel:** Utilizes Django's powerful admin interface for easy content management.

-----

### 💻 Tech Stack

  * **Django:** The core backend framework, providing an ORM, routing, and an admin panel.
  * **SQLite:** The default, file-based database for development.
  * **HTML, CSS & JavaScript:** For the frontend templates and user interaction.

-----

### ⚙️ Getting Started

Follow these steps to get a local copy of the project up and running.

#### **1. Clone the repository**

```bash
git clone https://github.com/sujith-ox/news.git
cd news
```

#### **2. Set up the project**

First, create a virtual environment to manage dependencies:

```bash
python -m venv venv
```

Activate the environment:

  * On Windows: `venv\Scripts\activate`
  * On macOS/Linux: `source venv/bin/activate`

Next, install the required packages. If you don't have a `requirements.txt` file, you can install just Django:

```bash
pip install django
```

#### **3. Apply migrations**

Django automatically handles database setup with its migration system.

```bash
python manage.py migrate
```

#### **4. Run the development server**

```bash
python manage.py runserver
```

The application will be available at `http://localhost:8000`.

-----

### 📄 License

This project is licensed under the **MIT License**.
