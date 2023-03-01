## Blog-Backend Rest API
A simple backend Rest API for a built using NestJS, Prisma, PostgreSQL and Swagger. Implemented input validation, transformation and error handling.

## Installation
1. Install dependencies:
```bash
$ npm install
```
2. Start a PostgreSQL database with docker using:
```bash
$ docker-compose up -d
```
3. Apply database migrations:
```bash
$ npx prisma migrate dev
```
4. Start the project:
```bash
$ npm run start:dev
```
5. Access the project at http://localhost:3000/api

## Further improvements
- [ ] User module and Authentication will be added
- [ ] Handle file uploads
- [ ] Unit test will be added
