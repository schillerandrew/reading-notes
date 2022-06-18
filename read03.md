> # Express REST API

> ## ES6 Classes

&nbsp;

> 1. Classes are a template for creating?

objects

> 2. Can a class declaration be hoisted?

No.

> 3. How would you describe a constructor and contextual "this" to a non-technical friend? 

A constructor is a simple template for an object, and you can use the constructor to create copies that follow the template. Contextual "this" is a way to assign properties to the objects (the copies) that you create.

> ### Two ways to define a class:

### [Class declaration](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Classes#defining_classes)

``` js
class Rectangle {
  constructor(height, width) {
    this.height = height;
    this.width = width;
  }
}
```

### [Class expression](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Classes#defining_classes)

``` js
// unnamed
let Rectangle = class {
  constructor(height, width) {
    this.height = height;
    this.width = width;
  }
};
console.log(Rectangle.name);
// output: "Rectangle"

// named
let Rectangle = class Rectangle2 {
  constructor(height, width) {
    this.height = height;
    this.width = width;
  }
};
console.log(Rectangle.name);
// output: "Rectangle2"
```

> ## Using Express Routing

&nbsp;

> 1. Within Express, what does routing refer to?

how an application's endoints (URIs) respond to client requests

> 2. What is the difference between a route path and a route method?

The route method determines which HTTP method will be used in the server request, whereas the route path defines the endpoint, especially in terms of taking in request parameters and request queries from the user/client.

path = `/get`, `/post`, etc

method = `?name=Andrew`, `/1`, etc

> 3. When is it appropriate to add `next` as a parameter to a route handler and what must you do if `next` has been passed to your middleware as a parameter?

The `next` paramter is useful when there are multiple callbacks, to pass control from callback to callback, but to do that you must remember to invoke the next callback in the function, using the syntax `next()`.

- `app.all()` = handles all HTTP (REST) methods
- `app.use()` = specify middleware as the callback (handler) function

> ## Express Routing

&nbsp;

> 1. What is an Express Router?

a mini-Express app that only provides routing functionality (`.use`, `.get`, etc)

> 2. By what means do we initialize express.Router() in an Express server?

We create an instance of `Router`.

> 3. What do we use route middleware for?

anything that should occur before a request is responded to, such as user authentication or logging