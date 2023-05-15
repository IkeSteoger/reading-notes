# 401 Prep Work: Practice in the Terminal

`SELECT` column, another_column,  
`FROM` mytable;

`SELECT` column, another_column, …  
`FROM` mytable  
`WHERE` condition  
`AND/OR` another_condition  
`AND/OR` …;

`DISTINCT` keyword will blindly remove duplicate rows.

`ORDER BY` sorts each row alpha-numerically based on the specific columns value

`LIMIT` reduces number of rows to return, optional `OFFSET` will specify where to begin counting the number of rows from.

`JOIN` can combine row data across two separate tables using this unique key.  
`INNER JOIN` is a process that matches rows from the first table and the second table that have the same key (as defined by `ON`).  
`LEFT/RIGHT/FULL JOIN` can be used to ensure that the data you need is not left out of the results. `LEFT` includes rows from A regardless of whether a matching row is found in B. `RIGHT` is the same, but reversed. `FULL` means both rows are kept, no matter of the matching row existance. When using any of these new joins, you will likely have to write additional logic to deal with NULLs in the result and constraints.

Use `IS/IS NOT NULL` to deal with above constraints.

It is recommended that when expressions are used in the `SELECT` part of the query, that they are also given a descriptive alias using the `AS` keyword.

`GROUP BY` uses the `HAVING` clause which is used specifically to allow us to filter grouped rows from the result set.

Query Order of Execution  
`SELECT DISTINCT` column, `AGG_FUNC(column_or_expression)`, …  
`FROM` mytable  
    `JOIN` another_table  
      `ON` mytable.column = another_table.column  
    `WHERE` constraint_expression  
    `GROUP BY` column  
    `HAVING` constraint_expression  
    `ORDER BY` column `ASC/DESC`  
    `LIMIT` count `OFFSET COUNT`;  

To add data to database we use `INSERT INTO` myTable (column, another_column) `VALUES`

To update database we use `UPDATE` myTable `SET` column=value_or_expr, ... `WHERE` condition

To delete from database we use `DELETE FROM` myTable `WHERE` condition

To create a table in database we use `CREATE TABLE IF NOT EXISTS` myTable `(`
    `column DataType TableConstraint DEFAULT default_value,`
    `another_column DataType TableConstraint DEFAULT default_value,`
   `…`
`);`

To alter tables (adding and removing columns, renaming table, etc) `ALTER TABLE` `ADD`/`DROP`/`RENAME TO`

Delete a table by using `DROP TABLE IF EXISTS` myTable;

![SQLBolt](../assets/SQLBolt.png)