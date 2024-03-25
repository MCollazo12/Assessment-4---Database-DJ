  ### Conceptual Exercise

  Answer the following questions below:

  • What is PostgreSQL?
	  PostgreSQL is an open-source relational database management system (RDBMS). It is used as a primary database for many web, mobile, and analytical applications.
	  
  • What is the difference between SQL and PostgreSQL?
	  SQL is the language used to manage/manipulate relational databases, while PostgreSQL is a type of RDBMS
	  
  • In psql , how do you connect to a database?
	  To connect to a database, the command `\c database_name` is used
	  
  • What is the difference between  HAVING  and  WHERE ?
	  WHERE filters input rows before groups are formed, while HAVING filters group rows *after* they've been computed.
	  
  • What is the difference between an  INNER  and  OUTER  join?
	  Inner joins return only the rows that match both tables, while outer joins return all rows from both tables.

  • What is the difference between a  LEFT OUTER  and  RIGHT OUTER  join?
	  In a left outer join, all rows from the left table are returned along with matching rows from the right table. It is reversed for a right outer join. 
	  
  • What is an ORM? What do they do?
		An ORM is a programming technique that allows you to manipulate data from a database using an object-oriented programming language.
		
  • What are some differences between making HTTP requests using AJAX and from the server side using a library like requests ?
	  AJAX allows for asynchronous requests between a client and a server, while server-side requests are executed on the server and the server will send a response back to the client (requires a page reload).
	  
  • What is CSRF? What is the purpose of the CSRF token?
	  CSRF or Cross-Site Request Forgery is a type of web security vulnerability that exploits unauthorized commands submitted from a user that the webpage trusts (exploiting the user's active session). The CSRF token helps to mitigate this risk by adding a unique token to each form submission which the server then verifies. 
	  
  • What is the purpose of form.hidden_tag() ?
	The hidden tag generates hidden input fields for each CSRF token. This is used to prevent CSRF attacks in conjunction with the CSRF token.

