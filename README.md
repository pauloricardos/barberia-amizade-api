Barber shop API using Nodejs, with Postgres as database, Redis as queue, and MongoDB for notification database.

### How to setup
Docker is required to setup local env. Check .env file for more details.
Node version >= 12 is required, Yarn/NPM as well.

## yarn sequelize db:migrate
Command line to migrate info to database using sequelize ORM.

## yarn run dev
Command line to run application, opening in port 3030.

## yarn queue
Command line to setup Redis queue to use email cancellation service.
