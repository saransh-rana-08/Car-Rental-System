# Car-Rental-System
It is the software ware for owner of car rental company. 
To run the program you have to Make the database named 'losrent'.
It contain the tables :-
      carregistration:-
              Field     | Type         | Null | Key | Default | Extra          |
            +-----------+--------------+------+-----+---------+----------------+
            | id        | int          | NO   | PRI | NULL    | auto_increment |
            | car_no    | varchar(255) | NO   |     | NULL    |                |
            | make      | varchar(255) | NO   |     | NULL    |                |
            | model     | varchar(255) | NO   |     | NULL    |                |
            | available | varchar(255) | NO   |     | NULL    |                |
            +-----------+--------------+------+-----+---------+----------------+
      customer :-
            +---------+--------------+------+-----+---------+----------------+
            | Field   | Type         | Null | Key | Default | Extra          |
            +---------+--------------+------+-----+---------+----------------+
            | id      | int          | NO   | PRI | NULL    | auto_increment |
            | cust_id | varchar(255) | NO   |     | NULL    |                |
            | name    | varchar(255) | NO   |     | NULL    |                |
            | address | text         | NO   |     | NULL    |                |
            | mobile  | int          | NO   |     | NULL    |                |
            +---------+--------------+------+-----+---------+----------------+

      
      rental :-
            +---------+--------------+------+-----+---------+----------------+
            | Field   | Type         | Null | Key | Default | Extra          |
            +---------+--------------+------+-----+---------+----------------+
            | id      | int          | NO   | PRI | NULL    | auto_increment |
            | car_id  | varchar(255) | NO   |     | NULL    |                |
            | cust_id | varchar(255) | NO   |     | NULL    |                |
            | fee     | int          | NO   |     | NULL    |                |
            | date    | varchar(255) | NO   |     | NULL    |                |
            | due     | varchar(255) | NO   |     | NULL    |                |
            +---------+--------------+------+-----+---------+----------------+
      
      returncar:-
            +-------------+--------------+------+-----+---------+----------------+
            | Field       | Type         | Null | Key | Default | Extra          |
            +-------------+--------------+------+-----+---------+----------------+
            | id          | int          | NO   | PRI | NULL    | auto_increment |
            | carid       | varchar(255) | NO   |     | NULL    |                |
            | custid      | varchar(255) | NO   |     | NULL    |                |
            | return_date | varchar(255) | NO   |     | NULL    |                |
            | elap        | int          | NO   |     | NULL    |                |
            | fine        | int          | NO   |     | NULL    |                |
            +-------------+--------------+------+-----+---------+----------------+
      

