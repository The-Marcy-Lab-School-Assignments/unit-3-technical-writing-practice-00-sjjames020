### Goal: Write your own “documentation” for the higher order functions
**Your documentation should include:**
- A description of the purpose
- A description of the syntax
- An example
- An explanation of the example
- Any additional notes/details

---
Your documentation here: 
# What is a Higher Order Function ?

A *Higher Order Function* is a funciton that operates on ther functions by taking them as arguments. 

### Example 

``` javascript

function lessThan(n) { // Here we declare a function lessThan that checks if a given number is less than an integer and give it a parameter of n
  return m => m < n; 
}
  let lessThan8 = lessThan(8); // We create a variable lessThan8 and set it equal to the function lessThan with an argument of 8. 
console.log(lessThan8(10))  // We pass 10 into the function we created earlier and 

// -> false

```

Higher order functions allow us to abstract the details of a script. Abstraction allows us to focus on the what instead of the how. 

