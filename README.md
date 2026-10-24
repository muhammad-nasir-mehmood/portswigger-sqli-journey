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
  - <img width="960" height="511" alt="sql 2" src="https://github.com/user-attachments/assets/251f2aee-3058-4245-9b8f-42532340ff31" />
- **Lab Solved Proof:**
  - ![Lab 2 - Login Bypass Success](sql%202%20ss.PNG)

---<img width="960" height="511" alt="sql 2 ss" src="https://github.com/user-attachments/assets/dfc1446d-2243-4f08-b077-0662f944882b" />


## Lab 3: SQL Injection Attack, Querying the Database Type and Version on Oracle

- **Lab Name:** SQL injection attack, querying the database type and version on Oracle
- **Description:** Explored an SQL injection vulnerability on an Oracle database using `UNION SELECT` queries to extract database architecture and table metadata.
- **Burp Suite Repeater Setup:**
  - ![Uploading sql 2 ss.PNG…]()
![Uploading sql 2 ss.PNG…]()
<img width="960" height="511" alt="sql 3 ss" src="https://github.com/user-attachments/assets/71224211-829f-4c43-a4ae-9b4e3c960221" />

- **Database Table Extraction:**
  - <img width="959" height="448" alt="sql lab3 ss2" src="https://github.com/user-attachments/assets/1b554a37-e68b-4106-a715-adbab474df5f" />
<img width="960" height="480" alt="sql lab 3 ss1" src="https://github.com/user-attachments/assets/87dafc27-e775-4ba7-bb87-46c90ad41ad4" />

  - 
- **Lab Solved Proof:**
  - <img width="959" height="510" alt="sql 3 ss 1" src="https://github.com/user-attachments/assets/fd35c87e-d3b9-4c9d-8e0e-02c3eef0c770" />


---

## Lab 4: SQL Injection Attack, Querying the Database Type and Version on MySQL and Microsoft

- **Lab Name:** SQL injection attack, querying the database type and version on MySQL and Microsoft
- **Description:** Investigated database behavior across MySQL and Microsoft SQL Server by injecting specific comment syntaxes and analyzing internal server error triggers.
- **Burp Suite Repeater Analysis:**
- <img width="958" height="509" alt="sql 4 ss" src="https://github.com/user-attachments/assets/28f09158-bf3d-44f7-8b75-345da7f134c3" />

  - 
- **Lab Solved Proof:**
  
<img width="960" height="511" alt="sql 4 ss1" src="https://github.com/user-attachments/assets/76829bc4-a7b2-47c8-9397-2f0d7ad2fcd1" />

---

## General Proxy & Intercept Setup

- **Burp Suite Proxy View:**
  - ![Burp Suite Intercept Setup](ss%201.PNG)
