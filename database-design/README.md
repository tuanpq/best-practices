# Database Design Best Practices

1. Take Stakeholder’s Perspective
- Keep in mind every stakeholder’s perspective
2. Select a Database Type (SQL, NoSQL)
- Relational Database, Hierarchical Database, Network Database, Object-Oriented Database
3. Define and Label Tables and Columns Consistently
- Give a simple name that defines contained data
- Avoid using plural names, abbreviations, and spaces in the name
4. Consider Normalization and Denormalization

| No. | Normalization | Denormalization |
|-----|---------------|-----------------|
| 1 | Normalization is used to remove redundant data from the database and to store non-redundant and consistent data into it. | Denormalization is used to combine multiple table data into one so that it can be queried quickly. |
| 2 | Normalization mainly focuses on clearing the database from unused data and to reduce the data redundancy and inconsistency. | Denormalization on the other hand focus on to achieve the faster execution of the queries through introducing redundancy. |
| 3 | During Normalization as data is reduced so a number of tables are deleted from the database hence tables are lesser in number. | On another hand during Denormalization data is integrated into the same database and hence a number of tables to store that data increases in number. |
| 4 | Normalization uses optimized memory and hence faster in performance. | On the other hand, Denormalization introduces some sort of wastage of memory. |
| 5 | Normalization maintains data integrity i.e. any addition or deletion of data from the table will not create any mismatch in the relationship of the tables. | Denormalization does not maintain any data integrity. |
| 6 | Normalization is generally used where number of insert/update/delete operations are performed and joins of those tables are not expensive. | On the other hand Denormalization is used where joins are expensive and frequent query is executed on the tables. |

5. Modelling, Design and Documentation
- Create ER diagrams
6. Privacy Is a Primary Concern
- Encrypt your passwords, restrict database access using authentication
- Use a different server for database than your application
7. Think of Long-Term Needs
- Scalable
- High performance / workload

