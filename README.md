# Recitation 1 - Git, Github and TypeScript Starter Code

See recitation handout on the [course website](https://cmu-313.github.io/recitations/reci1-github/)

The starter code is a basic express server with an endpoint that computes fibonacci(n)

## Running the App

The steps below aren't strictly necessary to complete the recitation.

1. Make sure you have TypeScript and npm installed
2. Run `npm install` to install dependencies
3. Run `npm start` to start the server
4. Go to a browser and visit `localhost:3000/fib/n` to see the result for fibonacci(n)

## Running tests and linter

We've setup a GitHub action to run eslint and tests for the fibonacci endpoint.

- You can run the linter locally by running `npm run lint`
- You can run the tests defined in `tests/fib.test.ts` by running `npm run test`
