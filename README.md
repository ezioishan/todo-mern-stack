# Todo-mern-stack
A simple app to maintain daily tasks built on MERN stack

# Features
  - Provides operations to Create, Read and Delete todos.
  - All these operations are done through an API

### Tech
* [ReactJS] - HTML enhanced for web apps!
* [mongoDB Atlas] - Markdown parser done right. Fast and easy to extend.
* [NodeJS] - evented I/O for the backend
* [Express] - fast node.js network app framework [@tjholowaychuk]

### API testing
To test the api, POSTMAN or INSOMNIA software can be used
* GET: http://localhost:5000/todos - Shows list of all todos
* POST: http://localhost:5000/todos - Creates a new todo with specified body
    body:

        {
            "action": "your todo title"
        }
* DELETE: http://localhost:5000/<id> - Deletes a todo with  **_id = <id>**

### Installation
The app requires [Node.js](https://nodejs.org/) v4+ to run.
Install the dependencies and devDependencies and start the server.

```sh
$ cd todo-mern-stack
$ npm install
$ node run dev
```

### Future improvements

 - Add Update operation
 - Make the UI more interactive

[//]: # (These are reference links used in the body of this note and get stripped out when the markdown processor does its job. There is no need to format nicely because it shouldn't be seen. Thanks SO - http://stackoverflow.com/questions/4823468/store-comments-in-markdown-syntax)

   [mongoDB Atlas]: <https://www.mongodb.com/cloud/atlas>
   [NodeJS]: <http://nodejs.org>

   [express]: <http://expressjs.com>
   [ReactJS]: <https://reactjs.org/>

