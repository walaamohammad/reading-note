### links
Links are the defining feature of the web
because they allow you to move from
one web page to another — enabling the
very idea of browsing or surfing.
You will commonly come across the following types of links:
● Links from one website to another
● Links from one page to another on the same website
● Links from one part of a web page to another part of the
same page
● Links that open in a new browser window
● Links that start up your email program and address a new
email to someone
![links](https://i.dlpng.com/static/png/7183819_preview.png)

______________________________________
Absolute URLs vs. Relative URLs
Both examples above are using an absolute URL (a full web address) in the href attribute.

A local link (a link to a page within the same website) is specified with a relative URL (without the "https://www" part)
________________________
* Use the <a> element to define a link
* Use the href attribute to define the link address
* Use the target attribute to define where to open the linked document
* Use the <img> element (inside <a>) to use an image as a link
* Use the mailto: scheme inside the href attribute to create a link that opens the user's email program

__________________________________________
## css layout
________________________________

CSS has the following positioning schemes that allow you to control
the layout of a page: normal flow, relative positioning, and absolute
positioning. You specify the positioning scheme using the position
property in CSS. You can also float elements using the float property
* Normal flow
Every block-level element
appears on a new line, causing
each item to appear lower down
the page than the previous one.
Even if you specify the width
of the boxes and there is space
for two elements to sit side-byside, they will not appear next
to each other. This is the default
behavior (unless you tell the
browser to do something else).
* Relative Positioning
This moves an element from the
position it would be in normal
flow, shifting it to the top, right,
bottom, or left of where it
would have been placed. This
does not affect the position of
surrounding elements; they stay
in the position they would be in
in normal flow.
* Absolute positioning
This positions the element
in relation to its containing
element. It is taken out of
normal flow, meaning that it
does not affect the position
of any surrounding elements
(as they simply ignore the
space it would have taken up).
Absolutely positioned elements
move as users scroll up and
down the page.
___________________________________________
### JavaScript Function Definitions
avaScript functions are defined with the function keyword.
You can use a function declaration or a function expression.
function functionName(parameters) {
  // code to be executed
}
All Functions are Methods
In JavaScript all functions are object methods.

If a function is not a method of a JavaScript object, it is a function of the global object (see previous chapter).

The example below creates an object with 3 properties, firstName, lastName, fullName.
________________________________________
In JavaScript, almost "everything" is an object.

Booleans can be objects (if defined with the new keyword)
Numbers can be objects (if defined with the new keyword)
Strings can be objects (if defined with the new keyword)
Dates are always objects
Maths are always objects
Regular expressions are always objects
Arrays are always objects
Functions are always objects
Objects are always objects
All JavaScript values, except primitives, are objects.
_______________________________________________
String Methods and Properties
Primitive values, like "John Doe", cannot have properties or methods (because they are not objects)
But with JavaScript, methods and properties are also available to primitive values, because JavaScript treats primitive values as objects when executing methods and properties.