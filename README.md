## Installation

```bash
$ pnpm install
```

## Running the app

```bash
# development
$ pnpm run start

# watch mode
$ pnpm run start:dev

# production mode
$ pnpm run start:prod
```

## Test

```bash
# unit tests
$ pnpm run test

# e2e tests
$ pnpm run test:e2e

# test coverage
$ pnpm run test:cov
```

## Docker

```bash
$ cd .\apps\reservations\
$ docker build ../../ -f Dockerfile -t sleepr_reservations
$ docker run sleepr_reservations
```

## Docker run

```bash
$ docker-compose up

```

## Docker down

```bash
$ docker-compose down

```

