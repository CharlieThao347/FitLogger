# Workout Tracker
A Django web application to create workouts, log said workouts, and track exercise progress.

## Description
The Workout Tracker is a Django-based web application that allows users to log workouts and monitor exercise progress. It includes features such as creating workout routines, logging said routines, and viewing exercise progress.

## Built With
- ![Django](https://img.shields.io/badge/Django-3.0.9-blue) **[Django](https://www.djangoproject.com/)** - Web framework used for backend development.
- ![Python](https://img.shields.io/badge/Python-3.8.10-blue) **[Python](https://www.python.org/)** - Programming language used for backend development.
- ![SQLite](https://img.shields.io/badge/SQLite-3.37.2-lightgrey) **[SQLite](https://www.sqlite.org/)** - Database used for storing data.
- ![Bootstrap](https://img.shields.io/badge/Bootstrap-4.5.3-blue) **[Bootstrap](https://getbootstrap.com/)** - Frontend framework for responsive design.
- ![JavaScript](https://img.shields.io/badge/JavaScript-ES6-blue) **[JavaScript](https://www.javascript.com/)** - Language used for frontend interactivity and dynamic content.
- ![jQuery](https://img.shields.io/badge/jQuery-3.5.1-blue) **[jQuery](https://jquery.com/)** - JavaScript library used for DOM manipulation.
- ![Chartist.js](https://img.shields.io/badge/Chartist-0.11.0-yellow) **[Chartist.js](https://gionkunz.github.io/chartist-js/)** - Library used to render clean and dynamic charts.

## Prerequisites
You can run this project through Docker (recommended for easy setup) or run it natively on your machine. Before you begin, ensure you have met the following requirements:  

If running through Docker:

**Docker**: You can download Docker from [docker.com](https://www.docker.com/get-started/).

Otherwise, if running natively on your machine:

**Python**: (3.8.10 or higher) - You can download Python from [python.org](https://www.python.org/downloads/).

## Installation

### Running through Docker 
### 1. Clone the repository
```bash
git clone https://github.com/yourusername/workout-tracker.git
cd workout-tracker
```

### 2. Build the Docker image by running the following command in your project directory:
```
docker build -t workout_tracker .
```

### 3. Run the Docker container:
```
docker run -p 80:80 workout_tracker
```

### 4. Open a browser and navigate to:
```
http://localhost:80
```
  
### Running it natively on your machine
### 1. Clone the repository
```bash
git clone https://github.com/yourusername/workout-tracker.git
cd workout-tracker
```

### 2. Install dependencies
```
pip install -r requirements.txt
```

### 3. Set up the database
```
python manage.py migrate
```

### 4. Run the development server
```
python manage.py runserver
```

### 5. Open a browser and navigate to:
```
http://127.0.0.1:8000
```

### Usage
Login/Sign Up: You can log in or create a new account via the landing page.  
  
Creating Workouts: After logging in, go to the "Home" page where you can create and log your workout routines. 
  
Viewing Past Workouts: Go to the "Completed Workouts" page to view your previous workouts  
  
View Progress: Go to the "My Progress" page to track and view progress over time for an exercise.




