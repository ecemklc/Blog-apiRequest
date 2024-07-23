# Blog with HTTP Request

![blog-httpRequest](https://github.com/user-attachments/assets/06c6fc28-971a-4f10-9f50-6ff3b64db3e7)


This is a simple blog project demonstrating the use of HTTP requests to fetch data from an API and render it on a webpage.

## Project Structure

- `index.html`: The main page that displays a list of blog posts.
- `blog.html`: The page that displays a single blog post in detail.
- `app.js`: The JavaScript file that handles fetching and displaying the list of blog posts.
- `blog.js`: The JavaScript file that handles fetching and displaying a single blog post.
- `style.css`: Custom CSS for additional styling (if any).

## Features

- Fetches data from `https://jsonplaceholder.typicode.com/posts` using HTTP requests.
- Displays a list of blog posts with a title, body, and random image on the main page.
- Each blog post card includes a "Read More" button that opens a detailed view of the post in a new tab.
- Uses Bootstrap for responsive and modern styling.

## How It Works

### Fetching Data

The data is fetched using the `XMLHttpRequest` object. In `app.js`, the `CardManager` class is responsible for making the HTTP request to fetch all blog posts and rendering them on the main page.
In blog.js, the script fetches data for a specific blog post based on the id parameter in the URL and displays it on the blog.html page.

## Getting Started
To get started with this project, simply clone the repository and open index.html in your browser.
