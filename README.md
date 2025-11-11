# GRAPL

It's not a REPL.

## Getting started

This repo uses `docker compose` to run playgrounds. If you don't already have Docker installed, you can install it by following the instructions [here](https://docs.docker.com/desktop).

### Usage

This repo provides several code playgrounds under the `playgrounds` directory where you can write code to run via the provided runtimes. You can even create new files and import them into the `main` file. Open the `main` file for the language of your choice in your favorite editor and start writing.

Once you've made your changes, you can run your playground using `bin/grapl` with the relevant command.

#### JavaScript

```sh
bin/grapl js
```

#### Python

```sh
bin/grapl python
```

#### Ruby

```sh
bin/grapl ruby
```

#### TypeScript

```sh
bin/grapl ts
```

#### Static website

```sh
bin/grapl web
```

Visit `http://localhost:8080` to view the running website. Any changes made to the `web` playground will be reflected on refresh. There is no need to restart the server.

### Configuration

There is an example `.env` file called `.env.example`. You can copy that file to specify versions other than the defaults for the different runtimes.
