🎥 Movie Search App
A simple web application to search for movies and save your favorites locally.
Features

Search movies using the OMDB API
View movie details including title, year, and poster
Add movies to favorites
Remove movies from favorites
Favorites persist in local storage between sessions

Live Demo
You can try the live demo here
Getting Started
Prerequisites

A modern web browser
An internet connection

Installation

Clone the repository:
Copygit clone https://github.com/yourusername/movie-search-app.git

Navigate to the project directory:
Copycd movie-search-app

Open index.html in your browser or use a local server.

Using Your Own API Key
The app currently uses a shared OMDB API key. For your own projects, it's recommended to get your own API key:

Visit OMDB API to get a free API key
Replace the API key in script.js:
javascriptCopyconst API_URL = "https://www.omdbapi.com/?apikey=YOUR_API_KEY";


Usage

Enter a movie title in the search box
Click "Search" or press Enter
Browse the results
Click "Add to Favorites" to save movies you like
View your favorites in the Favorites section
Click "Remove" to remove a movie from favorites

Limitations

Favorites are stored in your browser's local storage, so they:

Are only available on the device where you saved them
Will be lost if you clear your browser data
Cannot be shared between users



Technologies Used

HTML5
CSS3
JavaScript (ES6+)
OMDB API
LocalStorage API

License
This project is licensed under the MIT License - see the LICENSE file for details.
Acknowledgments

Movie data provided by OMDB API
Made by Shashi
