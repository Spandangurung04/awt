## HTTP methods
HTTP methods are used to perform actions on resources in web applications. HTTP methods are the different types of requests a client can make to the server. They allow the backend to recognize the type of response the clients expect.

### 1. GET
The GET method is used to retrieve data from the server without making any changes. 

### 2. POST
POST sends data to the server to create a new resource.

### 3. PUT
PUT method is used to update an existing resource completely.

### 4. DELETE
DELETE method removes a resource from the server.

---

## HTTP Status code
HTTP Status codes are numeric values sent by the server to the client.HTTP status codes are issued by a server in response to a client's request.

### 1. 1xx: Informational
These status codes are used when the request was received, and the server is continuing the process.

### 2. 2xx: Success
These status codes are used when the request was successfully received, understood, and accepted.

### 3. 3xx: Redirection
These status codes are used when the client must take additional steps to complete the request.

### 4. 4xx: Client Error
These status codes are used when the request has an error due to the client. For eg: wrong URL, unauthorized.

### 5. 5xx: Server error
These status codes are used when the server failed to process a valid request due to an internal issue.

---
## CSS Selectors
CSS selectors are used to add styling to all the selected tags.

### 1. Universal selectors
These selectors select all the elements.
```
*{
    margin: 0;
    padding: 0;
}
```

### 2. Type Selector
Type selector selects all the elements of given type.
```
p{
    color: red;
}
```

### 3. Class Selector
Class Selector selects all the elements of specified class.
```
.operator button{
    color: black;
    background-color: green;

}
```

### 4. ID Selector
Id selector selects all the element with a given id.
```
#intro{
  color: blue;
  font-size: 20px;
}
```
---

## Git Basics

### 1. Init
This command is used at the beginning of the project. This is neccessary because this command creates a hidden file .git which helps in tracking changes.

### 2. Add
This command us used to add changed files and folders.

### 3. Commit
This command saves staged changes with a message.

### 4. push
This command sends your commits to a remote repository.

### 5. pull
 This command fetches and merges changes from a remote repository.

 ### 6. Clone
  This command copies a remote repository to your local machine.

### 7. Branch
In Git, branches are the copies of a project where multiple people can work together without affecting one another.

---

## Callback Fubction
A callback function is a function that is passed as an argument to another function and is executed after the completion of that function.
```
function greet(name, callback) {
  console.log("Hi " + name);
  callback();
}

function sayBye() {
  console.log("Goodbye!");
}

greet("Alice", sayBye);
```

---

## Higher order function
A higher-order function is a function that takes one or more functions as arguments or returns a function as its result.
```
function greet(name) {
  return function(message) {
    console.log(message + ", " + name);
  };
}

const sayHello = greet("Ram");
sayHello("Hello");  // Output: Hello, Ram
```

---

## Array Methods
Array methods are built-in functions in programming languages like JavaScript that let you perform operations on arrays easily. They help you add, remove, search, transform, or iterate over elements in an array without writing complex code from scratch.

### 1. push()
Adds one or more elements to the end of an array.

### 2. pop()
Removes the last element from an array.

### 3. filter()
Creates a new array with elements that pass a test.

### 4. map()
Creates a new array by applying a function to each element.

### 5. forEach()
Executes a function on each array element and doesnot return a new array.



