## Goal
we want to build a starter kit that is deployble to aws and has oauth built in
this app should be as close as plug in and play

## Stack
- aws
- serverless
- mongo
- jwt
- express
- graphql

## Road Map
- install a express app in aws code star, make sure the app is deployed and
  we can interact with
- add mongo, make sure we can do CRUD
- set up a graphql server and make sure we can get result from graphql server
- implement jwt, make sure user can sign up, login and be authenticated,
  make sure authenticated user and unauthenticated user see different feedback
  - use graphQL to do the login or use dedicated serverless endpoin?
- abstract this into lib, cli, a service?
