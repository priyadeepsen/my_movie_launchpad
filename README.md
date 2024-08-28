<!DOCTYPE html>
<html>
<head>
	<title>Movie Launchpad</title>
	<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css" />
	<style>
		body {
			font-family: Arial, sans-serif;
			margin: 20px;
		}
		.header {
			background-color: #f0f0f0;
			padding: 20px;
			text-align: center;
		}
		.icon {
			font-size: 24px;
			margin: 10px;
		}
		.table-of-contents {
			list-style: none;
			padding: 0;
			margin: 0;
		}
		.table-of-contents li {
			margin-bottom: 10px;
		}
		.table-of-contents a {
			text-decoration: none;
			color: #337ab7;
		}
		.table-of-contents a:hover {
			color: #23527c;
		}
	</style>
</head>
<body>
	<div class="header">
		<h1>Movie Launchpad</h1>
		<i class="fas fa-film icon"></i>
	</div>
	<div class="content">
		<h2>Table of Contents</h2>
		<ul class="table-of-contents">
			<li><a href="#features">Features</a></li>
			<li><a href="#installation">Installation</a></li>
			<li><a href="#usage">Usage</a></li>
			<li><a href="#api-documentation">API Documentation</a></li>
		</ul>
		<h2 id="features">Features</h2>
		<ul>
			<li>Search for movies by title</li>
			<li>Display movie results in a grid layout</li>
			<li>Click on a movie to view more details</li>
		</ul>
		<h2 id="installation">Installation</h2>
		<ol>
			<li>Clone the repository: <code>git clone https://github.com/your-username/movie-launchpad.git</code></li>
			<li>Install the dependencies: <code>npm install</code></li>
			<li>Start the app: <code>npm start</code></li>
		</ol>
		<h2 id="usage">Usage</h2>
		<ol>
			<li>Open the app in your web browser: <code>http://localhost:3000</code></li>
			<li>Enter a movie title in the search bar</li>
			<li>Click the search icon to retrieve the results</li>
			<li>Click on a movie to view more details</li>
		</ol>
		<h2 id="api-documentation">API Documentation</h2>
		<p>The app uses the OMDB API to retrieve movie data. The API endpoint is: <code>http://www.omdbapi.com?apikey=7efd5516</code></p>
	</div>
</body>
</html>