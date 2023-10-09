

## Description
Task-management project is a web application developed in Nest.js for managing tasks and various assignments. This application allows users to register, log in, and manage their task lists. Users can create new tasks, view existing tasks, update them, and mark them as completed or delete them when done.

## Key Features
1-User Registration and Authentication: Users can register for an account or log in if they already have one. Authentication ensures the security of their data and privacy.

2-Task Management: Users can add new tasks by specifying their title and description. They can view their created tasks and update their status (such as open, in progress, or completed).

3-Searching and Filtering: Users can search for tasks using a simple search query or apply filters to find specific tasks based on their status, creation date, or keywords in the title or description.

4-Notifications: Users can receive notifications and alerts for their tasks, for example, when a task deadline is approaching.

5-Security: User information and their tasks are secure and encrypted, ensuring data privacy and security.

## Technologies Used

1-Nest.js: The application is built using Nest.js, a powerful framework for building server-side applications in TypeScript.

2-TypeORM: TypeORM is used for interacting with the database, providing an Object-Relational Mapping for TypeScript and JavaScript.

3-JWT (JSON Web Tokens): JWTs are used for user authentication, creating secure tokens for user sessions.

4-Database: User information and task data are stored in a database, such as MySQL, PostgreSQL, or MongoDB.

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

## Authors:
Klaudio Toska
