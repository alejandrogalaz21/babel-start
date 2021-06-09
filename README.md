<h3 align="center">Babel Node ES6 Example</h3> 
<p align="center">
  <a href="https://github.com/alejandrogalaz21/js-babel-node">
    <img src="https://media.giphy.com/media/13HBDT4QSTpveU/giphy.gif" alt="cat developer" width=350 height=250>
  </a>

  <p align="center">
    This is a practice repo for node.js
    <br>
    <a href="https://github.com/alejandrogalaz21/js-babel-node/issues">Report bug</a>
    ·
    <a href="https://github.com/alejandrogalaz21/js-babel-node/pulls">Request feature</a>
    <br>
    Author 
    <br>
    <a href="https://github.com/alejandrogalaz21">Alejandro Galaz</a>
      <p align="center">
        <a href="https://github.com/alejandrogalaz21">
          <img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" />    
        </a>
        <a href="https://gitlab.com/alejandrogalaz21">
          <img src="https://img.shields.io/badge/GitLab-330F63?style=for-the-badge&logo=gitlab&logoColor=white" />    
        </a>
        <a href="https://www.linkedin.com/in/jesus-alejandro-galaz-icedo-496b94115/">
          <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" />    
        </a>
        <a href="https://alejandrogalaz21@gmail.com">
          <img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" />    
        </a>
    </p>
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
8. [Legal](#legal)
9. [Thanks](#thanks)

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

 <p align="">  
    <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" /> 
    <img src="https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node-dot-js&logoColor=white" /> 
    <img src="https://img.shields.io/badge/Yarn-2C8EBB?style=for-the-badge&logo=yarn&logoColor=white"/> 
    <img src="https://img.shields.io/badge/Jest-C21325?style=for-the-badge&logo=jest&logoColor=white"/> 
  </p>

Requiriments:

[![node.js](https://img.shields.io/badge/node.js-v14.15.4-<COLOR>)](https://nodejs.org/es/)

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
$ yarn add nodemon -D
```

### Integrating Prettier and ESLint With VS Code

See : https://enlear.academy/integrating-prettier-and-eslint-with-vs-code-1d2f6fb53bc9

```
$ yarn add eslint eslint-config-prettier eslint-plugin-prettier prettier -D
```

### Install Mongoose

Install : https://www.npmjs.com/package/mongoose

Docs : https://mongoosejs.com/docs/guide.html

```
$ yarn add mongoose
```

### Configure Babel for a Nodejs Application

See : https://dev.to/adebayoileri/configure-babel-for-nodejs-application-3798

### Install chalk for logs

See : https://www.npmjs.com/package/chalk

```
$ yarn add chalk
```

### Install dotenv

Dotenv is a zero-dependency module that loads environment variables from a .env file into process.env. Storing configuration in the environment separate from code is based on The Twelve-Factor App methodology.

See : https://www.npmjs.com/package/dotenv

```
$ yarn add dotenv
```

# Refs :

- https://www.toptal.com/developers/gitignore
- https://www.markdownguide.org/basic-syntax/
- https://gist.github.com/rxaviers/7360908
- https://github.com/Naereen/badges/blob/master/README.md
- https://shields.io/
- https://github.com/alexandresanlim/Badges4-README.md-Profile

# Bugs and feature requests

Have a bug or a feature request? Please first read the [issue guidelines](https://github.com/alejandrogalaz21/js-babel-node/pulls) and search for existing and closed issues. If your problem or idea is not addressed yet, [please open a new issue](https://github.com/alejandrogalaz21/js-babel-node/issues).

# [](https://github.com/pranavms13/whatsapp-node-api#legal)📃 Legal

This code is in no way affiliated with, authorized, maintained, sponsored or endorsed or any of its affiliates or subsidiaries. This is an independent and unofficial software. Use at your own risk. **Commercial use of this code/repo is strictly prohibited.**

## Thanks 👋
