1. What do the letters of the acronym CRUD stand for?

Create, Read, Update, Delete.

2. Each action that CRUD represents maps to an HTTP request. What HTTP request does each CRUD action correspond to?

GET, POST, PUT, DELETE.


3. What does ORM stand for? Which ORM do we use when interacting with MongoDB?

Object Relational Mapping. Mongoose.


4. Which two HTTP request types include a body?

PUT and POST.


5. In a/an _______ coding model, when you call a function, it returns only when the action has finished and stops your program for the time the action takes. Likewise in a/an _______ coding model, multiple things are allowed to happen at one time. When you perform an action, your program continues to run. Fill in the blanks.

Synchronous and Asynchronous.


6. Fill in the missing piece of this snippet of code.

import ______ from "_______"
let Schema = ________.Schema;

mongoose from"mongoose", Schema from "mongoose.Schema".

7. What is middleware?

Middleware is software that is between an operating system and its running applications and enables communication and data management.


8. The ______ pipeline delivers information from the client while the ______ pipeline returns it. Fill in the blanks.

Request, Response


9. Demonstrate the pattern that is used to include a request query with the client's HTTP request providing the property tag and the value winter.

 async find(query = {}) {
    return await dbContext.Seasons.find()
  }