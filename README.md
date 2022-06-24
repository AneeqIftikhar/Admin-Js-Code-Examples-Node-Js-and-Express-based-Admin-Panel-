# Admin-Js-Code-Examples-Node-Js-and-Express-based-Admin-Panel-
Admin Js is one of the best Admin Panels available for Node and Express based Projects. It automatically generates crud operations for you db models. This repository will help you implement Admin Js with code examples that are missing from Documentation

# NodeJS-Express-Sequalize-JWT

> NodeJS Express REST API with JWT Authentication and support for MySQL and PostgreSQL with Sequalize.

- Authentication via [jsonwebtoken](https://www.npmjs.com/package/jsonwebtoken);

- Environments for `development` and `production`


## Table of Contents

- [Install & Use](#install-and-use)
- [Configs](#configs)
  - [.env](#.env-file)


## Install and Use

Start by cloning this repository

```sh
# HTTPS
$ git clone https://github.com/AneeqIftikhar/Admin-Js-Code-Examples-Node-Js-and-Express-based-Admin-Panel-.git
```
then use [npm](https://www.npmjs.com/) to

```sh
# Enter project root and Install dependencies
$ npm i

# Copy environment file 
$ cp .env.example .env

# start development with nodemon
$ npm run dev
```

## Configs

### .env file

#### Database

Configure the keys with your credentials in `.env` file.

```
  DB_DIALECT=mysql
  DB_HOST=localhost
  DB_NAME=name
  DB_USER=root
  DB_PASSWORD=root
  DB_PORT=3609
```