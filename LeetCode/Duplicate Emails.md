*PROBLEM*

<img width="302" alt="image" src="https://github.com/monjima107/Oracle-SQL/assets/114062300/b3d23c2b-fdc9-4baf-8503-279c3dabd029">

*SOLUTION*

__/* Write your PL/SQL query statement below */__ <br>
__select email as Email__ <br>
__from Person__ <br>
__where email is not null__ <br>
__group by email__ <br>
__having count(email)>1;__ <br>

*RESULT*

<img width="103" alt="image" src="https://github.com/monjima107/Oracle-SQL/assets/114062300/6c20bd60-3236-4ef8-8e8d-a086b5c42d52">
