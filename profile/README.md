<h1>Greetings</h1>

This is the organisation that I use for my Chess Tournament Manager project. It is an open source school project, where people who hosts tournaments can easily create pairings between players and share the current tournament standings with them.

If you want to run this application, clone the following repositories into a folder:
- frontend
- tournament-svc
- round-svc
- player-svc
- match-svc

Install [Docker](https://docs.docker.com/get-docker/) and then place the docker-compose.yml file in this repository in the folder where all the repositories are cloned to and run the following command:

```sh
docker compose -f "docker-compose.yml" up -d --build
```

If you want to know more about this project, go to the [documentation repository](https://github.com/ChessTournamentManager/Documentation)