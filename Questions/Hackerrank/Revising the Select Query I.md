# [Revising the Select Query I](https://www.hackerrank.com/challenges/revising-the-select-query/problem?isFullScreen=true)

Query all columns for all American cities in the CITY table with populations larger than 100000. The CountryCode for America is USA.

The CITY table is described as follows:

<img width="388" alt="Screenshot 2024-01-11 at 10 38 12 AM" src="https://github.com/SiddharthMathurDeveloper/Database-Management-System-DBMS/assets/133037456/85703bf5-1ab8-445f-9359-6ac64dbe4025">


```sql
select * from CITY where COUNTRYCODE = 'USA' AND POPULATION > 100000;
```
