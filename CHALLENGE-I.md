# Full-stack Web Developer - Challenge I

The challenge is to create a very simply, yet working Node.js website, with the ability to create, edit and view MongoDB database records (a basic CRUD application).

We'd like you to limit development time spent on the project to three hours.

## Requirements

### Part 1

- Install the latest version of Node.js (and npm) on your computer.
- Create a very basic website using the [Express framework](http://expressjs.com/).
- It should have a very basic homepage.

### Part 2

- Acquire access to a MongoDB instance, at [MongoDB Atlas](https://www.mongodb.com/) (free tier).
- Update your Node.js/Express application to manage database records:
  - Add a GET route which allows you to view records from the database.
  - Add a POST route which allows you to create a record in the database.
  - Add a PUT route which allows you to edit a record in the database.
  - Add a DELETE route which allows you to delete a record from the database.
- All record CRUD routes must be protected by a custom middleware that will return a HTTP status of 404, unless a cookie called 'allowed' has a value of 'yes'.

### Part 3

- Set it up on Heroku so we can preview the working version of your code. Here is a nice [guide to getting started with Node.js on Heroku](https://devcenter.heroku.com/articles/getting-started-with-nodejs#introduction).

## Rules

- You must use Mongoose to manage your MongoDB dataset. The dataset can be anything, but keep it simple (one or two properties at most).
- You must use Git and GitHub.
- Please send us a link to your GitHub repository where we can review your code.
