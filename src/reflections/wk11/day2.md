# Relationships

---

## What is the difference between a primary key and a foreign key



---

## What is an Alias?




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