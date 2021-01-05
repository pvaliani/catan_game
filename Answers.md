# Games Hub

Homework:

1. Create router method acting upon the collection of the database defines the routes of the games resource - this is located in the server side
2. The client is responsible for the front end view of the application and defines all components, containers which hold state of the database info. The server is responsible for retrieving and handling back end information from mongoDB to pass to the front end. 
3. The responsibility of server.js is to listen for client requests. As such we need to make the db, gamesCollection and gamesRouter available to the server.js at all times. It is responsible for listening on the port of choice i.e 5000 in this case
4. The gamesRouter is created from the createRouter method and its responsibilities affect our CRUD methods as part of our RESTful API. 
5. — Not sure I understand what this question is asking
6. The optional second argument is the type of request being defined i.e post, delete. By default this is a get request
7. It makes requests to the base url which is /api/games i.e 'http://localhost:5000/api/games/'
8. The MongoDB driver allows node.js apps to connect to mongoDB and work with data - it is middleware(?)

Extension:

The objectId is used because it is the unique reference which identifies the object we are invoking action on within the game.
