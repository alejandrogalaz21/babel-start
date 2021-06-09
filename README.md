<p align="center">
  <a href="https://github.com/alejandrogalaz21/mongoose-example">
    <img src="https://media.giphy.com/media/13HBDT4QSTpveU/giphy.gif" alt="cat developer" width=350 height=250>
  </a>

  <h3 align="center">Mongoose ES6 Example</h3>

  <p align="center">
    This is a practice repo using a mongodb object modeling for node.js
    <br>
    <a href="https://github.com/alejandrogalaz21/mongoose-example/issues">Report bug</a>
    ·
    <a href="https://github.com/alejandrogalaz21/mongoose-example/pulls">Request feature</a>
    <br>
    Author 
    <br>
    <a href="https://github.com/alejandrogalaz21">Alejandro Galaz</a>
  </p>
</p>

## Table of Contents

1. [General Info](#general-info)
2. [Technologies](#technologies)
3. [Installation](#installation)
4. [Dependecies](#dependencies)
5. [Refs](#refs)
6. [Bugs and feature requests](#bugs-and-feature-requests)
7. [Refs](#refs)

### General Info

---

Project Structure :

```text
src/
├── config/
│   └── mongoose.connection.js
├── models/
│   └── product.model.js
├── services/
│   └── product.service.js
├── test/
│   └── product.service.test.js
│   └── product.util.test.js
├── utils/
│   └── product.util.js
└── index.js

```

## Technologies

---

A list of technologies used within the project:

- [Node.js ](https://example.com): Version 14.15.4

## Installation

---

Create your .env file :

```
MONGO_DB_HOST=yourDBHost
MONGO_DB_NAME=yourDBName
MONGO_DB_USER=yourDBUser
MONGO_DB_PASSWORD=yourDBPassword
```

Run the Application in development mode :

```
$ git clone https://example.com
$ cd ../path/to/the/file
$ yarn
$ yarn dev
```

Run the aplication in debug :bug: mode in [Visual Studio Code](https://code.visualstudio.com/) :

Create your Visual Studio Code config file .vscode/launch.js

```
{
  "configurations": [
    {
      "type": "node",
      "request": "attach",
      "name": "Attach",
      "restart": true,
      "port": 9229
    },
    {
      "type": "node",
      "request": "launch",
      "protocol": "inspector",
      "name": "ES6 Debugger",
      "program": "${workspaceFolder}/src/index.js",
      "runtimeExecutable": "${workspaceRoot}/node_modules/.bin/babel-node",
      "runtimeArgs": ["--nolazy"],
      "env": {
        "BABEL_ENV": "debug"
      },
      "resolveSourceMapLocations": [
        "${workspaceFolder}/**",
        "!**/node_modules/**"
      ]
    }
  ]
}

```

## Dependencies :

---

### Install nodemoon

See : https://www.npmjs.com/package/nodemon

```
yarn add nodemon -D
```

### Integrating Prettier and ESLint With VS Code

See : https://enlear.academy/integrating-prettier-and-eslint-with-vs-code-1d2f6fb53bc9

```
yarn add eslint eslint-config-prettier eslint-plugin-prettier prettier -D
```

### Install Mongoose

Install : https://www.npmjs.com/package/mongoose

Docs : https://mongoosejs.com/docs/guide.html

```
yarn add mongoose
```

### Configure Babel for a Nodejs Application

See : https://dev.to/adebayoileri/configure-babel-for-nodejs-application-3798

### Install chalk for logs

See : https://www.npmjs.com/package/chalk

```
yarn add chalk
```

### Install dotenv

Dotenv is a zero-dependency module that loads environment variables from a .env file into process.env. Storing configuration in the environment separate from code is based on The Twelve-Factor App methodology.

See : https://www.npmjs.com/package/dotenv

```
yarn add dotenv
```

# Refs :

- https://www.toptal.com/developers/gitignore
- https://www.markdownguide.org/basic-syntax/
- https://gist.github.com/rxaviers/7360908

# Bugs and feature requests

Have a bug or a feature request? Please first read the [issue guidelines](https://github.com/alejandrogalaz21/mongoose-example/pulls) and search for existing and closed issues. If your problem or idea is not addressed yet, [please open a new issue](https://github.com/alejandrogalaz21/mongoose-example/issues).

# Thanks

Some Text
