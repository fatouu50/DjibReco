DjibReco

DjibReco is an AI-powered web application that recommends cafés and restaurants in Djibouti using a hybrid recommendation system (content-based + collaborative filtering).

The platform personalizes suggestions according to user preferences, ratings, and budget.

Project Overview

DjibReco aims to solve a simple problem:
How can users in Djibouti quickly find cafés and restaurants that match their tastes and budget?

The system combines:

Content-Based Filtering (cuisine type, price range, tags, location)

Collaborative Filtering (user ratings and behavior)

Hybrid Recommendation Model (weighted combination of both approaches)

The application is built with Python and Flask, using a relational database and a simple frontend interface.

Tech Stack

Backend:

Python 3

Flask

SQLAlchemy

Scikit-learn (for recommendation logic)

Database:

SQLite (development)

PostgreSQL (production-ready option)

Frontend:

HTML

CSS

Jinja2 templates

Data:

Restaurants dataset (local CSV or database entries)

User ratings

Project Structure

DjibReco/

app/
• init.py
• routes.py
• models.py
• recommender.py
• templates/
• static/

data/
• restaurants.csv

tests/

config.py
run.py
requirements.txt

Installation

Clone the repository:

git clone https://github.com/fatouu50/DjibReco.git
cd DjibReco

Create and activate a virtual environment:

python -m venv venv
source venv/bin/activate

Install dependencies:

pip install -r requirements.txt

Run the application:

python run.py
Features (Planned)

User authentication (register / login)

Add and rate restaurants

Personalized recommendations

Hybrid recommendation engine

Admin dashboard

Budget-based filtering

Restaurant search and filtering

Recommendation System

Content-Based Filtering
Uses restaurant features such as cuisine type, price range, and tags.

Collaborative Filtering
Uses user ratings to detect similar users or items.

Hybrid Model
Combines both approaches to improve accuracy and reduce cold-start issues.

Future Improvements

Deploy online

Add geolocation filtering

Improve ranking algorithm

Add real user dataset

Integrate reviews and sentiment analysis

Author

Project developed by Fatouu50
Master in Data Modeling & Artificial Intelligence
