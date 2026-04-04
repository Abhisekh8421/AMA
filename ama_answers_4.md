# JavaScript AMA Answers

---

## Q1. Difference between `Promise.all()` and `Promise.any()`

* **Promise.all()**

  * Waits for all promises to finish
  * If **any one fails → whole thing fails**
  * Returns all results

* **Promise.any()**

  * Waits for **first successful promise**
  * Ignores failures until one succeeds
  * Fails only if **all promises fail**

---

## Q2. What is JSON Serialization and Deserialization?

* **Serialization**

  * Convert object → JSON string
  * Example:

    ```js
    JSON.stringify({name: "Abhi"})
    ```

* **Deserialization**

  * Convert JSON string → object
  * Example:

    ```js
    JSON.parse('{"name":"Abhi"}')
    ```

---

## Q3. What is REST?

* REST is a way to build APIs using HTTP
* Uses methods like:

  * GET → get data
  * POST → create data
  * PUT → update data
  * DELETE → delete data

---

## Q4. How to convert JSON to Object?

```js
const obj = JSON.parse('{"name":"Abhi"}');
```

---

## Q5. What is Live and Static Collection?

* **Live Collection**

  * Updates automatically when DOM changes
  * Example: `getElementsByClassName`

* **Static Collection**

  * Does NOT update automatically
  * Example: `querySelectorAll`

---

## Q6. Can we pass named arguments in JavaScript?

* No direct named arguments like other languages
* But we use **object** as workaround:

```js
function user({name, age}) {
  console.log(name, age);
}

user({name: "Abhi", age: 22});
```

---

## Q7. What is an Endpoint?

* A URL where API is accessed
* Example:

  ```
  /api/users
  ```

---

## Q8. Stateful vs Stateless API

* **Stateless**

  * Server does NOT store user data
  * Every request is independent
  * Example: HTTP

* **Stateful**

  * Server stores user data (session)
  * Example: login sessions

---

## Q9. Command to start Django project

```bash
django-admin startproject projectname
```

Run server:

```bash
python manage.py runserver
```

---

## Q10. What is an Event in DOM?

* Any action by user or browser
* Examples:

  * click
  * keypress
  * mouseover

---

## Q11. Is HTTP Stateless or Stateful?

* HTTP is **Stateless**
* Server does not remember previous requests

---

## Q12. Difference between Function and Module

* **Function**

  * A block of code to perform a task
  * Example:

    ```js
    function add(a, b) {
      return a + b;
    }
    ```

* **Module**

  * A file that contains multiple functions or code
  * Used to organize code

---


