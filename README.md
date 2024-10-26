# Movie-Watchlist

A Flask web application that allows users to store, rate, and review movies they've watched or plan to watch. The app features user authentication, dark and light themes, and a user-friendly design.

## Project Overview
This project is a movie watchlist application that enables users to:

- Add movies they want to watch or have watched with detailed information.
- Rate movies on a 0-5 scale.
- Switch between light and dark modes.
- Sign up and log in securely using hashed passwords.
- Optionally enhance their experience with features such as user comments or public profiles.  

The app uses WTForms to manage form creation and validation, ensuring a secure and robust user experience.

## Features
- User Authentication: Sign-up and login functionality including secure password hashing.
- Watchlist Management: Add, view, and edit movies, with fields for title, director, year, cast, and more.
- Movie Rating: Clickable rating stars for each movie, allowing users to rate movies from 0 to 5.
- Last Watched: A "Last Watched" date that updates to the current date on click.
- Dark/Light Mode Toggle: Users can toggle between light and dark modes, with CSS variables for efficient styling.
- Responsive Design: Adjusts for mobile, tablet, and desktop viewing using responsive CSS.

## Installation
1. Clone the repository:
```
git clone [text](https://github.com/kiminzajnr/Movie-Watchlist.git)
cd Movie-Watchlist
```
2. Set up a virtual environment:
```
python3 -m venv venv
source venv/bin/activate   # On Windows use 'venv\Scripts\activate'
```
3. Install dependencies:
```
pip install -r requirements.txt
```
4. Configure environment variables:
- Add MongoDB URI and secret key to a .env file.
- Set up .flaskenv with:
```
FLASK_APP=movie_library
FLASK_ENV=development
```
5. Run the application:
```
flask run
```

## Usage
-vUser Signup and Login: Use the signup form to create an account with a password which will be securely hashed and stored.
- Adding Movies: Add new movies with a title, director, and year, and edit them to add more details like cast and rating.
- Toggle Dark Mode: Click the toggle in the navbar to switch between light and dark modes.
