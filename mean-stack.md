# Full-stack Engineer Exercise

The goal of this exercise is to:

1. Write a simple REST API server in Node.js
2. Consume the output of the API
3. Create an Angular web application to render the data in a readable, usable manner

## Introduction

This exercise is to see how comfortable you are working with a MEAN stack. You will have to implement a simple API (back-end) and also a simple Angular application (front-end).

## The API

The goal is to create a simple restful API thats supports CRUD operations. The API should model a book resource and therefore be able to list all books, add a new book, update a book and delete a book. The API should follow restful principles and therefore use HTTP verb methods to implement the CRUD operations. (Ex: GET /api/books - list books, PUT /api/books/:id - update a book).

Also, for persistence you should use a MongoDB database.

Each book should have at least the following properties:

- `id`: (string) a unique id
- `name`: (string) book name - may not be unique but will always be valued
- `author`: (string) the author of the book
- `genre`: (string) the genre of the book (ex: romance, sci-fi)
- `isbn`: (number) the ISBN of the book

## Angular web application

The goal is to create a front-end web application in AngularJs. The web app should consume the Node.js REST API and render the data in a readable format. It should have views to show all books, create a new book, update an existing book, and delete a book.

## Instructions

You have 5 days to complete this exercise. Use any additional tools / frameworks that you like.

You can either:

- Implement your solution locally, in which case you should email a zip file with a standalone, working solution when you're finished, or
- Upload your project to Github (or other scm) and email us the link to your repository.

Feel free to use any reference materials you may need, but please do not ask anyone for help.
