### Conceptual Exercise

Answer the following questions below:

- What is PostgreSQL?
  open source relationship database system

- What is the difference between SQL and PostgreSQL?

  SQL is a language for managing relationship databases, PostgreSQL is a relationship database system that uses SQL standards to communicate with data on the database

- In `psql`, how do you connect to a database?

psql database_name

- What is the difference between `HAVING` and `WHERE`?

  WHERE is used to filter data using condition like (WHERE flavor = 'chocolate')
  HAVING is used in combination with GROUP BY. It filters grouped data 

- What is the difference between an `INNER` and `OUTER` join?
INNER shows only data that shows up in both datatables, while OUTER join shows all of the data including data that is unique to each datatable. 

- What is the difference between a `LEFT OUTER` and `RIGHT OUTER` join?
LEFT OUTER bring all the data from the left sided datatable. It includes data that does not exist in the joining datatable
RIGHT OUTER is the opposite. it brings all of the data from the RIGHT datatable even the data that is not included in the left datatable. 


- What is an ORM? What do they do?
Object relational mapping that maps objects in an application to datatables which makes it easier to access and manipulate data. It reduces the amount of code developers need to write because under the hood ORM commands get converts into SQL to communicate with databases. 

- What are some differences between making HTTP requests using AJAX 
  and from the server side using a library like `requests`?
  AJAX makes an HTTP request from the client side/front-end, and HTTP request with a requests library is a backend/server side request. 

- What is CSRF? What is the purpose of the CSRF token?
cross site reference forgary token is a token that prevents submition of forms from external sites and from getting data from the current site. CSRF token is sent with the form when submitted and if the data coming in to the server from a form is missing a legitimate CSRF token, then data from that form is not accepted. 

- What is the purpose of `form.hidden_tag()`?
it hides CSRF token as a hidden input field. 
