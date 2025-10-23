# Module 1: Installation and Project Creation - Completed Assignment

This document outlines the steps taken to complete the assignment for Module 1, which involved creating three independent Django projects, setting up virtual environments, installing Django, applying migrations, and starting development servers for each.

## Project Directories

The projects were created in the following directories:

1.  `/Users/bryson/Desktop/Django_school_work/django_clas_work_1/module-1-django-basics-Brysonflowers/projects/yet-another-pokedex`
2.  `/Users/bryson/Desktop/Django_school_work/django_clas_work_1/module-1-django-basics-Brysonflowers/projects/facebook-clone`
3.  `/Users/bryson/Desktop/Django_school_work/django_clas_work_1/module-1-django-basics-Brysonflowers/projects/fake-movie-database`

## Commands Executed

Below are the exact commands executed for each project.

### Project 1: `yet-another-pokedex`

1.  **Create Project Directory:**
    ```bash
    mkdir -p /Users/bryson/Desktop/Django_school_work/django_clas_work_1/module-1-django-basics-Brysonflowers/projects/yet-another-pokedex
    ```

2.  **Create Virtual Environment:**
    ```bash
    python3 -m venv /Users/bryson/Desktop/Django_school_work/django_clas_work_1/module-1-django-basics-Brysonflowers/projects/yet-another-pokedex/.venv
    ```

3.  **Install Django:**
    ```bash
    source /Users/bryson/Desktop/Django_school_work/django_clas_work_1/module-1-django-basics-Brysonflowers/projects/yet-another-pokedex/.venv/bin/activate && pip install django
    ```

4.  **Start Django Project:**
    ```bash
    /Users/bryson/Desktop/Django_school_work/django_clas_work_1/module-1-django-basics-Brysonflowers/projects/yet-another-pokedex/.venv/bin/django-admin startproject yet_another_pokedex /Users/bryson/Desktop/Django_school_work/django_clas_work_1/module-1-django-basics-Brysonflowers/projects/yet-another-pokedex
    ```

5.  **Apply Initial Migrations:**
    ```bash
    /Users/bryson/Desktop/Django_school_work/django_clas_work_1/module-1-django-basics-Brysonflowers/projects/yet-another-pokedex/.venv/bin/python /Users/bryson/Desktop/Django_school_work/django_clas_work_1/module-1-django-basics-Brysonflowers/projects/yet-another-pokedex/manage.py migrate
    ```

6.  **Run Development Server:**
    ```bash
    cd /Users/bryson/Desktop/Django_school_work/django_clas_work_1/module-1-django-basics-Brysonflowers/projects/yet-another-pokedex && /Users/bryson/Desktop/Django_school_work/django_clas_work_1/module-1-django-basics-Brysonflowers/projects/yet-another-pokedex/.venv/bin/python manage.py runserver &
    ```

### Project 2: `facebook-clone`

1.  **Create Project Directory:**
    ```bash
    mkdir -p /Users/bryson/Desktop/Django_school_work/django_clas_work_1/module-1-django-basics-Brysonflowers/projects/facebook-clone
    ```

2.  **Create Virtual Environment:**
    ```bash
    python3 -m venv /Users/bryson/Desktop/Django_school_work/django_clas_work_1/module-1-django-basics-Brysonflowers/projects/facebook-clone/.venv
    ```

3.  **Install Django:**
    ```bash
    source /Users/bryson/Desktop/Django_school_work/django_clas_work_1/module-1-django-basics-Brysonflowers/projects/facebook-clone/.venv/bin/activate && pip install django
    ```

4.  **Start Django Project:**
    ```bash
    /Users/bryson/Desktop/Django_school_work/django_clas_work_1/module-1-django-basics-Brysonflowers/projects/facebook-clone/.venv/bin/django-admin startproject facebook_clone /Users/bryson/Desktop/Django_school_work/django_clas_work_1/module-1-django-basics-Brysonflowers/projects/facebook-clone
    ```

5.  **Apply Initial Migrations:**
    ```bash
    /Users/bryson/Desktop/Django_school_work/django_clas_work_1/module-1-django-basics-Brysonflowers/projects/facebook-clone/.venv/bin/python /Users/bryson/Desktop/Django_school_work/django_clas_work_1/module-1-django-basics-Brysonflowers/projects/facebook-clone/manage.py migrate
    ```

6.  **Run Development Server:**
    ```bash
    cd /Users/bryson/Desktop/Django_school_work/django_clas_work_1/module-1-django-basics-Brysonflowers/projects/facebook-clone && /Users/bryson/Desktop/Django_school_work/django_clas_work_1/module-1-django-basics-Brysonflowers/projects/facebook-clone/.venv/bin/python manage.py runserver &
    ```

### Project 3: `fake-movie-database`

1.  **Create Project Directory:**
    ```bash
    mkdir -p /Users/bryson/Desktop/Django_school_work/django_clas_work_1/module-1-django-basics-Brysonflowers/projects/fake-movie-database
    ```

2.  **Create Virtual Environment:**
    ```bash
    python3 -m venv /Users/bryson/Desktop/Django_school_work/django_clas_work_1/module-1-django-basics-Brysonflowers/projects/fake-movie-database/.venv
    ```

3.  **Install Django:**
    ```bash
    source /Users/bryson/Desktop/Django_school_work/django_clas_work_1/module-1-django-basics-Brysonflowers/projects/fake-movie-database/.venv/bin/activate && pip install django
    ```

4.  **Start Django Project:**
    ```bash
    /Users/bryson/Desktop/Django_school_work/django_clas_work_1/module-1-django-basics-Brysonflowers/projects/fake-movie-database/.venv/bin/django-admin startproject fake_movie_database /Users/bryson/Desktop/Django_school_work/django_clas_work_1/module-1-django-basics-Brysonflowers/projects/fake-movie-database
    ```

5.  **Apply Initial Migrations:**
    ```bash
    /Users/bryson/Desktop/Django_school_work/django_clas_work_1/module-1-django-basics-Brysonflowers/projects/fake-movie-database/.venv/bin/python /Users/bryson/Desktop/Django_school_work/django_clas_work_1/module-1-django-basics-Brysonflowers/projects/fake-movie-database/manage.py migrate
    ```

6.  **Run Development Server:**
    ```bash
    cd /Users/bryson/Desktop/Django_school_work/django_clas_work_1/module-1-django-basics-Brysonflowers/projects/fake-movie-database && /Users/bryson/Desktop/Django_school_work/django_clas_work_1/module-1-django-basics-Brysonflowers/projects/fake-movie-database/.venv/bin/python manage.py runserver &
    ```

## Verification

The development servers for all three projects are running in the background. To verify, you can visit `http://127.0.0.1:8000` in your browser for each project. Note that since all projects are running on the same port, you would need to stop one to view another, or configure them to run on different ports.

This completes the assignment.