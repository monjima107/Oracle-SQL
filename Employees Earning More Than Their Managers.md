*PROBLEM*

<img width="344" alt="image" src="https://github.com/monjima107/SQL-Leetcode/assets/114062300/e3e5a8e0-da5e-42f5-8b4e-f11fc39815be">


*SOLUTION*

__/* Write your PL/SQL query statement below */__ <br>
__select e.name as Employee__  <br>
__from Employee e join Employee em__  <br>
__on e.managerId=em.id__  <br>
__where e.salary>em.salary;__  <br>


*RESULT*

<img width="322" alt="image" src="https://github.com/monjima107/SQL-Leetcode/assets/114062300/1705e873-df5c-4f71-8830-8e6d98fde259">
