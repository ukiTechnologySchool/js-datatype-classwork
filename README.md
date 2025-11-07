# JavaScript Data Types, Methods & Real-World Relevance – Classwork

##  Overview
This classwork explores **JavaScript primitive data types**, **arrays**, **objects**, and their **methods** and **properties**.  
Each group will research, prepare code examples, and present **real-world use cases**.

---

## Group Allocation

| Group | Topic | Subtopics |
|-------|--------|------------|
| 1 | **Numbers & Strings** | Number methods & properties, String methods & properties |
| 2 | **Math & Loops** | Math methods, `for`, `while`, `do...while` loops |
| 3 | **Operators & Conditions** | Arithmetic, Assignment, Comparison, Logical, Conditional, Type operators, If/Else & Switch |
| 4 | **Date, Null, Undefined, BigInt, Symbol** | Working with date/time, handling empty/unknown values |
| 5 | **Objects** | Object creation, methods, and manipulation |
| 6 | **Arrays** | Array properties, methods, and iteration |

---

## Tasks & Deliverables
Each group must:
1. **Explore** assigned topics using documentation and examples.  
2. **Create** a 5–7 minute presentation including:
   - Short theory explanation  
   - **practical examples** (with code)  
   - **Real-world relevance question** (how this is used in real apps)
3. **Upload** a `.md` or `.js` file with examples to this repository.

---

##  Real-World Relevance Questions
Each group will explore one set of JavaScript concepts through **real-world scenarios**, **hands-on tasks**, and **example outputs**.  
Your goal is to understand **how data types, methods, and properties are applied in real projects**.

---

## Group 1 — Numbers & Strings

### 🔹 Real-World Scenario:
You are developing a **shopping cart** that calculates discounts and formats customer names before printing the receipt.

###  Tasks
- Use `toFixed()` to round total price values.  
- Use `parseInt()` and `Number.isNaN()` to handle numeric conversions.  
- Use string methods like `trim()`, `toUpperCase()`, and `slice()` to clean and display names.

### Example Output:
```
Total Price: 99.99 → Rounded: 100
Customer Name: "   niroobana  " → "NIROOBANA"
```

---

## Group 2 — Math & Loops

### Real-World Scenario:
You are designing a **fitness tracker** that calculates and displays daily calorie burn for 7 days.

### Tasks
- Use `Math.random()` and `Math.round()` to simulate daily calorie values.  
- Use a `for` loop to print each day’s data.  
- Use a `while` or `do…while` loop to calculate total calories burned.

### Example Output:
```
Day 1: Calories = 1740
Day 2: Calories = 1823
Total Calories in Week: 12345
```

---

## Group 3 — Operators & Conditions

### Real-World Scenario:
You are building a **student grading system** that checks pass/fail status and provides feedback based on marks.

### Tasks
- Use arithmetic operators (+, /) to compute total and average marks.  
- Use comparison (>=) and logical (&&, ||) operators to decide pass/fail.  
- Use the conditional (? :) operator or `if…else` statement to print messages.

### Example Output:
```
Average Mark: 72.5
Result: Pass
Feedback: "Good Job!"
```

---

## Group 4 — Date, Null, Undefined, BigInt, Symbol

### Real-World Scenario:
You are creating a **system log generator** for a website.

### Tasks
- Use `Date()` to display current date and time when a user logs in.  
- If a field value is missing, print `"No Data"` instead of `undefined`.  
- Use `BigInt` for large transaction IDs (e.g., 987654321012345678901n).  
- Use `Symbol()` to create a unique session ID for each login.

###  Example Output:
```
Login Time: 2025-11-07 10:15:23
User ID: 987654321012345678901n
Session ID: Symbol(userSession)
Status: No Data
```

---

## Group 5 — Objects

### Real-World Scenario:
You are managing an **employee database** that stores and retrieves employee details.

### Tasks
- Create an object with properties: `name`, `role`, and `salary`.  
- Use `Object.keys()` and `Object.values()` to display details.  
- Add a method to calculate yearly salary.

### Example Output:
```
Employee: Kaviya
Keys: ["name", "role", "salary"]
Yearly Salary: 1020000
```

---

##  Group 6 — Arrays

### Real-World Scenario:
You are developing a **movie-rating app** that filters and displays top-rated movies.

### Tasks
- Create an array of objects containing `title` and `rating`.  
- Use `filter()` to select movies with rating > 7.  
- Use `map()` or `forEach()` to print movie titles.

### Example Output:
```
All Movies: ["Inception", "Avatar", "Flash"]
Top Rated: ["Inception"]
Count of Top Movies: 1
```
---

## Submission Format
- Folder name: `Group<number>_<topic>`
- Inside each folder:
  - `README.md` – Summary and explanations  
  - `examples.js` – Your code examples
  - `pratical.js`-Your Real-World Relevance Questions 

---

## Presentation Evaluation

| Criteria | Description | Marks |
|-----------|--------------|--------|
| Content Understanding | Explains methods, syntax & purpose clearly | 20 |
| Real-World Relevance | Demonstrates practical usage | 20 |
| Code Accuracy | Examples work correctly | 20 |
| Presentation Skills | Confidence, clarity, timing | 20 |
| Creativity | Extra examples or visualization | 20 |
| **Total** |  | **100** |

---

##  Resources
- [MDN JavaScript Reference](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference)
- [W3Schools JavaScript](https://www.w3schools.com/js/)
- [JavaScript.info](https://javascript.info)

---

### Tip for Students
Use `console.log()` and VS Code Live Server to test and visualize outputs before presenting.

```
