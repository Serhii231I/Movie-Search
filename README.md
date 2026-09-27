# React + Vite

# 🎬 Movie Search

A responsive movie search application built with React and JavaScript.

The application allows users to discover trending movies, search for movies by title, view detailed movie information, explore cast members, and read user reviews.

## 🚀 Live Demo

https://moviesearch-seven-wheat.vercel.app/

## 📸 Features

- 🔎 Search movies by title
- 🔥 Browse trending movies
- 🎬 View detailed movie information
- 👥 Explore movie cast
- 💬 Read movie reviews
- 🧭 Client-side routing
- ⚡ Lazy loading of pages and components
- ⏳ Loading states
- ❌ 404 Not Found page
- 📱 Responsive user interface
- 🌐 REST API integration with TMDB

## 🛠️ Technologies

- React
- JavaScript
- React Router
- Axios
- Formik
- Vite
- CSS Modules
- clsx
- React Loader Spinner
- REST API
- TMDB API
- Git
- GitHub
- Vercel

## 🏗️ Application Structure

The application is organized into reusable React components and separate pages.

Main application sections include:

- Home page
- Movie search page
- Movie details page
- Movie cast
- Movie reviews
- Navigation
- 404 Not Found page
- API service layer

## 🧭 Routing

React Router is used for client-side navigation.

Available routes include:

- `/` — Home page with trending movies
- `/movies` — Movie search
- `/movies/:movieId` — Movie details
- `/movies/:movieId/cast` — Movie cast
- `/movies/:movieId/reviews` — Movie reviews

## 🌐 API Integration

The application uses the TMDB REST API to retrieve movie data.

Axios is used to communicate with the API and handle asynchronous HTTP requests.

The application retrieves:

- Trending movies
- Movie details
- Movie cast
- Movie reviews
- Search results

## ⚡ Performance

React lazy loading is used for pages and selected components.

`React.lazy()` and `Suspense` help load application sections only when they are required.

This reduces the initial amount of JavaScript that needs to be loaded by the browser.

## 📝 Forms

Formik is used to handle the movie search form.

The application processes the user's search query and sends the request to the TMDB API.

## 🎯 Project Goals

The project was developed to gain practical experience with modern React development and working with external REST APIs.

Through this project I practiced:

- Building reusable React components
- React hooks
- Client-side routing
- Dynamic routes
- REST API integration
- Axios
- Asynchronous JavaScript
- Lazy loading
- Loading states
- Form handling
- Responsive UI development
- Error and empty states
- Git and GitHub workflow
- Frontend deployment with Vercel

## 📦 Installation

Clone the repository:

```bash
git clone https://github.com/Serhii231I/Movie-Search.git
```
