# MySQL- QUERIES
### SHOW DATABASES:
```syntax
SHOW DATABASES;
```
| Database           |
|:----|
| batch_students     |
| information_schema |
| mysql              |
| performance_schema |
| sys                |

###### 5 rows in set (0.01 sec)
****

### CREATE DATABASE:
```syntax
CREATE DATABASE mobel_furnitures;
```
###### Query OK, 1 row affected (0.02 sec) 
****

### USE DATABASE:
```syntax
use mobel_furnitures;
```
###### Database changed
****

### CREATE TABLE:
```syntax
CREATE TABLE products (Product_id int(5) primary key, Product_Name varchar(255), Product_type varchar(30)); 
```
###### Query OK, 0 rows affected, 1 warning (0.07 sec)
****

### SHOW TABLES:
```syntax
SHOW TABLES;
```
| Tables_in_mobel_furnitures|
|:----|
| products                  |

###### 1 row in set (0.01 sec)