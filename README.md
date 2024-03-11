# AI Blog Generator Project

 The AI Blog Generator is a Django-based web application designed to generate a blog post 
 from a YouTube video link using OpenAI's language model. This project integrates user
 registration and login functionalities, providing a personalized experience for content generation.

## Features

- **User Registration:** Enable users to create accounts for personalized access.
- **User Login:** Securely log in to the application with registered accounts.
- **Blog Generation:** Leverage OpenAI's language model to generate blog articles based on YouTube videos.
- **View Past Generated Blogs:** Users can view a history of previously generated blog articles.

## Technologies Used

- **Python**
- **Django**
- **PostgreSQL**
- **HTML/JavaScript**
- **Tailwind CSS**
- **OpenAI**
- **Assembly AI**

### Prerequisites

- Python 
- Django
- OpenAI API Key
- AssemblyAI API Key
- Postgre database

  ### Installation and Run Server

1. **Clone the repository:**

    ```bash
    git clone https://github.com/Omri-Ma/ai_blog_app.git
    ```

2. **Navigate to the project directory:**

    ```bash
    cd ai_blog_app
    ```

3. **Install dependencies:**

    ```bash
    pip install -r requirements.txt
    ```

4. **Configure OpenAI API Key:**

-- Go to views.py and inset your key instead of "Insert your OpenAI key here"

5. **Configure Assembly AI API Key:**

-- Go to views.py and inset your key instead of "Insert your Assembly AI key here"

6. **Configure PostgreSQL Database:**

-- Update the database settings in settings.py:

7. **Perform database migrations:**
   ```bash
    python manage.py migrate
    ```
8. **Run the development server**
   ```bash
    python manage.py runserver
   
9. **Visit http://localhost:8000 in your web browser to access the application.**


## Screenshots:
-- Login and blog generation out of a YouTube link:

https://github.com/Omri-Ma/ai_blog_app/assets/60123518/40299f4d-219e-4357-87c4-7eefd53abfb7

-- History of generated blogs for the user:

![blogs-list](https://github.com/Omri-Ma/ai_blog_app/assets/60123518/09ce2f85-67c0-4cfd-83b9-a2001d1e393b)

-- Blog details:

![blog-details](https://github.com/Omri-Ma/ai_blog_app/assets/60123518/9c995491-e0e3-4035-bd35-031bb746d6eb)


    ```
