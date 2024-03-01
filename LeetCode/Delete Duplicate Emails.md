*PROBLEM*

<img width="455" alt="image" src="https://github.com/monjima107/Oracle-SQL/assets/114062300/4ebea900-f667-4bbe-b81b-734375f5c05a">

*SOLUTION*

__/* Write your PL/SQL query statement below */__ <br>
__delete from Person__ <br>
__where id not in (__ <br>
    __select min(id)__ <br>
    __from Person__ <br>
    __group by email__ <br>
__);__ <br>

*RESULT*

<img width="132" alt="image" src="https://github.com/monjima107/Oracle-SQL/assets/114062300/3e3b5480-48cd-4c74-a322-1aae4795644f">
