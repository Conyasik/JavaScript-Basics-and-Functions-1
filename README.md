// 1. Console Log Basics
console.log("Hello, Code the Dream!");

// 2. Variable Declarations
const myName = "Adusha";
let age = 36;
const hasKids = true;

console.log("Name:", myName);
console.log("Age:", age);
console.log("Has kids?", hasKids);
console.log("Type of 'hasKids':", typeof hasKids);

// 3. Basic Math and Strings
const num1 = 10;
const num2 = 5;
const sum = num1 + num2;

console.log("Sum:", sum);
console.log(`${num1} + ${num2} = ${sum}`);

// 4. Functions
function greet(name) {
  return `Hello, ${name}!`;
}

console.log(greet("Adusha"));

// 5. Nested Functions (Revised and Fully Tested)
function double(num) {
  return num * 2;
}

function tripleThenDouble(num) {
  const tripled = num * 3;
  const doubled = double(tripled);
  return doubled;
}

// 🔁 Test cases for tripleThenDouble function
console.log("Test with positive number (5):", tripleThenDouble(5));     // Expected: 30
console.log("Test with small positive number (2):", tripleThenDouble(2)); // Expected: 12
console.log("Test with zero (0):", tripleThenDouble(0));               // Expected: 0
console.log("Test with negative number (-3):", tripleThenDouble(-3));  // Expected: -18
console.log("Test with large number (100):", tripleThenDouble(100));   // Expected: 600

// 6. Math Object Examples
const negative = -42;
console.log("Absolute value:", Math.abs(negative));
console.log("Rounded value:", Math.round(3.6));
console.log("Random number (0-1):", Math.random());
