# 🎬 Movie Explorer

**Movie Explorer** is a React-based application that allows users to browse and search. It offers a seamless, multi-page experience with state management, routing, and an intuitive UI.

## 🚀 Features

### Core Features
- **Movie Search:** Quickly search for movies and display the results dynamically.
- **Movie Details Page:** View detailed information, including title, release date, and ratings.
- **Favorites:** Save and manage your favorite movies on a dedicated page.
- **Dynamic Routing:** Smooth navigation between Home, Movie Details, and Favorites pages.
- **Light/Dark Mode:** Switch themes for a personalized experience.

### Bonus Features
- **API Integration:** Fetch real-time movie data using the OMDb API (or TMDB API).
- **Pagination:** Load more movies seamlessly for better user experience.
- **Error Handling:** Friendly messages for API errors or unexpected issues.

## 🛠️ Tech Stack
- **Frontend Framework:** React
- **State Management:** useState (local state), useContext (global state)
- **Routing:** React Router DOM
- **HTTP Requests:** Axios for API integration
- **Styling:** CSS for responsive and modern UI design

## 🗂️ Project Structure
```plaintext
src/
├── components/          # Reusable components (MovieList, MovieItem, SearchBar, etc.)
├── pages/               # Pages (Home, MovieDetails, Favorites)
├── context/             # Global state management with useContext
├── hooks/               # Custom React hooks (if any)
├── services/            # API services for fetching data
├── styles/              # CSS files for styling
├── App.js               # Main component with routing setup
└── index.js             # Entry point
```

## Getting Started
### Prerequisites
- Node.js and npm installed on your system.
### Installation
1. Clone the repository
2. Install dependencies: npm install
3. Create a .env file in the root directory and add your API key.
4. Start the development server: npm start

## 📚 Usage
- Search for Movies: Enter a movie name in the search bar and see the results populate dynamically.
- View Movie Details: Click on a movie to view more details on a dedicated page.
- Manage Favorites: Mark movies as favorites and access them from the Favorites page.

# Author
- **Kainat Umar** - *Developer of this React Based Movie Explorer Application*
