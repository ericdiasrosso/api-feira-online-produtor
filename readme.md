
# Getting started

## Installation

1. Install [Node.JS](https://nodejs.org/en/) LTS version
2. Install PostgreSQL
3. Clone this repository and enter on the respective folder
4. Install dependencies running: `yarn` or `npm install`

## Things to do before run the project:

1. Create database (by follow the commands):

- CREATE USER `user` WITH PASSWORD `password`
- CREATE DATABASE `database`
- GRANT ALL PRIVILEGES ON DATABASE `database` to `user`

2. Run `yarn start` or `yarn dev` to start server


## Directory Structure

```
├── /src
|   ├── /database
├── /test
```

## Postman

[![Run in Postman](https://run.pstmn.io/button.svg)](https://app.getpostman.com/run-collection/aba33a508a2c4dff0754)


## Database

This project uses sequelize as query builder.
