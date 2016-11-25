# Full-stack Web Developer - Challenge I

The challenge is to create a work Node.js website, with the ability to create, edit and view MongoDB database records (a basic CRUD application).

## Requirements

### Part 1

- Install the latest version of Node.js (and npm) on your computer (or for bonus points use https://github.com/smebberson/vagrant-nodejs).
- Create a very basic website using the [Express framework](http://expressjs.com/).
- It should have a very basic homepage.

### Part 2

- Install MongoDB on your computer (or the Vagrant environment).
- Add GET and POST routes which allows you to create a record in the database.
- Add a GET route which allows you to view these records from the database.
- Add a GET and POST route which allows you to edit a record in the database.
- Add a DELETE route which allows you to delete a record from the database.
- All record view, create, edit and delete routes must be protected by a custom middleware that will return a HTTP status of 404, unless a cookie called 'allowed' has a value of 'yes'.
- Set it up on Heroku so we can preview the working version of your code. Here is a nice [guide to getting started with Node.js on Heroku](https://devcenter.heroku.com/articles/getting-started-with-nodejs#introduction).

## Rules

- You must use Mongoose to manage your MongoDB dataset. The dataset can be anything, but keep it simple (one or two properties).
- You must use Git and GitHub.
- Please send us a link to your GitHub page where we can review your code.

