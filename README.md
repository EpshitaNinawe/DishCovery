# DishCovery

## Overview

DishCovery is a recipe recommendation system that helps users find the perfect dish based on their mood, available ingredients, or even a specific dish name. The idea is simple: just tell DishCovery what you’re feeling or what you have on hand, and it will suggest dish names, necessary ingredients, and step-by-step recipes for how to make them.

Whether you’re in the mood for something comforting or want to experiment with what’s in your pantry, DishCovery makes it easy to whip up a delicious meal tailored to your tastes. By using the K-Nearest Neighbors (KNN) machine learning algorithm, it delivers suggestions that enhance your cooking experience. Plus, with an intuitive interface, navigating through your culinary options is a breeze.

---

## Features

- **Interactive Recipe Search**: Chatbot interface for searching recipes based on ingredients, mood, or dish names.
- **User Authentication**: Sign-up and login functionality to personalize the user experience.
- **Dynamic Content**: Interactive web pages with rich media content, including images and animations.
- **Contact and About Pages**: Informative pages about the application and ways to contact the developers.

---

## Technology Stack

- **Frontend**: HTML, CSS, JavaScript
- **Backend**: Django
- **Database**: SQLite (default with Django)
- **Data Handling**: Pandas
- **Machine Learning**: scikit-learn (K-Nearest Neighbors)
- **Deployment**: Django Development Server (Localhost)
- **Version Control**: GitHub

---

## Installation

1. **Clone the Repository**:
   ```bash
   git clone <repository-url>
   ```

2. **Navigate to the Project Directory**:
   ```bash
   cd DishCovery
   ```

3. **Install Dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

4. **Apply Migrations**:
   ```bash
   python manage.py migrate
   ```

5. **Run the Development Server**:
   ```bash
   python manage.py runserver
   ```

6. **Access the Application**:
   Open your web browser and navigate to `http://127.0.0.1:8000`.

---

## Project Structure

```
DishCovery/
├── manage.py             # Django's command-line utility for administrative tasks
├── recipe/               # Django app with models, views, and templates
│   ├── admin.py          # Admin interface configurations
│   ├── apps.py           # Application configuration
│   ├── models.py         # Database models
│   ├── views.py          # Request handlers
│   ├── urls.py           # URL routing
│   ├── templates/        # HTML templates for rendering web pages
│   ├── static/           # Static files (images, CSS, JavaScript)
│   └── migrations/       # Database migration files
├── userproject/          # Main project configuration
│   ├── settings.py       # Project settings
│   ├── urls.py           # Root URL configurations
│   ├── wsgi.py           # Deployment interface (WSGI)
│   └── asgi.py           # Deployment interface (ASGI)
├── food_data.csv         # Contains data for recipes
└── requirements.txt      # Python dependencies
```

---

## Data

- `food_data.csv`: Contains data for recipes.

---

## Usage

1. **Mood-Based Recipe Suggestions**: The chatbot suggests recipes based on your mood, providing the recipe name, steps, and ingredients needed.
2. **Dish Name-Based Recipe Search**: Input a dish name to get the relevant recipe details, including the recipe steps and ingredients required.
3. **Ingredient-Based Recipe Search**: Enter a list of ingredients to get recipe suggestions, with the recipe name, steps, and ingredients needed.
4. **Contact Us**: Use the contact page for inquiries or feedback.

---

## Contributing

Contributions are welcome! Feel free to fork the repository and submit a pull request.

---

## Contact

For more information, you can contact the project maintainer at:

**GitHub**: [https://github.com/EpshitaNinawe](https://github.com/EpshitaNinawe)
