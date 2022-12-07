### Goal: Write your own “documentation” for the higher order functions
**Your documentation should include:**
- A description of the purpose
- A description of the syntax
- An example
- An explanation of the example
- Any additional notes/details

---
Your documentation here: 

# Higher-Order Functions

## Definiton

**Higher-Order Functions** are functions that *receive* another function as a parameter or return a function as a return value. Higher-order functions allow us to be more flexible with *how* we interact with our arguments.

### Syntax

```js
const variable;
const functionName = variable.iterative method(argument => {
  code
})

```js
const foods = ["Pizza", "Fried Chicken", "Patties", "Burgers", "Fries", "Red Velvet Cake"]; // Declared a variable with an array of string elements.

const foodsToEat = foods.map(food => `I want to eat ${food}`); // 
// `.map` is applied to the array `foods`, `foodsToEat` takes in the .map function.
console.log(foodsToEat) // logs "I want to eat Pizza", "I want to eat Fried Chicken", etc... to console.
```
