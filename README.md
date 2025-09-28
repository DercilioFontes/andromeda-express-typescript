# Andromeda Express TypeScript Server

## Fork from 🚀 Express TypeScript Boilerplate 2025

<https://github.com/edwinhern/express-typescript>

## Setup

- `pnpm install`

- `cp .env.template .env`

## Andromeda image

- `andromeda` folder

## Multi-stage build

- The app is build with npm and Node

- The app runner is Andromeda

```sh
docker build -t dercilio/andromeda-typescript-express:0.1.0-draft43 .

docker run --name andromeda-typescript-express -p 8080:8080 dercilio/andromeda-typescript-express:0.1.0-draft43
```
