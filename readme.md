# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup
1. Install [Docker](https://docs.docker.com/get-docker/)
2. Verify docker is ready by running `docker -v` in your terminal 
3. Run `docker compose up` from the project root directory
4. Test app works by pointing browser at http://localhost:3000/api/ping
