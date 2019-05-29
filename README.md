# MESN STARTER PROJECT

Not sure if this MESN stack term is official, I use it according to popular MEAN and MERN stacks. :)

Svelte is gaining popularity lately, very interesting and elegant tool for building lightweight, fast user interface. 
This is starter project for MESN stack. If you need something more in this project please create issue and I will try to implement it.

## Requirements

For development, you will need Node.js and npm installed on your environement.

### Node

[Node](http://nodejs.org/) is really easy to install & now include [NPM](https://npmjs.org/).
You should be able to run the following command after the installation procedure
below.

    $ node --version
    v10.15.1

    $ npm --version
    6.9.0

#### Node installation on OS X

You will need to use a Terminal. On OS X, you can find the default terminal in
`/Applications/Utilities/Terminal.app`.

Please install [Homebrew](http://brew.sh/) if it's not already done with the following command.

    $ ruby -e "$(curl -fsSL https://raw.github.com/Homebrew/homebrew/go/install)"

If everything when fine, you should run

    brew install node

#### Node installation on Linux

    sudo apt-get install python-software-properties
    sudo add-apt-repository ppa:chris-lea/node.js
    sudo apt-get update
    sudo apt-get install nodejs

#### Node installation on Windows

Just go on [official Node.js website](http://nodejs.org/) & grab the installer.
Also, be sure to have `git` available in your PATH, `npm` might need it.

---

## Install

    $ git clone https://github.com/HalilovicAmel/mesn-starter-project.git
    $ cd PROJECT
    $ npm install
    $ npm client-install
    
    Update mongoDB URI in config/key.js


## Start & watch - client only

    $ npm run client

## Build client

    $ npm run client:build

## Start & watch - server only

    $ npm run server

## Start & watch - server and client concurrently

    $ npm run dev

---

## Languages & tools

### JavaScript

- Programming language used to create interactive effects within web browsers.

### MongoDB

- [MongoDB](https://www.mongodb.com/) NoSQL database for storing data.

### ExpressJS

- [ExpressJS](https://expressjs.com/) Minimalistic Node.js web framework.

### Svelte

- [Svelte](https://svelte.dev/) Compiler that takes your declarative components and converts them into efficient JavaScript that surgically updates the DOM.

### Node

- [Node](https://nodejs.org) - JavaScript runtime built on Chrome's V8 JavaScript engine.
