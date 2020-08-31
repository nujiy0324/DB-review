## some Problems of SQL on Leetcode

```mysql
#1
select FirstName, LastName, City, State
from Person left join Address
on Person.PersonId = Address.PersonId;


#2
SELECT
(SELECT DISTINCT
            Salary
        FROM
            Employee
        ORDER BY Salary DESC#逆向排序，如果不加的话就是正向排序
        LIMIT 1 OFFSET 1) AS SecondHighestSalary;、
        
        
#LIMIT 用法
LIMIT 2,1 #跳过两条数据，读取一条数据，即读第三条数据
LIMIT 2 OFFSET 1 #从第一条开始读（不包含），读2条


```

