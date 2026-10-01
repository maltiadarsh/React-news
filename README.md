# News App

A lightweight React + Vite news dashboard that shows the latest headlines from NewsAPI and lets users switch categories such as general, business, technology, sports, entertainment, health, and science.

## Features

- Category-based news navigation
- Live top-headlines feed from NewsAPI
- Responsive card-based article layout
- Article image, title, description, and external link
- Built with React and Vite

## Tech Stack

- React 19
- Vite
- JavaScript
- NewsAPI

## Prerequisites

Before running the app, make sure you have:

- Node.js 18 or newer
- npm
- A NewsAPI key from [NewsAPI](https://newsapi.org/)

## Installation

1. Install dependencies:

   ```bash
   npm install
   ```

2. Go to [NewsAPI](https://newsapi.org/) and create an account to get your API key.

3. Create a `.env` file in the project root:

   ```env
   VITE_API_KEY=your_newsapi_key_here
   ```

3. Start the development server:

   ```bash
   npm run dev
   ```

4. Open the local URL shown in the terminal (typically http://localhost:5173).

## Available Scripts

```bash
npm run dev
npm run build
npm run preview
npm run lint
```

## Project Structure

```bash
src/
  App.jsx
  main.jsx
  index.css
  Components/
    Navbar.jsx
    NewsBoard.jsx
    NewsItems.jsx
```

## Notes

- The app reads the API key from the `VITE_API_KEY` environment variable.
- Without a valid NewsAPI key, the headlines request will fail.
- The app is intended for frontend development and demonstration purposes.

## License

This project is for educational/demo use.
