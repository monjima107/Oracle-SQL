*PROBLEM*

<img width="229" alt="image" src="https://github.com/monjima107/Oracle-SQL/assets/114062300/9a35e9a2-a673-4126-bdd5-508259a3484f">

*SOLUTION*

__/* Write your PL/SQL query statement below */__ <br>
select c.name as Customers--__ <br>
__from Customers c left join Orders o__ <br>
__on c.id=o.customerId__ <br>
__where o.id is null;__ <br>

*RESULT*

<img width="125" alt="image" src="https://github.com/monjima107/Oracle-SQL/assets/114062300/8493cd1b-29d3-4778-bafd-b10393c2fb87">
