1. Which keywords are used to declare a variable in JavaScript?

-let, var, and const.


2. What is the definition of a function?
-A set of statements that has a task and a value.


3. What are the SOLID principles?

Single responsibiltiy, Open closed principle, Liskov substition principle, Interface segregation principle, and Dependency inversion priciple.


4. Given this array:

let fruit = ['apple', 'banana', 'pineapple',  'orange', 'strawberry']
What index is the pineapple's current position? How do you know?

-fruit[2]. I know because the pineapple is the 2nd value (from 0) in the fruit array.


5. With these two objects:

let you = { name:"You", hair: true, friends: [] }
let them = { name:"Them", hair: false, friends: [] }
how would you .push the them object into the you object's array of friends?

-them.prototype.push.apply(you, them)


6. Give an example of a JavaScript Conditional:

if(10 < 20){
  console.log("10 is less than 20")
}

(10 < 20) is the conditional.


7. In the for loop below, what is the name of the piece belongs inside the empty "______" space? What would you put here to increase i by one on every iteration?

for ( let i = 0; i < arr.length; _______ ) {
  //...

  -It is an incrementor. It takes whatever i is and adds 1 to it.

8. What does the DOM acronym stand for? Which file is first accessed to render the DOM?
-Document Object Model. HTML.


9. What are the 9 ECMAScript types as defined by MDN?
-Numbers, functions, booleans, Symbol, BigInt, String, null, undefined, Object.


10. When it comes to functions or methods, what is the difference between a parameter and an argument?
-Arguments are passed in a function. Parameters are names listed within the function.



11. What is the difference between a primitive value and a reference value?
-Primitives (null, boolean, string, undefined) are stored in the stack and references are objects in the heap.