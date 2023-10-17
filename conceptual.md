### Conceptual Exercise
Answer the following questions below:

- What is PostgreSQL?

- What is the difference between SQL and PostgreSQL?

- In `psql`, how do you connect to a database?

- What is the difference between `HAVING` and `WHERE`?

- What is the difference between an `INNER` and `OUTER` join?

- What is the difference between a `LEFT OUTER` and `RIGHT OUTER` join?

- What is an ORM? What do they do?

- What are some differences between making HTTP requests using AJAX 
  and from the server side using a library like `requests`?

- What is CSRF? What is the purpose of the CSRF token?

- What is the purpose of `form.hidden_tag()`?


1. **What is PostgreSQL?**
PostgreSQL is an advanced, open-source, object-relational database system that uses and extends the SQL language. It is known for its stability, feature robustness, and its ability to handle high volumes of data. PostgreSQL supports complex queries, triggers, foreign keys, and stored procedures.

2. **What is the difference between SQL and PostgreSQL?**
SQL (Structured Query Language) is a standard language for managing and manipulating relational databases. PostgreSQL, on the other hand, is an open-source, object-relational database system that uses and extends the SQL language. Essentially, PostgreSQL is a specific implementation of a database system that uses SQL as its querying language.

3. **In `psql`, how do you connect to a database?**
To connect to a database in `psql`, you use the following command:
```
psql -d [database_name] -U [username]
```
Replace `[database_name]` with the name of the database you want to connect to and `[username]` with your username.

4. **What is the difference between `HAVING` and `WHERE`?**
In SQL, the `WHERE` clause is used to filter records before any groupings are made. The `HAVING` clause is used to filter values after they have been grouped. Essentially, `WHERE` is used with individual records, and `HAVING` is used with aggregated groups.

5. **What is the difference between an `INNER` and `OUTER` join?**
An `INNER JOIN` returns only the rows that have matching values in both tables. An `OUTER JOIN`, on the other hand, returns all the rows from one or both tables, matching them where possible and filling in any missing values with nulls.

6. **What is the difference between a `LEFT OUTER` and `RIGHT OUTER` join?**
A `LEFT OUTER JOIN` returns all the rows from the left table, and the matched rows from the right table. A `RIGHT OUTER JOIN` does the opposite, returning all the rows from the right table and the matched rows from the left table.

7. **What is an ORM? What do they do?**
An ORM (Object-Relational Mapping) is a programming technique for converting data between incompatible type systems in object-oriented programming languages and relational databases. ORMs enable developers to work with data in the form of objects and classes, abstracting the database details away. They provide a high-level, object-oriented interface for accessing and managing the database.

8. **What are some differences between making HTTP requests using AJAX and from the server side using a library like `requests`?**
Making HTTP requests using AJAX involves using JavaScript to send requests from the client side, whereas making requests from the server side using a library like `requests` in Python involves sending requests from the server. AJAX requests are initiated by client-side scripts, while server-side requests are initiated by server-side code. Additionally, server-side requests are more secure as they can hide sensitive information, while AJAX requests might expose some of the logic to end-users.

9. **What is CSRF? What is the purpose of the CSRF token?**
CSRF (Cross-Site Request Forgery) is an attack that tricks the victim into submitting a malicious request. The purpose of the CSRF token is to validate that a request is legitimate and originated from an expected user. It helps prevent unauthorized or malicious actions, ensuring that requests come from forms that you have generated.

10. **What is the purpose of `form.hidden_tag()`?**
In the context of web development, `form.hidden_tag()` is a function that generates a hidden input field within an HTML form. It is commonly used to include hidden data that needs to be sent along with the form submission but doesn't need to be displayed to the user. This hidden data can be used for various purposes such as maintaining state, providing security, or passing additional information between the client and server.






