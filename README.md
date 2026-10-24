# PortSwigger Web Security Academy - SQL Injection Labs

This repository contains my practice work, solutions, and screenshots from the PortSwigger Web Security Academy SQL Injection labs.

---

## Lab 1: SQL Injection Vulnerability in WHERE Clause Allowing Retrieval of Hidden Data

* **Description:** In this lab, an SQL injection vulnerability was exploited within the product category filter in the WHERE clause. By appending the payload `'+OR+1=1--` to the URL parameter, the query logic was modified to evaluate as true, retrieving hidden unreleased products from the database.
* **Browser Screenshot / Evidence:**
  * ![Lab 1 - Hidden Data Retrieval](sql%201.PNG)
