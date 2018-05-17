SELECT * FROM sqlol.users                               =>          *Get all fields from the table "sql.users"*

SELECT * FROM sqlol.ssn                                 =>          *Get all fields from the table "sql.ssn"*

SELECT name FROM sqlol.ssn                              =>          *Get fields "name " from the table "sql.ssn"*

SELECT ssn as name FROM sqlol.ssn                       =>          *Get fields "ssn" from the table "sql.ssn" and and change its field name to "name"*

SELECT * FROM sqlol.ssn WHERE name='Herp Derper'        =>          *Get all fields from the table "sql.ssn" with the "name" field equal to "Herp Derper"*
