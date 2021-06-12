## JavaScript Objects
_____________________________________________
You have already learned that JavaScript variables are containers for data values.
* Objects are variables too. But objects can contain many values.
* The values are written as name:value pairs (name and value separated by a colon).

* JavaScript objects are containers for named values called properties or methods.

_________________________-
## Object Properties
The name:values pairs in JavaScript objects are called properties.
Accessing Object Properties
You can access object properties in two ways:

objectName.propertyName
Object Methods
Objects can also have methods.

Methods are actions that can be performed on objects.

Methods are stored in properties as function definitions.
_____________________________________________
The this Keyword
In a function definition, this refers to the "owner" of the function.

In the example above, this is the person object that "owns" the fullName function.

In other words, this.firstName means the firstName property of this object.

Read more about the this keyword at JS this Keyword.

Accessing Object Methods
You access an object method with the following syntax
If you access a method without the () parentheses, it will return the function definition.
Do Not Declare Strings, Numbers, and Booleans as Objects!
When a JavaScript variable is declared with the keyword "new", the variable is created as an object
_________________________________________________________
## JavaScript HTML DOM
With the HTML DOM, JavaScript can access and change all the elements of an HTML document.

The HTML DOM (Document Object Model)
When a web page is loaded, the browser creates a Document Object Model of the page.

The HTML DOM model is constructed as a tree of Objects
![document object model](https://www.w3schools.com/js/pic_htmltree.gif)
