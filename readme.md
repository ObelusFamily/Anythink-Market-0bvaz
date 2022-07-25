# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

1. Clone the Anything Marketing github [repo](https://github.com/ObelusFamily/Anythink-Market-0bvaz).
2. Install [Docker](https://docs.docker.com/get-docker/) on your system.
3. Verify if docker is installed by running the following commands in your terminal: `docker -v` and `docker-compose -v`.

4. Then, in terminal open project's root directory run the command `docker-compose up`.
   <br>If docker is running correctly then you should be able to connect to local database. Test this by pointing your browser to [http://localhost:3000/api/ping](http://localhost:3000/api/ping).

5. Now the backed is up and running. Now, it’s time to check the frontend and make sure it’s connected to the backend. If everything is working properly, you’ll be able to create a new user on [http://localhost:3001/register](http://localhost:3001/register).
6. Create one new user (choose a nickname and everything) and you’ll be able to move to the next task.
