# Chat Application

A secure Chat Applications in MERN stack.

## Tech used:

- JWT used to create access tokens for an application.
- MongoDB for the Databases.
- React (react.js) for the UI web framework.
- Material-UI for styling the components.
- socket.io for chatting.- babel for transcompilling.


For other dependencies check [package.json](package.json)

## What is it?:

A secure chat application where the messages of the users are not stored in any databases.
It is a secure onetime chat application where the users can connect with each other chat and leave, 
without being worried about where their messages will be stored and who will have access to it.

## Build:

This is a stand alone application build with react and node.js. 
Here, both the front end and back end code are in the same repository instead of being seperate.

    To run:
    - clone the repo using this link
    - Replace the Mongo URl with yours to access the database
    - install the dependencies using 'npm install'.    
    - open a terminal and run 'npm start'.

## Back-end
First navigate to the [server](server) directory and run
```
nodemon app.js

## Front-end
First navigate to the [server](server) directory and run
```
npm start

This will start the server in port `8000` on your `localhost:3000` for the FrontEnd and you can use the application.

