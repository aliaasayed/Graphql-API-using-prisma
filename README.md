## Description

Simple Blog App Using Graphql APIs And Prisma

## Database Configration

```bash
Add your database configration in prisma/docker-compose.yml [host, databasename,
username, password]
```

## Installation

```bash
$ npm install
$ cd prisma
$ docker-compose up -d
$ prisma deploy -e ../config/dev.env
$ cd ..
```

## Running the app

```bash
# start
$ npm start

# development
$ npm run dev
```

## View Deployed link
https://shrouded-ocean-69632.herokuapp.com/