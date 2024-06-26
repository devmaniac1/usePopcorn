# usePopcorn

usePopcorn is a React application that allows users to search for movies and add them to their watched list along with ratings. It utilizes the OMDB API to fetch movie data and provides a user-friendly interface to interact with the movies.

## Features

- 🔎Search Movies: Users can search for movies by entering keywords in the search bar. The application dynamically displays search results as the user types.
- ✔View Movie Details: Clicking on a movie from the search results displays detailed information about the selected movie, including its plot, cast, director, IMDb rating, and more.
- ➕Add to Watched List: Users can add movies to their watched list along with their own ratings. Once added, the movie appears in the watched list with the user's rating.
- ⭐Watched Movies Summary: The application provides a summary of the user's watched movies, including the total number of movies watched, average IMDb rating, average user rating, and average runtime.
- ❌Delete from Watched List: Users can remove movies from their watched list if they no longer wish to track them.

## Technologies Used

React: The frontend of the application is built using React, a JavaScript library for building user interfaces.
OMDB API: The Open Movie Database (OMDB) API is used to fetch movie information, including details such as title, plot, cast, and ratings.
LocalStorage: LocalStorage is utilized to persist the user's watched list across browser sessions.

## Usage

To use the application, simply enter keywords in the search bar to search for movies. Click on a movie from the search results to view its details and optionally add it to your watched list with a rating. The watched list can be accessed by clicking on the toggle button. Movies can be removed from the watched list by clicking the delete button next to each movie.

## Installation

To run the application locally, follow these steps:

Clone the repository to your local machine.
Navigate to the project directory and run npm install to install dependencies.
Run npm start to start the development server.
