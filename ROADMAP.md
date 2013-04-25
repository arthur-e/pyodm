What I Would Like to Eventually See
-----------------------------------

At the basic level, I would like this module to have near 1:1 feature parity
with the ODM Tools software provided by CUAHSI. To me that means simple function 
or method calls that:
+ accept any `pyodbc`, `MySQLdb`, or `psycopg21 connection object and a filename
or handle
+ upload data the database in the file to the appropriate table at the other end
of the connection object

After that is accomplished, I would like simple function or method calls that
leverage the pandas and matplotlib libraries to:
+ retrieve data
+ export data
+ visualize data (can of worms: opened)
+ provide utilities for basic QA/QC and sanity checks
