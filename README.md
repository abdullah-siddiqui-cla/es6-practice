# 1. Arrow Functions
Exercise: Rewrite the function below using an arrow function.

```
function multiply(a, b) {
  return a * b;
}
```

Solution Idea: Convert multiply into an arrow function:

# 2. Default Parameters
Exercise: Create a function greet that takes two arguments: name and greeting. If no greeting is provided, it should default to "Hello".

```
greet("Alice"); // "Hello, Alice"
greet("Alice", "Hi"); // "Hi, Alice"
```

Solution Idea: Use default parameters for greeting.


# 3. Destructuring
Exercise: Extract values from the object user and log them individually.

```
const user = {
  name: "John",
  age: 25,
  location: "New York"
};
```

Solution Idea: Use destructuring to extract the values.

# 4. Spread and Rest Operators
Exercise: Write a function sum that takes any number of arguments and returns their sum.

```
sum(1, 2, 3); // 6
sum(4, 5);    // 9
```

Solution Idea: Use the rest operator to handle a variable number of arguments.


# 5. Template Literals
Exercise: Create a function introduce that takes name and age as parameters and returns a sentence like "Hello, my name is [name] and I am [age] years old."

introduce("Alice", 30); // "Hello, my name is Alice and I am 30 years old."

Solution Idea: Use template literals to format the sentence.

# 6. Map, Filter, and Reduce
Exercise: Given an array of numbers, return a new array with only the even numbers, each multiplied by 2.

```
const numbers = [1, 2, 3, 4, 5, 6];
```

Solution Idea: Use filter to get even numbers and map to multiply them by 2.

javascript
Copy code
const result = numbers.filter(num => num % 2 === 0).map(num => num * 2);
console.log(result); // [4, 8, 12]

# 7. Promises and Async/Await
Exercise: Write a function fetchData that returns a promise that resolves with "Data fetched!" after 2 seconds. Then, create an async function getData that uses fetchData and logs the resolved value.

javascript
Copy code
getData(); // After 2 seconds: "Data fetched!"

Solution Idea: Define fetchData to return a delayed promise, and use await in getData.
### Hint: Use `setTimeout` method to wait for 2 seconds and call the `resolve` method in the callback.
