# ethsf-iCash
# frontend
  
`todo: add api`  

# backend

## Getting Started

### Prerequisites

- [Git](https://git-scm.com/)
- [Node.js and npm](nodejs.org) Node ^4.2.3, npm ^2.14.7
- [GulpJS](https://gulpjs.com/) (`yarn global add gulp-cli`)
- [PostgreSQL](https://www.postgresql.org/) (`brew install postgresql`) (see db config for role)
- [Redis](https://redis.io/) Running on default port locally

### Developing

1. Run `yarn install` to install server dependencies.

2. Run `gulp db:create` to create database. Run `gulp db:drop` to drop database.

3. Run `node_modules/.bin/babel-node node_modules/.bin/sequelize db:migrate` to run migrations.

4. Run `gulp db:seed` to seed database.  (Not Implemented)

5. Run `yarn start` to start backend development.

## Testing

Running `npm test` will run the unit tests with karma. (not implemented)