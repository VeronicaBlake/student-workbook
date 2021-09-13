# Relationships

---

## What is the difference between a primary key and a foreign key

Primary keys are unique pieces of information (usually an id) that you can use to refer to records on a table. A Foreign key is another table's primary key used in a different table. This allows the table to reference 


---

## What is an Alias?

An alias is an assignment that is  used to give a table, or a column of a table, a temporary name. 

---

## Demonstrate how you would query a join statement that would get all of a doctor's patients from the following collections:

SELECT
  d.*,
  p.*
FROM
  doctors d
  JOIN patients p ON p.id = d.id
WHERE
  d.id = 1;
  (if you're looking for the patients on the doctor with the Id of 1)