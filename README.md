# Blog back-end application

# Getting started

## Installation

### Prerequisites

 - Node.js 16.18.0
 - docker & docker-compose

Clone this repository
```bash
  git clone git@github.com:yegor-ts/blog-backend.git
```

Go to the project directory

```bash
  cd blog-backend
```

Install dependencies using [yarn](https://classic.yarnpkg.com/en/docs/install/#mac-stable)

```bash
  yarn install
```

Create a ***.env*** file in root directory and add following values

```bash
  POSTGRES_HOST=
  POSTGRES_PORT=
  POSTGRES_USER=
  POSTGRES_PASSWORD=
  POSTGRES_DB=
  PORT=
```

Run the project

```bash
 yarn start
```

## Database

The project uses PostgreSQL and TypeORM.

Create a docker.env file in the root directory and add following values

```bash
  POSTGRES_USER=
  POSTGRES_PASSWORD=
  POSTGRES_DB=
  PGADMIN_DEFAULT_EMAIL=
  PGADMIN_DEFAULT_PASSWORD=
```

Run docker-compose to create and start containers

```bash
  docker-compose up --build
```
Now you got PostgreSQL and pgadmin available in docker containers