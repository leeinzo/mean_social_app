
// Start up MongoDB server in command 
c:\program files\mongodb\server\3.2\bin --> mongod.exe

// If need to view database directly open another command - the above command needs to be running first
c:\program files\mongodb\server\3.2\bin --> mongo.exe

--> use social
--> db.posts.find()

// Angular app
C:\Users\Lee\Documents\GitHub\mean_social
// now copied to \mean_social_api - browse for root (localhost:3000)

// The API 

// Mongoose ODM to interact with MongoDB - a light layer on top of Mongo driver
npm install --save mongoose

C:\Users\Lee\Documents\GitHub\mean_social_api --> node server.js

$ npm install --global nodemon
$ nodemon server.js  // auto-restarts server.js if changes detected
