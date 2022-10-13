# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

Run docker-compose up in your codespace's terminal to load Anythink's backend and frontend.
Once docker-compose finishes loading up, the backend should be running and able to connect to the database.
After the server is up, make sure you test it by pointing your browser to https://obelusfamily-anythink-market-bjeki-95g659w96g6hpqw4-3000.githubpreview.dev/api/ping
If everything is working properly, you’ll be able to create a new user on https://obelusfamily-anythink-market-bjeki-95g659w96g6hpqw4-3001.githubpreview.dev/register
