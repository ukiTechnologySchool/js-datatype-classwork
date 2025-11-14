# JavaScript Practical Question Bank
### Covers Core + ES6–ES2021 Concepts

---

## Numbers & Strings

**Core + ES6–ES2021 Concepts:**
- Number, parseInt(), isNaN(), toFixed(), template literals, String.prototype.replaceAll(), padStart(), padEnd(), string interpolation.

### Practice Questions
1. Write a program to round a floating number to 2 decimals and display it with a currency symbol using template literals.  
2. Get a user’s full name and display it in uppercase without extra spaces.  
3. Format a receipt like:`Item: Keyboard
Price: Rs 250.00`
(padEnd() for alignment.)  
4. Convert "123abc" safely to a number and handle NaN using Number.isNaN().  
5. Create a function that takes a list of product prices and returns the total with commas (e.g., 1,234.56).  
6. Clean unwanted characters from a text input like "hello@@world@@!".  

---

## Math & Loops

**Core + ES6–ES2021 Concepts:**
- Math.random(), Math.max(), Math.min(), Math.trunc(), for...of, for...in, forEach(), continue, break.

### Practice Questions
1. Generate 10 random integers between 1 and 100 using Math.random() and Math.floor().  
2. Find the largest and smallest value in an array using Math.max() and the spread operator.  
3. Write a for...of loop to calculate the sum of array values.  
4. Display numbers from 1 to 50 but skip multiples of 5 using continue.  
5. Use a do...while loop to simulate login attempts until the correct password is entered.  
6. Create a multiplication table using nested for loops.  

---

## Operators & Conditions

**Core + ES6–ES2021 Concepts:**
- Arithmetic, assignment, comparison, logical, ternary (? :), ??, optional chaining (?.).

### Practice Questions
1. Compare two student scores and display who passed using the ternary operator.  
2. Use logical operators (&&, ||) to check eligibility for a loan based on income and age.  
3. Use the nullish coalescing operator (??) to assign a default username.  
4. Demonstrate optional chaining (?.) when accessing nested object properties.  
5. Create a simple grading system using if...else and print A/B/C/D/F grades.  
6. Evaluate multiple expressions and log both result and type.  

---

## Date, Null, Undefined, BigInt, Symbol

**Core + ES6–ES2021 Concepts:**
- Date, timestamp operations, optional chaining, BigInt, Symbol, nullish coalescing, timezone formatting.

### Practice Questions
1. Display current date and time in readable format (YYYY-MM-DD HH:MM:SS).  
2. Calculate how many days remain until New Year.  
3. Use BigInt to store a large ID (e.g., transaction number) and perform addition.  
4. Create two Symbol() values and show that they are unique.  
5. Demonstrate difference between null and undefined with examples.  
6. Use Intl.DateTimeFormat to format date according to your locale.  
7. Store a log entry with timestamp and unique Symbol ID.  

---

# Objects

**Core + ES6–ES2021 Concepts:**
- Object destructuring, shorthand property names, spread & rest in objects, Object.keys(), Object.values(), Object.entries(), Object.fromEntries(), optional chaining.

## Practice Questions
## Part 1
---
### **1.How do you create an empty JavaScript object?**

Write a JavaScript statement to create an empty object named `person`.

---

### **2. Create an Object with Properties and Methods**

Write a JavaScript program to create an object called **`person`** with properties **`name`** and **`age`**.  
Then, create a **function inside the object** called **`IntroduceYou`** that takes a `person` object as a parameter and logs a message to the console.  

**Example Output:**
```
Hi, I am John and I am 25 years old.
```

---

### **3. Create a Method that Greets Students**

Create a function inside the **`person`** object called **`greetStudent`** that takes a `student` object as a parameter and logs this message:  
```
Hello <person name>, Welcome to the Coding School!
```

---

### **4. Access Object Properties**

Write a JavaScript program to access object properties using **dot notation** and **bracket notation**.  

---

### **5. Add a New Property**

Write a JavaScript program to **add a new property** to an existing object.  
Add a new property **`email`** with the value `"shan@example.com"` to the `person` object.

---

### **6. Remove a Property**

### Write a JavaScript program to **remove a property** from an object using the `delete` keyword.  
---

### **7. Check Property Existence**

Write a JavaScript program to **check whether a property exists** in an object using the `in` operator or `hasOwnProperty()` method.

**Example:**
```js
console.log("name" in person);
```

---

### **8. Merge Two Objects**

Create two objects, **`student`** and **`course`**, and merge them into a new object named **`studentCourse`** using the **spread operator** or **`Object.assign()`**.

---

### **9. Check for a Specific Property**

Write a program to check if an object has a specific property named **`address`**.  
If it exists, log `'Address is there'`, otherwise log `'Address not found'`.

**Example:**
```js
if ("address" in person) {
  console.log("Address is there");
} else {
  console.log("Address not found");
}
```

---

### **10. Convert Object to JSON**

Create an object **`book`** with properties `title`, `author`, and `year`.  
Then convert it into a **JSON string**.

---

### **11. Array of Objects**

Create an **array of objects** called **`students`**.  
Each object in the array should have the following properties:

| Property | Type   | Example Value |
|-----------|--------|----------------|
| name      | string | "Asha"         |
| age       | number | 21             |
| gpa       | number | 3.7            |

## Part 2
1. Create an object representing a student and destructure name and age.  
2. Use shorthand syntax to create an object inside a function.  
3. Clone and update an object using the spread operator {...}.  
4. Convert an object to array using Object.entries() and back using Object.fromEntries().  
5. Write a method inside an object that calculates tax based on salary.  
6. Use optional chaining to access a nested property safely.  
7. Merge two objects (e.g., user info and contact info).  

---

## Arrays

**Core + ES6–ES2021 Concepts:**
- map(), filter(), reduce(), find(), findIndex(), flat(), flatMap(), spread [...], rest ...args, destructuring, Array.from(), includes(), at() (ES2022).
### Part 1
## JavaScript Array Questions – 
## Based on numbers = [1, 2, 36, 7]

---

### **1. Access First and Last Elements**

Write a JavaScript program to access the **first** and **last** elements of the `numbers` array.

---
### **2. Add Elements**

Write a JavaScript program to **add a new number** at the **end** and **beginning** of the `numbers` array.

---
### **3. Remove Elements**

Write a JavaScript program to **remove the first and last elements** from the `numbers` array.

---

### **4. Loop Through Array**

Write a JavaScript program to **loop through the `numbers` array** and print each element using a `for` loop.

---

### **5. Use forEach()**

Write a JavaScript program to **loop through the `numbers` array** using the **`forEach()`** method.

---

### **6.  Find Maximum and Minimum**

Write a JavaScript program to find the **maximum** and **minimum** values in the `numbers` array.

---

### **7. Check for Element**

Write a JavaScript program to **check whether the number `36` exists** in the `numbers` array.

---

### **8. Sum of Elements**

Write a JavaScript program to calculate the **sum of all numbers** in the `numbers` array.

---

### **9. Sort Array**

Write a JavaScript program to **sort the `numbers` array** in ascending order.

---

### **10. Reverse Array**

Write a JavaScript program to **reverse the `numbers` array**.

---

### **11. Filter Numbers**

Write a JavaScript program to **create a new array** containing only numbers **greater than 5** from the `numbers` array.


### Part 2

* Array creation and access
* forEach(), map(), filter(), reduce(), reduceRight()
* find(), includes()
* Spread operator [...], Rest parameter (...args)
* Destructuring, Nested arrays, flat(), flatMap()

## Practice Questions
1. Create and Access Arrays
Sample Array: [10, 15, 20, 25, 30]
Access the first and last element.

2. Filter and Find
Sample Array: [10, 15, 20, 25, 30] 
Filter the array to return only even numbers.

3.Find the student with grade "A".
Sample Array:
const students = [
  { name: 'Alice', grade: 'B' },
  { name: 'Bob', grade: 'A' },
  { name: 'Charlie', grade: 'C' }
];

4. Calculate the sum of all numbers using reduce().
Sample Array: [10, 15, 20, 25, 30] 

4. Merge the two arrays using the spread operator.
Sample Arrays: [1,2,3] and [4,5,6] 

5. Extract the first two elements using destructuring.
Sample Array: [100, 200, 300, 400] 

6. Flatten the nested array using flat().
Sample Array: [[1,2],[3,4],[5,6]] 

7. Rest Parameter
Create a function average(...scores) that returns the average of any number of scores.

8. Check if the number 25 exists in the array using includes().
Sample Array: [10, 15, 20, 25, 30] 

9. Convert the string to an array of characters using Array.from().
Sample String: 'HELLO'
 
10. Access the last element using .at(-1).
Sample Array: [5,10,15,20,25] 
