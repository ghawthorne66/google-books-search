# React Google Books Search

### Overview

React-based Google Books Search app. This SPA (Single Page Application) uses [`react-router-dom`]to navigate, hide and show your React components without changing the route within Express. Using helper/util functions and React lifecycle methods to query and display books based on user searches, this is a full MERN stack application allows users to save books to a database to refer to at a later date. Built with Node, Express and MongoDB, and React-Toastify for custom alerts. Toasty!

### required npm packages

`mongoose`, `axios`, `react-router-dom`, `react-toastify`

## Database

1. Connect to a MongoDB database named `googlebooks` using the mongoose npm package.

2. Using mongoose, create a Book schema.

3. Books should have each of the following fields:

* `title` - Title of the book from the Google Books API

* `authors` - The book's author(s) as returned from the Google Books API

* `description` - The book's description as returned from the Google Books API

* `image` - The Book's thumbnail image as returned from the Google Books API

* `link` - The Book's information link as returned from the Google Books API

* Example JSON:

    ```js
    {
      authors: ["Mark Twain"]
      description: "The humorist reflects on his scuffling years — silver mining in Nevada, working at a Virginia City newspaper, down and out in San Francisco, reporting for a newspaper from Hawaii, and more."

      image: "https://books.google.com/books/content/images/frontcover/-vfK1oQo9m8C?fife=w400-h600"
      link: "https://play.google.com/store/books/details?id=-vfK1oQo9m8C&source=gbs_api"
      title: "Roughing It"
    }
    ```


### Technologies Implemented

* Bootstrap
* Express
* Node.js
* React
* MongoDB
* Heroku

### Live site

* deployed: 


