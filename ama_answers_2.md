### Q1) What is `DATE_TRUNC`?

`DATE_TRUNC` is a SQL function used to cut a date/time to a specific part like year, month, or day.
It removes the smaller parts of the timestamp.
Example: `DATE_TRUNC('month', timestamp_column)` gives the first day of that month.

---

### Q2) How to extract date from timestamp?

You can use `DATE()` function.
Example: `SELECT DATE(timestamp_column);`
It removes the time part and shows only the date.

---

### Q3) What is `ROUND()` function in SQL?

`ROUND()` is used to round a number to a specific decimal place.
Example: `ROUND(12.456, 2)` → `12.46`.
It helps in formatting numeric results.

---

### Q4) What are indexes in SQL?

Indexes are used to make data searching faster.
They work like an index in a book.
They improve `SELECT` query performance.

---

### Q5) How to make a link to an image in HTML?

Use `<a>` tag with `<img>` inside it.
Example:

```html
<a href="https://example.com">
  <img src="image.jpg">
</a>
```

Clicking the image will open the link.

---

### Q6) What is commit and rollback in Git?

`Commit` saves your changes permanently in Git.
`Rollback` means undoing changes (using commands like `git reset`).
Commit stores changes, rollback removes them.

---

### Q7) What are inline and block elements in HTML?

Block elements take full width (like `<div>`, `<p>`).
Inline elements take only required width (like `<span>`, `<a>`).
Block starts on new line, inline does not.

---

### Q8) How to read from file in Python?

Use `open()` function.
Example:

```python
file = open("data.txt", "r")
content = file.read()
```

It reads the file content.

---

### Q9) What is list in HTML?

Lists are used to show items.
There are two types: ordered `<ol>` and unordered `<ul>`.
Items are written using `<li>` tag.

---

### Q10) Different types of CSS

1. Inline CSS – inside HTML tag.
2. Internal CSS – inside `<style>` tag.
3. External CSS – separate `.css` file.

---

### Q11) What is `<br>` tag in HTML?

`<br>` is used to break a line.
It moves content to the next line.
It does not need a closing tag.

---

### Q12) What is CTE in SQL?

CTE (Common Table Expression) is a temporary result set.
It is written using `WITH` keyword.
It makes complex queries easier to read.

---

### Q13) What is Deadlock in SQL?

Deadlock happens when two transactions wait for each other.
Both are blocked and cannot continue.
The database cancels one transaction to solve it.

---

### Q14) Which is faster: TRUNCATE or DELETE?

`TRUNCATE` is faster than `DELETE`.
It removes all rows quickly.
`DELETE` removes rows one by one.

---

### Q15) What is iframe in HTML?

`<iframe>` is used to show another webpage inside a webpage.
Example: embedding YouTube video.
It loads external content.

---

### Q16) What is padding and margin?

Padding is space inside the element (around content).
Margin is space outside the element (around border).
Padding affects inside spacing, margin affects outside spacing.
