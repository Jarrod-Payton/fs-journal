# Intro to Server side concerns with JavaScript

**1.** What do the letters of the acronym `CRUD` stand for?
<!-- enter you answer in the space below -->
```
Create, Read, Update, Destroy  (delete I just thought Destroy sounded more powerful)
```
**2.** Each action that `CRUD` represents maps to an HTTP request. What HTTP request does each `CRUD` action correspond to?
<!-- enter you answer in the space below -->
```
create (post) read (get) update(put) delete (delete)
```
**3.** What does `ORM` stand for? Which `ORM` do we use when interacting with MongoDB
<!-- enter you answer in the space below -->
```
Object Relational Mapping, MongoDB uses Schema as their object mapping
```
**4.** Which two `HTTP` request types include a body?
<!-- enter you answer in the space below -->
```
put and post
```
**5.** In a/an _______ coding model, when you call a function, it returns only when the action has finished and stops your program for the time the action takes. Likewise in a/an _______ coding model, multiple things are allowed to happen at one time. When you perform an action, your program continues to run.  Fill in the blanks.
<!-- enter you answer in the space below -->
```
first is async with await and the second is a default setup
```

**6.** Fill in the missing piece of this snippet of code.
```js
import ______ from "_______"
let Schema = ________.Schema;
```
<!-- enter you answer in the space below -->
```
Username from Profile let Schema = Profile.Schema
```
**7.** What is middleware?
<!-- enter you answer in the space below -->
```
Middleware is the TSA of the castle where knights in full metal pass but are slightly modified to allow it to get taken in correctly (it changes the data to make it readable to the server depending on how you have it all worded in the background)
```
**8.** The ______ pipeline delivers information from the client while the ______ pipeline returns it. Fill in the blanks. 
<!-- enter you answer in the space below -->
```
the server pipeline and the user pipeline, the server pipeline is used to give and translate information as well as store it where as the client pipeline gives the server info to store using CRUD
```
**9.** 
Demonstrate the pattern that is used to include a request query with the client's `HTTP` request providing the property `tag` and the value `winter`.
<!-- enter you answer in the space below -->
```
api/whatever?tag=winter
```