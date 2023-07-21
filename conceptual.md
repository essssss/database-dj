### Conceptual Exercise

Answer the following questions below:

-   What is PostgreSQL?

    -   A database software

-   What is the difference between SQL and PostgreSQL?

    -   SQL is the database language, PostgreSQL is the program that sets your database and allows your terminal to interact with the database

-   In `psql`, how do you connect to a database?
    -   if Postgres is not running you type `psql database_name`. If postgres is running type `\c database_name`
-   What is the difference between `HAVING` and `WHERE`?

    -   `HAVING` is used with aggregate (`GROUP BY`) functions. `WHERE` is used without those functions.

-   What is the difference between an `INNER` and `OUTER` join?

    -   `INNER` joins show items that have values in both tables,
    -   `OUTER` joins show items that are in one table and may not be in another one. Specify using `LEFT` or `RIGHT` joins.

-   What is the difference between a `LEFT OUTER` and `RIGHT OUTER` join?
    -   A `LEFT OUTER` join shows items that are in the first table listed even if they have no matching values in the second table. `RIGHT OUTER` is the opposite.
-   What is an ORM? What do they do?
    -   an ORM maps data from a database into a python dictionary format so you can interact with it that way.
-   What are some differences between making HTTP requests using AJAX and from the server side using a library like `requests`?
    -   Using AJAX in a browser can cause issues if you are interacting with an API that requires authentication. But you can do asynchronous functions
-   What is CSRF? What is the purpose of the CSRF token?
    -   CSRF stands for Cross-site request forgery. A CSRF token is sent with a form and lets the destination know that the form was sent from an appropriate site.
-   What is the purpose of `form.hidden_tag()`?
    -   `form.hidden_tag()` is useful for hiding form fields, particularly the aforementioned CSRF token.
