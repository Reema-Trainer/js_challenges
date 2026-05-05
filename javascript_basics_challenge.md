# JavaScript Basics — Real World Challenges

## Topics Covered
- Variables (`var`, `let`, `const`)
- Data Types
- Arithmetic Operators
- Assignment Operators
- Unary Plus & Negation
- Math Object
- String Methods
- Type Conversion
- Random Numbers
- Arrays & Objects
- Template Literals

---

# Challenge #1 — Student Registration System

You are building a small system for a training center.

## Requirements
1. Create these variables:
- student name
- birth year
- course name
- monthly fee
- isRegistered

2. Use:
- `let`
- `const`
- `var`

correctly depending on whether values may change or not.

3. Calculate:
- current age
- yearly payment (`monthly fee * 12`)

4. Print a professional message using:
- concatenation `+`
- template literals `` ``

## Bonus
- Try accessing a `var` variable before declaration.
- Try accessing a `let` variable before declaration.
- Explain the difference.

---

# Challenge #2 — Online Store Discount Calculator

You are creating an e-commerce system.

## Requirements

```js
const productName = "Laptop";
let productPrice = "4500";
let discount = 15;
```

1. Convert price from string to number.

2. Calculate:
- discount value
- final price after discount

3. Print:

```txt
Product: Laptop
Old Price: 4500
Discount: 15%
Final Price: 3825
```

## Bonus
- Round final price to 2 decimal places.
- Add `$` after price.

---

# Challenge #3 — Weather Dashboard

Create a mini weather system.

## Requirements

```js
let city = "Gaza";
let temperature = -3.7;
let isRaining = true;
```

Use:
- `Math.abs()`
- `Math.round()`
- `Math.floor()`
- `Math.ceil()`

Print weather details professionally.

## Bonus
If temperature is below `0`, print:

```txt
Warning: Freezing weather!
```

---

# Challenge #4 — Username Cleaner

You are validating usernames before account creation.

## Requirements

```js
let username = "    ReEma_AsKer   ";
```

Use:
- `trim()`
- `toLowerCase()`
- `toUpperCase()`
- `charAt()`

## Output Example

```txt
Original Username:     ReEma_AsKer
Clean Username: reema_asker
First Letter: r
```

## Bonus
Print the username in ALL CAPS.

---

# Challenge #5 — Product Search Engine

You are building search functionality.

## Requirements

```js
let products = "phone-laptop-tablet-camera-headphones";
```

Use:
- `indexOf()`
- `lastIndexOf()`
- `slice()`
- `substring()`
- `split()`

## Tasks
1. Find the position of `"camera"`.
2. Extract `"laptop"`.
3. Convert products into array.
4. Print the last product.

---

# Challenge #6 — Banking System

Simulate a bank account.

## Requirements

```js
let balance = 1000;
```

Apply:
- deposit
- withdrawal
- multiplication for yearly savings

Use:
- `+=`
- `-=`
- `*=`

## Example

```js
balance += 500;
balance -= 200;
```

## Bonus
Use increment and decrement operators:

```js
++balance;
balance--;
```

---

# Challenge #7 — Password Strength Checker

Create a password validation system.

## Requirements

```js
let password = "  Pass1234  ";
```

## Check:
- Remove spaces
- Password length
- First character
- Convert to uppercase
- Convert to lowercase

## Bonus
Print:

```txt
Strong Password
```

if length > 8.

---

# Challenge #8 — Random Dice Game

Create a dice game between two players.

## Requirements

```js
let player1 = Math.trunc(Math.random() * 6) + 1;
let player2 = Math.trunc(Math.random() * 6) + 1;
```

## Tasks
1. Print both numbers.
2. Print the winner.
3. Print the difference.

## Bonus
If numbers are equal:

```txt
Draw!
```

---

# Challenge #9 — Employee Salary System

You are managing employees.

## Requirements

```js
let employeeName = "Ahmad";
let salary = 5500.756;
```

## Tasks
1. Print salary with:
- `toFixed(2)`

2. Convert salary to string.

3. Print number of digits in salary.

4. Print:

```txt
Employee Ahmad earns 5500.76$
```

---

# Challenge #10 — Smart Text Analyzer

## Requirements

```js
let sentence = "JavaScript is amazing";
```

## Tasks
1. Print:
- first character
- last character
- sentence length

2. Convert sentence:
- uppercase
- lowercase

3. Extract:

```txt
JavaScript
```

4. Repeat sentence 3 times using:

```js
repeat()
```

---

# Challenge #11 — University GPA Calculator

A university wants a GPA helper.

## Requirements

```js
let math = 95;
let programming = 88;
let algorithms = 91;
```

## Tasks
1. Calculate:
- total
- average

2. Use:
- `Math.round()`
- `Math.floor()`
- `Math.ceil()`

3. Print grade:
- A
- B
- C

Depending on average.

---

# Challenge #12 — Restaurant Bill Splitter

You are creating a restaurant app.

## Requirements

```js
let totalBill = 275.80;
let people = 4;
```

## Tasks
1. Calculate:
- each person payment
- tax (10%)
- final total

2. Round values properly.

3. Print formatted receipt.

---

# Mega Challenge — Mini E-Commerce Console App

Combine EVERYTHING.

## Requirements
Build a small console-based shopping system.

## Features
- Product name
- Product category
- Product price
- Quantity
- Discount
- Tax
- Final price
- Username formatting
- Random coupon generator
- Product search
- String methods
- Math methods
- Type conversion

## Example Output

```txt
Welcome REEMA

Product: Laptop
Category: Electronics
Price: 5000$
Quantity: 2
Discount: 10%
Tax: 5%

Final Total: 9450$

Coupon Code: SALE25
```

## Advanced Bonus
Add:
- random order number
- date
- password checker
- stock availability
- shipping calculator
- loyalty points system

