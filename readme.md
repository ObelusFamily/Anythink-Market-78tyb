# Welcome to the Anythink Market repo

## Contents

- [Setting up](#setting-up)
- [Development](#development)

## Setting up

To start the app use [Docker](https://docs.docker.com/get-docker/).

To do this, from the root run:
```shell
docker-compose up
```

It will start both frontend and backend, including all the relevant dependencies, and the db.

To check you can ping the [backend health endpoint](http://localhost:3000/api/ping)

```shell
curl http://localhost:3000/api/ping
```

To confirm the front end is working, you can try to [register a user](http://localhost:3001/register)

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.
