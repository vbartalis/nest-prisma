## Description

[Nest](https://github.com/nestjs/nest) framework TypeScript starter repository.

## Installation

```bash
$ npm install
```

## Running the app

```bash
# development
$ npm run start

# watch mode
$ npm run start:dev

# production mode
$ npm run start:prod
```

## Test

```bash
# unit tests
$ npm run test

# e2e tests
$ npm run test:e2e

# test coverage
$ npm run test:cov
```

## Develop the Nest application

> DON'T commit .env files into version control, add `.env` to `.gitignore`. `.env` files are added here as an example.

```bash
npm install

cp .env.example .env

npx prisma generate

npm run start:dev
```

## Docker File

Get started by running

```bash
docker build -t nest-api .

docker run -p 3000:3000 --env-file .env -d nest-api
```

## Docker Compose

```bash
docker-compose up
# or detached
docker-compose up -d
```
