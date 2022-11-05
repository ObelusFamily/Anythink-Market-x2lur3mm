# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

1. clone the repo.
2. install docker on your machine.
3. run:
```
docker-compose up
```
4. visit: http://localhost:3000/api/ping to verify installation.
5. visit: http://localhost:3001/register to create your local user.