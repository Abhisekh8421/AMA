# JavaScript AMA Answers

### Q1: What is a Promise?

A Promise is an object that represents a value that will come in the future.
It has 3 states:

* Pending (waiting)
* Resolved (success)
* Rejected (failed)

---

### Q2: How does setTimeout work?

`setTimeout` runs a function after a delay.
It does not block the code. It is handled by browser/Node and runs later using the event loop.

---

### Q3: What is Async JavaScript?

Async JavaScript means running code without blocking other code.
Example: API calls, timers.
It helps in doing multiple tasks smoothly.

---

### Q4: JavaScript is single-threaded or multi-threaded?

JavaScript is **single-threaded**.
But it can handle async tasks using the **event loop**.

---

### Q5: What is `this` keyword?

`this` refers to the object that is calling the function.

Example:

* In object → refers to object
* In normal function → refers to global (or undefined in strict mode)

---

### Q6: Explain forEach method

`forEach` is used to loop through an array.

Example:

```js
arr.forEach((item) => {
  console.log(item);
});
```

It does not return anything.

---

### Q7: Calling a parameterized function without arguments

If you don’t pass arguments, parameters become `undefined`.

Example:

```js
function test(a) {
  console.log(a);
}
test(); // undefined
```

---

### Q8: What happens if we use Promise.all() with 4 promises?

* If all promises succeed → returns all results
* If one fails → it immediately fails

---

### Q9: What is TLE?

TLE = Time Limit Exceeded
It means your code is too slow and did not finish in given time.

---

### Q10: What is Rest Operator?

Rest operator (`...`) collects multiple values into one array.

Example:

```js
function sum(...nums) {
  console.log(nums);
}
```

---

### Q11: If we return in catch, will finally execute?

Yes, `finally` will always execute.

---

### Q12: What is Node.js?

Node.js is a runtime that allows you to run JavaScript outside the browser.

---

### Q13: What are Template Literals?

Template literals use backticks (`` ` ``) and allow variables inside strings.

Example:

```js
let name = "John";
console.log(`Hello ${name}`);
```

---

### Q14: Output of console.log("2" + 2)

Output: `"22"`
Because string + number → string

---

### Q15: What is Higher Order Function?

A function that:

* takes another function as argument OR
* returns a function

Example:

```js
function test(fn) {
  fn();
}
```

---
