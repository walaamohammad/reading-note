# Passing Functions as Props
# lists and keys
_____________________________________
____________________________________
* What does .map() return?

It will return an array with the same length of the looping array. with the same or new values.
If I want to loop through an array and display each value in JSX, how do I do that in React?

You have to use list to save the data in list item that has li elements, then you have to use ReactDOM.render and render data by ul element.
Each list item needs a unique *Key* .

* What is the purpose of a key?

to give the list a stable identity, and to make React knows which items have changed or edited or removed.
___________________________________
# spread operator
____________________________

* What is the spread operator?
##### It is … used to expand array items and combining arrays and objects and more things also.

# List 4 things that the spread operator can do.
* split array items to arguments.
* combining or copying arrays.
* adding items in React state.
* using arrays as arguments in math functions.
__________________________________
 Give an example of using the spread operator to combine two arrays.
* const array1 = [1,2,3] const array2 = [5,6,7] const array3=[…array1,…array2]
-Give an example of using the spread operator to add a new item to an array.
* Const array1 = [1,2,3] const array2 = […array1,3]
Give an example of using the spread operator to combine two objects into one.
* const obj1={name: ‘ahmad’} const obj2={age:’25’} const obj3={…obj1,…obj2}

____________________________________________
## passing functions between components
____________________________________
### In the video, what is the first step that the developer does to pass functions between components?
* He made an increment function and it looped over the array in the state by map.
### In your own words, what does the increment function do?
* It looping about an array called people by map method. then it will add one to the counter and change the state data by setState depending on the user click

### How can you pass a method from a parent component into a child component?
* by using props with the same function name in the child component. 4-How does the child component invoke a method that was passed to it from a parent component.
* by props. using this.props.propName.


______________________________
#### Things I want to know more about
* Still, I need more effort to understand React concepts well. Also, learning more about react Bootstrap.