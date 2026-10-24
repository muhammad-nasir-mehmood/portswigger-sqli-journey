# PortSwigger Web Security Academy - SQL Injection Labs

This repository contains my practice work, solutions, and screenshots from the PortSwigger Web Security Academy SQL Injection labs.

---

## Lab 1: SQL Injection Vulnerability in WHERE Clause Allowing Retrieval of Hidden Data

- **Lab Name:** SQL injection vulnerability in WHERE clause allowing retrieval of hidden data
- **Description:** In this lab, an SQL injection vulnerability was exploited within the product category filter in the WHERE clause. By appending the payload `'+OR+1=1--` to the URL parameter, the query logic was modified to evaluate as true, retrieving hidden unreleased products from the database.
- **Browser Screenshot / Evidence:**
  - ![Lab 1 - Hidden Data Retrieval](sql%201.PNG)

---

## Lab 2: SQL Injection Vulnerability Allowing Login Bypass

- **Lab Name:** SQL injection vulnerability allowing login bypass
- **Description:** In this lab, an SQL injection vulnerability was present in the login functionality. By injecting the SQL comment payload `administrator'--` into the username parameter, the password verification logic was commented out, allowing authentication bypass directly as the `administrator` user.
- **Burp Suite Repeater Analysis:**
  - ![Lab 2 - Burp Suite Request & Response](sql%202.jpg)
- **Lab Solved Proof:**
  - ![Lab 2 - Login Bypass Success](sql%202%20ss.PNG)
