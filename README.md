# Hello! My name is Tori Tomlinson   
## Projects   
### SQL Sakila  
---   
The Sakila database (version 1.3) is an example database from the MySQL workbench app. 

![Sakila_EER_Diagram](SakilaSQL/Sakila_EER_Diagram.png)  

[Link to sql project foler](/SakilaSQL/)

[Link to sql file Rental](/SakilaSQL/Rental.sql)

[Link to sql file Testing](/SakilaSQL/Testing.sql)

[Link to EER Diagram](/SakilaSQL/Sakila_EER_Diagram.png)

[Link to Schema](/SakilaSQL/sakila-schema.sql)
```sql
SELECT
    CONCAT('$',amount) AS 'Payment Amount',
    DATE_FORMAT(payment_date, "%d/%m/%Y") AS 'Payment Date'
FROM payment LIMIT 20;
```

