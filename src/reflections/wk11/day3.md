# SQL Injection

---

## What is SQL injection?

A SQL injection is when an attacker inserts arbitrary sql into a web application database query, allowing them to take complete control over your web applicaiton database. 


---

## What are 3 methods SQL injection can be done by?

User input - if data is unsanitized, the attacker injects SQL into the back end to delete, copy or modify the contents of the database

Modify Cookies - malware infects the client state information stored locally on the computer to create a back-end database

Second Order - Designed to run later when the poisoned data is used in a different context

---

## How can we detect and sanitize SQL injection attacks?

We can detect SQL injection attacks by implementing a web applicaiton firewall, and using Network based and nost based intrusion detection systems. IDSs monitor connections to your database server and flag suspicious activity. 

We can sanitize data by treating any input into a web application as untrustworthy and treating it as such. Account privelages should also be limited, and stored procedures can be implemented as well. 
