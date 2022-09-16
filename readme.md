# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

Clone GitHub Repo
Install Docker - https://docs.docker.com/get-docker/
Ensure Docker has been installed using 'docker -v' and 'docker-compose -v'
If Docker has been installed correctly, you will be able to see '{"msg":"Pong! Seems like Everythink is working, great job!"}' when accessing http://localhost:3000/api/ping on your browser
Now check the frontend is working - http://localhost:3001/register
Create an account