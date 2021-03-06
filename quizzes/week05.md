# Intro to Server side concerns with JavaScript

**1.** What do the letters of the acronym `CRUD` stand for?
<!-- enter you answer in the space below -->
```
Create, Read, Update and Destroy
```
**2.** Each action that `CRUD` represents maps to an HTTP request. What HTTP request does each `CRUD` action correspond to?
<!-- enter you answer in the space below -->
```
GET, POST, PUT and DELETE.
```
**3.** What does `ORM` stand for? Which `ORM` do we use when interacting with MongoDB
<!-- enter you answer in the space below -->
```
Object-Relational Mapping. Mongoose uses ODM 'Object-Document Mapper'.
```
**4.** Which two `HTTP` request types include a body?
<!-- enter you answer in the space below -->
```
Put when editting and Post when creating.
```
**5.** In a/an _______ coding model, when you call a function, it returns only when the action has finished and stops your program for the time the action takes. Likewise in a/an _______ coding model, multiple things are allowed to happen at one time. When you perform an action, your program continues to run.  Fill in the blanks.
<!-- enter you answer in the space below -->
```
In a/an 'Synchronous' coding model, when you call a function, it returns only when the action has finished and stops your program for the time the action takes. Likewise in a/an 'Asynchronous' coding model, multiple things are allowed to happen at one time. When you perform an action, your program continues to run.  Fill in the blanks.
```

**6.** Fill in the missing piece of this snippet of code.
```js
import ______ from "_______"
let Schema = ________.Schema;
```
<!-- enter you answer in the space below -->
```
import mongoose from 'mongoose'
let Schema = mongoose.Schema
```
**7.** What is middleware?
<!-- enter you answer in the space below -->
```
They are functions which are passed control during execution of asynchronous functions.
```
**8.** The ______ pipeline delivers information from the client while the ______ pipeline returns it. Fill in the blanks. 
<!-- enter you answer in the space below -->
```
The 'request' pipeline delivers information from the client while the 'response' pipeline returns it.
```
**9.** 
Demonstrate the pattern that is used to include a request query with the client's `HTTP` request providing the property `tag` and the value `winter`.
<!-- enter you answer in the space below -->
```
?tag=winter
```