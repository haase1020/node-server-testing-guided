# Web API Testing

## Objectives

- setup Jest for testing Node.js code
- write tests for API endpoints
- use Heroku Prostgres in production

component(props) => UI;
function(args) => value;
endpoint(data) => response;

## Flow of testing
- run the server
- make a request
- inspect the response --> use a library (like supertest)


## integration tests
- test how different parts of the system (program) work together
- we write integration tests for endpoints

## unit tests
- we verify the correctness of one part of the system in isolation

## 3 questions commonly tested for endpoints
- Does it return the correct status code for the input provided?
- Does it return the data in the expected format?
- Does the data returned, if any, have the right content?


## add to package.json or input npm i jest --init
},
  "jest": {
    "testEnvironment": "node"
  }
## also:
  "test": "jest --watch"

  ## documentation on configuration for jest
  https://jestjs.io/docs/en/configuration


  npm i -D supertest
  npm i jest??
