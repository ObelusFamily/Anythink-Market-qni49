# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

01. Once you log in to GitHub and approve your invitation. Go to 
https://github.com/ObelusFamily/Anythink-Market-qni49 and clone the repository.

02. To Install Docker, follow the link - https://docs.docker.com/get-docker/

03.  You can verify docker is ready by running the following commands in your terminal: docker -v and docker-compose -v

04. Go to the project root directory, and run 'docker-compose up' to load anythink's backend and frontend. If Docker is working correctly, the backend should be running and able to connect to your local database.

05. Test this by pointing your browser to http://localhost:3000/api/ping. This means the backend is up and running.

06. Now, it’s time to check the frontend and make sure it’s connected to the backend. If everything is working properly, you’ll be able to create a new user on http://localhost:3001/register . Create one (choose a cool nickname and everything) and you’ll be able to move to the next task.
