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

## Migrations

```bash
# create migrations
$ npx typeorm migration:create path/name

# generate migrations
$ npx typeorm migration:generate path/name -d ormconfig.js

# run migrations
$ npx typeorm migration:run -d ormconfig.js

# revert migrations
$ npx typeorm migration:revert -d ormconfig.js
```