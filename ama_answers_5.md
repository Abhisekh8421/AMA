#  AMA Answers


## Q1: What is CAP Theorem?

CAP theorem states that a distributed system can only guarantee **2 out of 3** properties:

- **C (Consistency):** All nodes see the same data at the same time  
- **A (Availability):** Every request gets a response (success/failure)  
- **P (Partition Tolerance):** System continues working even if network fails  

 You can choose:
- CP (Consistency + Partition tolerance)
- AP (Availability + Partition tolerance)

But **not all three together**.

---

## Q2: What is User Authentication?

User authentication is the process of verifying **who the user is**.

Example:
- Login using **username + password**
- System checks if credentials match stored data

Types:
- Password-based
- OTP-based
- OAuth (Google login)

---

## Q3: What is the need of venv folder?

`venv` (virtual environment) is used to:
- Isolate project dependencies
- Avoid conflicts between projects
- Keep packages separate

 Example:
Project A → Django 3  
Project B → Django 5  
Both can run without conflict using venv

---

## Q4: What is Django-admin?

`django-admin` is a command-line tool used to:
- Create Django project → `django-admin startproject`
- Manage project tasks

 It helps in **initial setup and management** of Django projects.

---

## Q5: Difference between Session and Cookies

| Feature     | Cookies                      | Sessions                      |
|------------|-----------------------------|------------------------------|
| Storage     | Stored in browser           | Stored on server             |
| Security    | Less secure                 | More secure                  |
| Size        | Limited (~4KB)              | No strict limit              |
| Speed       | Faster (client-side)        | Slightly slower              |

---

## Q6: What are Aggregations?

Aggregation means **performing calculations on data**.

Examples:
- COUNT()
- SUM()
- AVG()
- MAX(), MIN()

 Used in databases to summarize data.

Example:
Total users = COUNT(users)

---

## Q7: What are Magic Methods in Python?

Magic methods (dunder methods) are special methods with `__` (double underscore).

Examples:
- `__init__()` → constructor
- `__str__()` → string representation
- `__len__()` → length

 They allow customization of class behavior.

---

## Q8: What are Triggers?

Triggers are **automatic actions in a database**.

 They run when:
- INSERT
- UPDATE
- DELETE happens

Example:
- When a new user is added → automatically log entry

---

## Q9: Does Django use raw passwords? If not, how are they verified?

 Django does NOT store raw passwords.

 It stores **hashed passwords**.

Process:
1. User enters password
2. Django hashes it
3. Compares with stored hash

 Uses secure hashing algorithms (like PBKDF2)

---

## Q10: What is Django Authentication System?

Django provides a built-in system for:
- User login/logout
- Password hashing
- Permissions & roles

Components:
- User model
- Authentication middleware
- Login/Logout views

---

## Q11: Why use Sessions over Cookies?

Sessions are preferred because:
- Data is stored on server (secure)
- Cannot be easily modified by user
- Suitable for sensitive data (login info)

 Cookies are less secure since they are stored in browser.

---

## Q12: What is Cascade?

Cascade means **automatic deletion of related data**.

