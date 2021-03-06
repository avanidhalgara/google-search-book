# Google-search-book

## Overview
React-based Google Books Search app. This SPA (Single Page Application) uses [react-router-dom]to navigate, hide and show your React components without changing the route within Express. Using helper/util functions and React lifecycle methods to query and display books based on user searches.This is a full MERN stack application allows users to save books to a database to refer to at a later date. Built with Node.js, Express and MongoDB, and React-Toastify for custom alerts. 

## Required npm packages
  - mongoose
  - axios
  - react-router-dom
  - react-toastify

## Database
Connect to a MongoDB database named googlebooks using the mongoose npm package.

- Using mongoose, create a Book schema.

- Books should have each of the following fields:

  - title - Title of the book from the Google Books API

   - authors - The books's author(s) as returned from the Google Books API

   - description - The book's description as returned from the Google Books API

  - image - The Book's thumbnail image as returned from the Google Books API

  - link - The Book's information link as returned from the Google Books API
  
  ## Technologies Implemented:
- Bootstrap
- Express
- Node.js
- React
- MongoDB
- Heroku

 [Link for Heroku Deployment](https://google-search-book1.herokuapp.com)



## Screenshot
![image](https://user-images.githubusercontent.com/65205190/90460969-b8ffaa00-e0ca-11ea-84bc-d1c8fe0623fa.png)

