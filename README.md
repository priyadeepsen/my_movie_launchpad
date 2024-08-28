<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Movie Launchpad</title>
    <style>
      body {
        font-family: Arial, sans-serif;
        margin: 20px;
      }
      h1, h2, h3, h4, h5, h6 {
        color: #333;
        margin-bottom: 10px;
      }
      .tech-stack {
        list-style: none;
        padding: 0;
        margin: 0;
      }
      .tech-stack li {
        display: inline-block;
        margin-right: 20px;
      }
      .tech-stack li img {
        width: 20px;
        height: 20px;
        vertical-align: middle;
        margin-right: 5px;
      }
      .features {
        list-style: none;
        padding: 0;
        margin: 0;
      }
      .features li {
        margin-bottom: 10px;
      }
      .features li:before {
        content: "\2713";
        font-size: 18px;
        color: #4caf50;
        margin-right: 10px;
      }
      .getting-started ol {
        list-style: decimal;
        padding: 0;
        margin: 0;
      }
      .getting-started ol li {
        margin-bottom: 10px;
      }
    </style>
  </head>
  <body>
    <h1>
      Movie Launchpad
      <img src="https://reactjs.org/logo-og.png" alt="React Logo" width="20" height="20" />
    </h1>
    <p>A React-based movie search application built with Vite and OMDB API</p>
    <h2>Tech Stack:</h2>
    <ul class="tech-stack">
      <li>
        <img src="https://reactjs.org/logo-og.png" alt="React Logo" /> React
      </li>
      <li>
        <img src="https://vitejs.dev/logo-with-shadow.png" alt="Vite Logo" /> Vite
      </li>
      <li>
        <img src="https://omdbapi.com/favicon.ico" alt="OMDB API Logo" /> OMDB API
      </li>
      <li>
        <img src="https://eslint.org/favicon.ico" alt="ESLint Logo" /> ESLint
      </li>
    </ul>
    <h2>Project Overview:</h2>
    <div>
      <p>
        Movie Launchpad is a simple movie search application that allows users
        to search for movies using the OMDB API. The application is built using
        React and Vite, with a focus on providing a fast and seamless user
        experience.
      </p>
    </div>
    <h2>Features:</h2>
    <ul class="features">
      <li>Search for movies using the OMDB API</li>
      <li>Display movie results with poster images and basic information</li>
      <li>Responsive design for mobile and desktop devices</li>
    </ul>
    <h2>Getting Started:</h2>
    <div class="getting-started">
      <ol>
        <li>
          Clone the repository: <code>git clone https://github.com/your-username/movie-launchpad.git</code>
        </li>
        <li>
          Install dependencies: <code>npm install</code> or <code>yarn install</code>
        </li>
        <li>
          Start the development server: <code>npm run dev</code> or <code>yarn dev</code>
        </li>
        <li>
          Open the application in your web browser: <code>http://localhost:3000</code>
        </li>
      </ol>
    </div>
  </body>
</html>