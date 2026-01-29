# Favorite Movie App

A React application to discover, search, and save your favorite movies using The Movie Database (TMDb) API.

## Features

- **Browse Popular Movies** - View trending movies on the home page
- **Search Movies** - Search for any movie by title
- **Save Favorites** - Add movies to your favorites list
- **Persistent Storage** - Your favorites are saved locally
- **Responsive Design** - Works on desktop and mobile devices

## Tech Stack

- **React** - UI framework
- **The Movie Database (TMDb) API** - Movie data source
- **CSS** - Styling
- **Context API** - State management

## Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/projectbrady/FavoriteMovieApp.git
   cd FavoriteMovieApp
   ```

2. **Install dependencies:**

   ```bash
   npm install
   ```

3. **Create `.env.local` file in the root directory:**

   ```
   REACT_APP_API_KEY=your_tmdb_api_key_here
   REACT_APP_BASE_URL=https://api.themoviedb.org/3
   ```

4. **Get a TMDb API key:**
   - Visit [https://www.themoviedb.org/settings/api](https://www.themoviedb.org/settings/api)
   - Sign up for a free account
   - Request an API key

5. **Start the development server:**

   ```bash
   npm start
   ```

6. **Open your browser and navigate to:**
   ```
   http://localhost:3000
   ```

## Usage

- **Home Page** - Browse popular movies or search by title
- **Search** - Enter a movie title and click "Search"
- **Add to Favorites** - Click the ♥ button on any movie card
- **View Favorites** - Click "Favorites" in the navigation to see your saved movies

## Project Structure

```
src/
├── components/       # Reusable components
│   └── MovieCard.jsx
├── pages/           # Page components
│   ├── Home.jsx
│   └── Favorites.jsx
├── services/        # API calls
│   └── api.js
├── contexts/        # React Context
│   └── MovieContext.js
├── css/             # Stylesheets
└── App.jsx
```

## API Reference

This app uses the TMDb API. Learn more at [https://www.themoviedb.org/settings/api](https://www.themoviedb.org/settings/api)

## License

This project is open source and available under the MIT License.

## Author

Brady - [GitHub Profile](https://github.com/projectbrady)
