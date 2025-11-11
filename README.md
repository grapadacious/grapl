# GRAPL

It's not a REPL.

## Getting started

This repo uses `asdf` to manage runtime installs. If you don't already have `asdf` installed, you can install it by following the instructions [here](https://asdf-vm.com/guide/getting-started.html).

### Prerequisites

```sh
asdf plugin add nodejs
asdf plugin add python
asdf plugin add ruby
```

### Installation

```sh
asdf install
npm install
```

### Usage

This repo provides several code playgrounds under the `playgrounds` directory where you can write code to run via the provided runtimes. You can even create new files and import them into the `main` file! Open the `main` file for the language of your choice in your favorite editor and start writing.

Once you've made your changes, you can run your playground by using the scripts in the `bin` directory like this:

```sh
bin/js
bin/python
bin/ruby
bin/ts
```
