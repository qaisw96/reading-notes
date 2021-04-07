# Database normalization 

process used to organize a database into tables and columns. The idea is that a table should be about a specific topic and that only those columns which support that topic are included.
For example, a spreadsheet containing information about sales people and customers serves several purposes:
+ Identify sales people in your organization
+ List all customers your company calls upon to sell product
+ Identify which sales people call on specific customers


## Reasons for Normalization
1. minimize duplicate data
2. avoid data modification issues
3. simplify queries

## Normalization Forms : 

1. First Normal Form – The information is stored in a relational table and each column contains atomic values, and there are not repeating groups of columns.
2. Second Normal Form – The table is in first normal form and all the columns depend on the table’s primary key.
3. Third Normal Form – The table is in second normal form and all of its columns are not transitively dependent on the primary key.
