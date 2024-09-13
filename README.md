# REACT-GAME-HUB

**REACT-GAME-HUB** is a game discovery web application built using **Vite**, **React**, and **TypeScript**, styled with **Chakra UI**, and integrated with the **RAWG API** to fetch game data. The app allows users to browse a wide selection of games, filter them by genre and platform, sort them by various criteria, and search for specific games. Users can also view detailed descriptions of games, including trailers and screenshots. The app provides both dark and light theme modes for a better user experience.

## Features

- **Browse Games**: View a list of games fetched from the RAWG API.
- **Filter Games**:
  - By genre (e.g., action, adventure, RPG, etc.)
  - By platform (e.g., PlayStation, Xbox, PC, etc.)
- **Sort Games**: Sort games by criteria like release date, popularity, and rating.
- **Search Games**: Search for games by title.
- **Game Details**: Click on a game to view detailed information.
- **Dark/Light Themes**: Switch between dark and light modes for the user interface.

## Technologies Used

- **Vite**: Fast build tool optimized for modern web development.
- **React**: Frontend library for building interactive user interfaces.
- **TypeScript**: Strongly typed programming language that builds on JavaScript.
- **Chakra UI**: Component library for building accessible, responsive, and customizable UI components.
- **RAWG API**: External API used to fetch game data, including game information, genres, platforms, trailers, and screenshots.

## Installation

To set up and run the project locally, follow these steps:

1. **Clone the repository**:

   ```bash
   git clone https://github.com/bohdanadev/react-game-hub.git
   cd react-game-hub
   ```

2. **Install dependencies**:

   ```bash
   npm install
   ```

3. **Get RAWG API Key**:

   - Visit the [RAWG API website](https://rawg.io/apidocs) to obtain your API key. You'll have to create an account first.
   - Rename `.env.example` file to `.env` and add your API key:
     ```bash
     VITE_API_KEY=your_api_key_here
     ```

4. **Run the development server**:

   ```bash
   npm run dev
   ```

5. **Build the project for production**:
   ```bash
   npm run build
   ```

## Usage

- **Filtering**: Select a genre and/or platform to narrow down the list of games.
- **Sorting**: Use the sort dropdown to sort games by popularity, release date, rating, etc.
- **Searching**: Use the search bar to find specific games by title.
- **Game Details**: Click on a game's name to view its description, attributes, trailer, and screenshots.
- **Theme Toggle**: Switch between dark and light mode using the theme toggle button.
