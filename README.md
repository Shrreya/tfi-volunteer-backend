# Parse Server & Dashboard

A Node + Express API server with a MongoDB database built using [Parse Server](https://github.com/parse-community/parse-server) with a dashboard to manage apps. </br>
(Web app to create &amp; discover volunteering opportunities.)

## Tech stack
* Backend - Node + Express + Parse + MongoDB
* [Frontend](https://github.com/Shrreya/tfi-volunteer-frontend/) - React + Redux + Material UI 

## Running locally
```
$ npm install
$ npm start
```
Dashboard is accessible at http://localhost:PORT/dashboard </br>
Default port is 1337.

### Environment variables required
MONGODB_URI, APP_ID, MASTER_KEY, SERVER_URL, PORT, APP_NAME, USER_NAME, PASSWORD </br>
Can be provided through the terminal or a .env file in the root directory

## Project Structure
```bash
├── README.md - This file.
├── index.js # Starter script for server setting up API & dashboard.
├── package.json # npm package manager file.
├── package-lock.json # automatically generated tree for npm operations.
└── cloud
    └── main.js # Cloud code (optional)
```

## Relevant Links
* [Parse Platform](https://parseplatform.org/)
* [Parse Server Guide](https://docs.parseplatform.org/parse-server/guide/)
* [Parse Dashboard](https://github.com/parse-community/parse-dashboard)
* [Parse Cloud Code Guide](https://docs.parseplatform.org/cloudcode/guide/)
* [Deploying to Heroku](https://devcenter.heroku.com/articles/deploying-a-parse-server-to-heroku)
