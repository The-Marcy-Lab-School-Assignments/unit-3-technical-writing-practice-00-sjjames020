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

A *Higher Order Function* is a funciton that operates on ther functions by taking them as arguments. These functions allow large amounts of data to be operated on. 

### Examples

``` javascript

function lessThan(n) { // Here we declare a function lessThan that checks if a given number is less than an integer and give it a parameter of n
  return m => m < n; 
}
  let lessThan8 = lessThan(8); // We create a variable lessThan8 and set it equal to the function lessThan with an argument of 8. 
console.log(lessThan8(10))  // We pass 10 into the function we created earlier and compare 8 to 10 using the function lessThan8.  

// -> false

```

Higher order functions allow us to abstract the details of a script. Abstraction allows us to focus on the what instead of the how. 

---
### Notes on Callback functions
Sometimes we use a function provided to a higher order function to be executed by the higher order function, this is called a callback function. Some examples of higher order methods include the `forEach()` method, `map()` method, and `filter()` method. The f`orEach()` method executes a provided function once for each array element. The `map()` method creates a new array populated with the results of calling a provided function on every element in the calling array. The `filter()` method creates a shallow copy of a portion of a given array, filtered down to just the elements from the given array that pass the test implemented by the provided function.

### forEach 

``` javascript
const numbers = [1, 2, 3, 4, 5]; // an array of numbers 

function addOne(array) {
  for (let i = 0; i < array.length; i++) { // iterate over a given array
    console.log(array[i] + 1); // logs the element of the array + 1 to the console
  }
}

addOne(numbers); // passes the array numbers into the fuction.

const numbers = [1, 2, 3, 4, 5]; // an array of numbers

numbers.forEach((number) => console.log(number + 1)); // for each element in the array numbers console.log that element + 1
```
These functions do the same task but the second function is simplified.

