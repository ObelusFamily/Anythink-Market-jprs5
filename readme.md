# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

1. `git clone` this repo and `cd` inside the new directory.
2. Install ([Docker]https://www.docker.com/).
3. Run `docker-compose-up`
4. Once that finishes you should be able to

- Test that the backend works through `GET`ing this ([url]https://obelusfamily-anythink-market-jprs5-vq4x4q6qgr3w9xw-3000.githubpreview.dev/api/ping).
- Test that the frontend works by registering a new user ([here]https://obelusfamily-anythink-market-jprs5-vq4x4q6qgr3w9xw-3001.githubpreview.dev/register).
