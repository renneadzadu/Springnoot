# Springboot


mysql> show databases;
+--------------------+
| Database           |
+--------------------+
| elite11            |
| information_schema |
| jokeapp            |
| jokesnew           |
| movies             |
| mysql              |
| performance_schema |
| sys                |
+--------------------+
8 rows in set (0.02 sec)

mysql> use jokeapp;
Database changed
mysql> select * from joke;
+----+----------------------------------------------------------------------------+
| id | value                                                                      |
+----+----------------------------------------------------------------------------+
|  1 | Do you want to hear a construction joke? - Sorry, I?m still working on it. |
|  2 |  When does a joke become a ?dad? joke? - When it becomes apparent.         |
+----+----------------------------------------------------------------------------+
2 rows in set (0.00 sec)

mysql> select * from joke;
+----+--------------------------------------------------------------------------------------+
| id | value                                                                                |
+----+--------------------------------------------------------------------------------------+
|  1 | Do you want to hear a construction joke? - Sorry, I?m still working on it.           |
|  2 |  When does a joke become a ?dad? joke? - When it becomes apparent.                   |
|  3 | Why should you never trust stairs? they?re always up to something.                   |
|  4 | The first rule of the Alzheimer?s club is -Wait, where are we again                  |
|  5 | Why doesn?t Dracula have any friends? -Well, honestly, he?s a real pain in the neck. |
+----+--------------------------------------------------------------------------------------+
5 rows in set (0.00 sec)

mysql> select * from joke;
+----+--------------------------------------------------------------------------------------+
| id | value                                                                                |
+----+--------------------------------------------------------------------------------------+
|  1 | Do you want to hear a construction joke? - Sorry, I?m still working on it. meme...   |
|  2 |  When does a joke become a ?dad? joke? - When it becomes apparent.                   |
|  3 | Why should you never trust stairs? they?re always up to something.                   |
|  4 | The first rule of the Alzheimer?s club is -Wait, where are we again                  |
|  5 | Why doesn?t Dracula have any friends? -Well, honestly, he?s a real pain in the neck. |
|  6 | Why aren?t koalas considered bears? - They don?t have the right koala-fications.     |
+----+--------------------------------------------------------------------------------------+
6 rows in set (0.00 sec)

mysql> select * from joke;
+----+--------------------------------------------------------------------------------------+
| id | value                                                                                |
+----+--------------------------------------------------------------------------------------+
|  1 | Do you want to hear a construction joke? - Sorry, I?m still working on it. meme...   |
|  2 |  When does a joke become a ?dad? joke? - When it becomes apparent.                   |
|  3 | Why should you never trust stairs? they?re always up to something.                   |
|  4 | The first rule of the Alzheimer?s club is -Wait, where are we again                  |
|  5 | Why doesn?t Dracula have any friends? -Well, honestly, he?s a real pain in the neck. |
|  6 | Why aren?t koalas considered bears? - They don?t have the right koala-fications.     |
+----+--------------------------------------------------------------------------------------+
6 rows in set (0.00 sec)

mysql> select * from joke;
+----+--------------------------------------------------------------------------------------+
| id | value                                                                                |
+----+--------------------------------------------------------------------------------------+
|  1 | Do you want to hear a construction joke? - Sorry, I?m still working on it. meme...   |
|  3 | Why should you never trust stairs? they?re always up to something.                   |
|  4 | The first rule of the Alzheimer?s club is -Wait, where are we again                  |
|  5 | Why doesn?t Dracula have any friends? -Well, honestly, he?s a real pain in the neck. |
|  6 | Why aren?t koalas considered bears? - They don?t have the right koala-fications.     |
+----+--------------------------------------------------------------------------------------+
5 rows in set (0.00 sec)

mysql>
