# Nepali Connect

Developed using Nestjs, GraphQL, Prisma, Docker, ReactJS, Apollo/Client.

## Backend

#### Stack:

- NestJS
- GraphQL
- Passport
- graphql-subscriptions
- Prisma
- Docker
- Postgresql

##### features:

1. Jwt authentication/authorization
5. **_subscriptions-transport-ws_** authentication
6. **_graphql-ws_** authentication

### Steps to run backend

- `npm run docker:up` (in case you don't want to use docker, then please replace the `DATABASE_URL` in server/.env)
- `npm install`
- `npm run start:dev`

#### DB Data Visualize

`npx prisma studio`

<img width="1440" alt="image" src="https://github.com/subasah/nepaliconnect/assets/11132042/7c09f6db-0253-4e6a-8540-b57c69560b14">

> Signup
<img width="1148" alt="image" src="https://github.com/subasah/nepaliconnect/assets/11132042/aeb8cf9a-88e4-4d25-b68e-1b63893ff09c">


> Login
<img width="1149" alt="image" src="https://github.com/subasah/nepaliconnect/assets/11132042/d0713113-684a-4813-9f9c-259487656572">


> Logout 

