# OMGDEFOLDTEMPLATE

This is
the [OMGSERVERS](https://github.com/OMGSERVERS/omgservers) [Project Template](https://defold.com/manuals/editor-templates/)
for the [Defold Engine](https://github.com/defold/defold).

To use this project as a template, follow the [Defold guide](https://defold.com/manuals/editor-templates/).

### Structure

- [Client-side](https://github.com/OMGSERVERS/omgdefold/tree/main/client): Contains the client-side code.
- [Server-side](https://github.com/OMGSERVERS/omgdefold/tree/main/server): Contains the server-side code.
- [Dockerfile](https://github.com/OMGSERVERS/omgdefold/blob/main/Dockerfile): Used to build the game runtime as a
  headless Defold build using `bob.jar`.
- [Config JSON](https://github.com/OMGSERVERS/omgdefold/blob/main/config.json): Provides matchmaking and custom
  configuration for the game.
- [Server Settings](https://github.com/OMGSERVERS/omgdefold/blob/main/server.settings): Contains separate settings for
  building a headless version of the game.

### Getting Started with the Project

1. Run `./omgprojectctl.sh build` to build the Docker container.
1. Run `./omgserversctl.sh localtesting runServer` to start the server in a Docker container.
1. Run `./omgserversctl.sh localtesting initProject` to initialize a new server project and developer account.
1. Run `./omgserversctl.sh localtesting deployProject` to deploy a new project version locally.
1. Open `game.project` in Defold and run the game.