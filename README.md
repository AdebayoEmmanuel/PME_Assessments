# PME_Assessments
Display the average billing amount for each employee between 2019 to 2021, assume #0 billing amount if nothing is billed for a particular year of that employee.

For example, we have the following data.

Note: Kindly convert the script to whatever version of SQL you write in.
```sql
create table employeeBilling
(
     employeeId               	int,
     employeeName             	varchar(1),
     billingId                		varchar(5),
     billingDate     		date,
     billedAmount            	int
);
```
```sql
insert into employeeBilling values (1, 'A', 'id1', to_date('10-10-2020','dd-mm-yyyy'), 100);
insert into employeeBilling values (1, 'A', 'id2', to_date('11-11-2020','dd-mm-yyyy'), 150);
insert into employeeBilling values (1, 'A', 'id3', to_date('12-11-2021','dd-mm-yyyy'), 100);
insert into employeeBilling values (2, 'B', 'id4', to_date('10-11-2019','dd-mm-yyyy'), 150);
insert into employeeBilling values (2, 'B', 'id5', to_date('11-11-2020','dd-mm-yyyy'), 200);
insert into employeeBilling values (2, 'B', 'id6', to_date('12-11-2021','dd-mm-yyyy'), 250);
insert into employeeBilling values (3, 'C', 'id7', to_date('01-01-2018','dd-mm-yyyy'), 100);
insert into employeeBilling values (3, 'C', 'id8', to_date('05-01-2019','dd-mm-yyyy'), 250);
insert into employeeBilling values (3, 'C', 'id9', to_date('06-01-2021','dd-mm-yyyy'), 300);

select * from employeeBilling;
```
Output Format
A table displaying employeeId, employeeName, and average billing amount.
Submission

Kindly provide a screenshot of your SQL environment alongside your query to solve the problem and the result. 
Results should be posted on the group. 

Enjoy!!!
