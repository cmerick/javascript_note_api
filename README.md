Api Evernote Based

This is a study case where I develop the backend of an application of note creation.

The DB was made with MongoDB and tests were made with Postman;

As far as it goes you can:
    .Create an account and login;
    .Create notes with titles and texts;
    .Delete and update this notes;
    .Search for specifics notes;

.Creating an account is based in bcrypt, jsonwebtoken and dotenv for authentication;
.All the others functions are based on authorization token linked with the account;

Frameworks and others: nodemon, mongoose, express-generator (no-view), bcrypt, jsonwebtoken, dotenv, cors;

