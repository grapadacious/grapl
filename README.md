# GRAPL

It's not a REPL.

## Getting started

This repo uses `docker compose` to run playgrounds. If you don't already have Docker installed, you can install it by following the instructions [here](https://docs.docker.com/desktop).

### Usage

This repo provides several code playgrounds under the `playgrounds` directory where you can write code to run via the provided runtimes. You can even create new files and import them into the `main` file. Open the `main` file for the language of your choice in your favorite editor and start writing.

Once you've made your changes, you can run your playground by using the scripts in the `bin` directory like this:

```sh
bin/grapl js
bin/grapl python
bin/grapl ruby
bin/grapl ts
bin/grapl web
```
