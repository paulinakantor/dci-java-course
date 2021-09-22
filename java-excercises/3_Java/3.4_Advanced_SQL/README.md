# Java - Databases - Advanced SQL

## Overview
This submodule provides learners with advanced SQL techniques.

## Objectives
By the end of this submodule, the learners should be able to:

* Understand and know how to combine multiple tables together using JOIN statements
* Know more advanced datatypes and use them
* Understand and create sub queries in SELECT, UPDATE, INSERT, DELETE statements
* Know different aggregate functions and use them in queries
* Know how to group and filter records using GROUP BY and HAVING statements

## Materials and Resources

### Exercises - instruction
For excercises you need to use Northwind database.
You can follow given instruction to set up this database: https://github.com/pthom/northwind_psql

![Northwind schema](https://www.google.com/url?sa=i&url=https%3A%2F%2Fdocs.yugabyte.com%2Flatest%2Fsample-data%2Fnorthwind%2F&psig=AOvVaw1Ud47xUNm2Z97C-RhC-Tdw&ust=1631386356487000&source=images&cd=vfe&ved=0CAkQjRxqFwoTCOi82_SJ9fICFQAAAAAdAAAAABAD)

You can find database also in this repository as **schema.png** file.

**IMPORTANT**
According to agenda excercises about aggregate functions should have 3TUs and GROUP BY should be a part of it. 
I introduced a change here by putting GROUP BY and HAVING together. So excercises for aggregate functions contains only tasks for COUNT, SUM, MIN, MAX, AVG functions and I plannned them to take 1TU. Excercises for GROUP BY and HAVING I planned to take 3TUs.

File with excercises has only a list of tasks to do.
File with solutions also contains difficulty level as well as time needed to make this task.

Expected from students: file with SQL scripts that will contain solutions (one file per chapter, like: joins_solutions.sql, etc).

#### Exercises

JOIN excercises  
Time: 3TUs ~ 2h15min  
When: After lecture about JOINs  
Link: https://github.com/paulinakantor/dci-java-course/blob/main/java-excercises/3_Java/3.4_Advanced_SQL/Java-Advanced_SQL-Joins/Join%20excercises  
Solution: https://github.com/paulinakantor/dci-java-course/blob/solutions/java-excercises/3_Java/3.4_Advanced_SQL/Java-Advanced_SQL-Joins/Join%20solutions   
 
Data types excercises  
Time: 2TUs ~ 1h30min  
When: After lecture about data types  
Link: https://github.com/paulinakantor/dci-java-course/blob/main/java-excercises/3_Java/3.4_Advanced_SQL/Java-Advanced_SQL-Datatypes/Datatypes%20excercises  
Solution: https://github.com/paulinakantor/dci-java-course/blob/solutions/java-excercises/3_Java/3.4_Advanced_SQL/Java-Advanced_SQL-Datatypes/Datatypes%20solutions  
  
Sub queries excercises  
Time: 1TU ~ 45min  
When: After lecture about sub queries (but max() function should be explained first)  
Link: https://github.com/paulinakantor/dci-java-course/blob/main/java-excercises/3_Java/3.4_Advanced_SQL/Java-Advanced_SQL-Subqueries/Sub%20queries%20excercises  
Solution: https://github.com/paulinakantor/dci-java-course/blob/solutions/java-excercises/3_Java/3.4_Advanced_SQL/Java-Advanced_SQL-Subqueries/Sub%20queries%20solutions  

IMPORTANT: some tasks of course can be solved using JOINs. Make sure that students use sub queries where possible.

Aggregate functions excercises  
Time: 1TU ~ 45min  
When: After lecture about aggregate functions (without group by & having)  
Link: https://github.com/paulinakantor/dci-java-course/blob/main/java-excercises/3_Java/3.4_Advanced_SQL/Java-Advanced_SQL-Aggregate_functions/Aggregate%20function%20excercises  
Solution: https://github.com/paulinakantor/dci-java-course/blob/solutions/java-excercises/3_Java/3.4_Advanced_SQL/Java-Advanced_SQL-Aggregate_functions/Aggregate%20functions%20solutions  

GROUP BY & HAVING excercises  
Time: 3TU ~ 2h15min   
When: After all lectures (includes examples with aggregate functions, joins, sub queries). Also, knowledge about ordering (ORDER BY), limiting the result (LIMIT) and aliasing (AS) is important here.  
Link: https://github.com/paulinakantor/dci-java-course/blob/main/java-excercises/3_Java/3.4_Advanced_SQL/Java-Advanced_SQL-Groupby_having/GROUP%20BY%20%26%20HAVING%20excercises  
Solution: https://github.com/paulinakantor/dci-java-course/blob/solutions/java-excercises/3_Java/3.4_Advanced_SQL/Java-Advanced_SQL-Groupby_having/GROUP%20BY%20%26%20HAVING%20solutions  
