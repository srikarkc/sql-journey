# From Sam's Teach Yourself SQL in 10 Minutes a Day, 5th edition book


### Key Terms

1. DBMS (Database Management Systems)
2. Database
3. Table,
4. Schema,
5. Column,
6. Datatype,
7. Rows (aka Records),
8. Primary Key

Tables have properties and characteristics that define how data gets stored in them, this is known as schema. Provides information about the database and table layout & properties.

Primary key (a column) uniquely identifies every row in a table.

---

### Retrieving Data

'SELECT' statement, needs 2 pieces of information at the least, what you want to select and from where you want to select it. 

'SELECT' is on of the keywords and is NOT case-senstitive.

Multiple SQL statement must be separated by a ';'

'DISTINCT' keyword to get only distinct results.

Different DBMS'es have different ways of limiting results -> Best way for PostgreSQL is to include LIMIT keyword at the end.

Comments can start with a '--', 

---

### Sorting retrieved data

'ORDER BY' clause