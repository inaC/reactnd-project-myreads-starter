# MyReads Project

This project corresponds to the first Udacity's React Fundamentals course. It used the provided starter template as a starting point.

## TL;DR

In order to run the project:

* install all project dependencies with `npm install`
* start the development server with `npm start`

## What You're Getting
```bash
├── CONTRIBUTING.md
├── README.md - This file.
├── SEARCH_TERMS.md # The whitelisted short collection of available search terms for you to use with your app.
├── package.json # npm package manager file. It's unlikely that you'll need to modify this.
├── public
│   ├── favicon.ico # React Icon, You may change if you wish.
│   └── index.html # DO NOT MODIFY
└── src
    ├── App.css # Styles for your app. Feel free to customize this as you desire.
    ├── App.js # This is the root of your app. Contains static HTML right now.
    ├── App.test.js # Used for testing. Provided with Create React App. Testing is encouraged, but not required.
    ├── Book.js # Component modeling a book.
    ├── BooksAPI.js # A JavaScript API for the provided Udacity backend. Instructions for the methods are below.
    ├── icons # Helpful images for your app. Use at your discretion.
    │   ├── add.svg
    │   ├── arrow-back.svg
    │   ├── arrow-drop-down.svg
    │   └── image_not_found.svg
    ├── index.css # Global styles. You probably won't need to change anything here.
    ├── ListBooks.js # Component modeling a the list of books.
    ├── SearchBooks.js # Component modeling the search book page.
    ├── SearchBooksResults.js # Component used in SearchBooks in order to show the books retrieved from the provided API.
    └── Shelf.js # Component used in ListBooks in order to separate the books by their associated shelves.
```

## Important

The backend API uses a fixed set of cached search results and is limited to a particular set of search terms, which can be found in [SEARCH_TERMS.md](SEARCH_TERMS.md). That list of terms are the _only_ terms that will work with the backend, so don't be surprised if your searches for Basket Weaving or Bubble Wrap don't come back with any results.

## Create React App

This project was bootstrapped with [Create React App](https://github.com/facebookincubator/create-react-app). You can find more information on how to perform common tasks [here](https://github.com/facebookincubator/create-react-app/blob/master/packages/react-scripts/template/README.md).

## Resources Used
* Not found book cover [icon](https://pixabay.com/en/false-error-missing-absent-x-red-2061132/)
* At the time this document was last updated, such icon has been defined as:
    CC0 Creative Commons
    Free for commercial use 
    No attribution required
