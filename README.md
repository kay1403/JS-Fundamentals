````markdown
# JS-Fundamentals

Welcome to the **JS-Fundamentals** project!  
This repository contains JavaScript exercises to practice basic concepts such as variables, loops, functions, arguments, and console output.

## Learning Objectives

By completing these exercises, you should be able to:

- Explain why JavaScript programming is amazing
- Run JavaScript scripts
- Create variables and constants
- Understand the differences between `var`, `let`, and `const`
- Work with different data types
- Use `if`, `if...else` statements
- Use comments
- Assign values to variables
- Use `while` and `for` loops
- Use `break` and `continue`
- Define and call functions
- Understand return values
- Understand variable scope
- Use arithmetic operators
- Manipulate objects (dictionaries)
- Import files/modules

---

## Files and Scripts

### 0. `0-javascript_is_amazing.js`
Prints `"JavaScript is amazing"` using a constant.
```bash
node 0-javascript_is_amazing.js
````

---

### 1. `1-multi_languages.js`

Prints 3 lines for C, Python, and JavaScript.

```bash
node 1-multi_languages.js
```

---

### 2. `2-arguments.js`

Prints a message depending on the number of arguments:

* No argument → `"No argument"`
* One argument → `"Argument found"`
* More than one → `"Arguments found"`

```bash
node 2-arguments.js
```

---

### 3. `3-value_argument.js`

Prints the first argument passed or `"No argument"` if none.

```bash
node 3-value_argument.js [your_argument]
```

---

### 4. `4-concat.js`

Prints two arguments in the format: `"arg1 is arg2"`.

```bash
node 4-concat.js arg1 arg2
```

---

### 5. `5-to_integer.js`

Prints the first argument as an integer:

* If convertible → `"My number: <integer>"`
* Otherwise → `"Not a number"`

```bash
node 5-to_integer.js [number]
```

---

### 6. `6-multi_languages_loop.js`

Prints 3 languages using a loop and an array.

```bash
node 6-multi_languages_loop.js
```

---

### 7. `7-multi_c.js`

Prints `"C is fun"` multiple times:

* Number of repetitions = first argument
* If invalid → `"Missing number of occurrences"`

```bash
node 7-multi_c.js [number]
```

---

### 8. `8-square.js`

Prints a square of size X using `"X"` character:

* First argument = size of square
* If invalid → `"Missing size"`

```bash
node 8-square.js [size]
```

---

### 9. `9-add.js`

Adds two integers using a function `add(a, b)`:

```bash
node 9-add.js num1 num2
```

---

## How to Run

1. Make sure you have **Node.js** installed.
2. Open your terminal and navigate to the repository folder.
3. Run any script using:

```bash
node <script_name.js> [arguments]
```

---

## Notes

* Do **not** use `var`, only `let` and `const`.
* Use `console.log(...)` for all outputs.
* Use loops and functions as required.
* Handle argument conversion with `parseInt()` where needed.
* No try/catch is used; use `isNaN()` to handle invalid numbers.

---

## Author

Ange Koumba
