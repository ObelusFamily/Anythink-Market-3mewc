# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

You can run docker-compose up in your codespace's terminal to load Anythink's backend and frontend.
Pointing your browser to https://obelusfamily-anythink-market-3mewc-779xv97qxx5cgjq-3000.githubpreview.dev/api/ping to test de BE

You can register a new user on FE at this url:
https://obelusfamily-anythink-market-3mewc-779xv97qxx5cgjq-3001.githubpreview.dev/register

Just make sure that you run all scripts in the next quests on one of the containers created by docker-compose up.  Also, you can use docker exec to run commands on a running container.