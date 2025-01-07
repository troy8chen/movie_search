# MovieSearch 🎬

## Overview
MovieSearch is a dynamic web application that leverages the TMDB API to display the latest movies, enable movie searches, and allow users to create a personalized favorites list.

*Original Tutorial Credit: YouTube Tutorial - Build a Movie Search App in React*
["Build a Movie Search App in React"](https://www.youtube.com/watch?v=G6D9cBaLViA).

## Features

🔍 Search latest movies
❤️ Add/Remove movies to favorites
💾 Persistent favorites storage
🌐 Responsive design

## Technologies

- [React](https://reactjs.org/)
- [React Router](https://reactrouter.com/) 
- [Context API](https://reactjs.org/docs/context.html)
- [TMDB API](https://www.themoviedb.org/documentation/api)

## Installation

1. Clone the repository
```bash
https://github.com/troy8chen/movie_search.git
```

2. Run npm install

3. Create .env file with TMDB API key

4. Run npm start

## Environment Variables

```bash
REACT_APP_TMDB_API_KEY=your_tmdb_api_key
```

## Project Structure

```bash
text
src/
├── components/
├── contexts/
├── css/
├── pages/
├── services/
├── App.jsx
└── main.js
```

## API Reference

    Fetch Popular Movies: getPopularMovies()
    Search Movies: searchMovies(query)

## Contributing
Contributions are welcome! Please submit pull requests.

## License
This project is licensed under the [MIT License](https://opensource.org/licenses/MIT)
