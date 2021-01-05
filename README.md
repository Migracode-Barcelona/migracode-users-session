# migracode-users-session

## Before to start
1. Think about a complete login system, draw the forms on a paper
2. Could you list the different endpoints your backend needs to be able to complete all login functionalities? explain how would work each one and dessign the database on a paper

## Part 1: Back-End
1. Create the DB
2. Create the project structure, 2 folders clientand server
3. Int the In the server  folder create a server connected to the DB
4. Develop the 4 endpoints (introduce bcrypt to store passwords, email sender??, there is an easy way to manage sessions in Node?)
5. Test endpoints with postman

## Part 2: Front-End
1. In the client folder, Build the react APP
2. Build Register Component connected to the server
3. Build Login Component connected to the server
4. Build Dashboard Component connected to the server, how do we manage the sessionId in the front, cookies?

## Part 3: Add roles to the users in your project
1. Server: There will be an admin role, change the server to only allow admin users access to all users data
2. Client: Add the role and in client code, only the admin will see a complete list of all users, able to remove them 1 by 1
