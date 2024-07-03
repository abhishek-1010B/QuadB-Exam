Certainly! Here is the revised document with the updated repository URL:

# MERN Ecommerce

## Description

An ecommerce store built with the MERN stack, utilizing third-party APIs. This ecommerce store enables three main different flows or implementations:

1. Buyers browse the store categories, products, and brands
2. Sellers or Merchants manage their own brand component
3. Admins manage and control the entire store components 

* Features:
  * Node provides the backend environment for this application
  * Express middleware is used to handle requests and routes
  * Mongoose schemas to model the application data
  * React for displaying UI components
  * Redux to manage the application's state
  * Redux Thunk middleware to handle asynchronous redux actions

## Quickstart Guide

To run this project locally, you can use Docker Compose provided in the repository. Here is a guide on how to run this project locally using Docker Compose:

Clone the repository:
```
$ git clone https://github.com/abhishek-1010B/QuadB-Exam.git
```

Edit the `docker-compose.yml` file and update the values for `MONGO_URI` and `JWT_SECRET`.

Then simply start Docker Compose:
```
$ docker compose -f docker-compose.yml up
```

## Database Seed

* The seed command will create an admin user in the database.
* The email and password are passed with the command as arguments.
* Use the below command, replacing brackets with your email and password. 
* For more information, see the code [here](server/utils/seed.js).

```
npm run seed:db [email-***@****.com] [password-******] // This is just an example.
```

## Demo

This application is deployed on Vercel. Please check it out :smile: [here](https://mern-store-gold.vercel.app).

See the admin dashboard [demo](https://mernstore-bucket.s3.us-east-2.amazonaws.com/admin.mp4).

## Install

Some basic Git commands are:

```
$ git clone https://github.com/abhishek-1010B/QuadB-Exam.git
$ cd project
$ npm install
```

## Start development

```
$ npm run dev
```

## Simple build for production

```
$ npm run build
```

## Run build for production

```
$ npm start
```

## Languages & Tools

- [Node](https://nodejs.org/en/)
- [Express](https://expressjs.com/)
- [Mongoose](https://mongoosejs.com/)
- [React](https://reactjs.org/)
- [Webpack](https://webpack.js.org/)

### Code Formatter

- Add a `.vscode` directory.
- Create a file `settings.json` inside `.vscode`.
- Install Prettier - Code formatter in VSCode.
- Add the following snippet:  

```json
{
  "editor.formatOnSave": true,
  "prettier.singleQuote": true,
  "prettier.arrowParens": "avoid",
  "prettier.jsxSingleQuote": true,
  "prettier.trailingComma": "none",
  "javascript.preferences.quoteStyle": "single"
}
```

Feel free to ask if you need further adjustments or additions!