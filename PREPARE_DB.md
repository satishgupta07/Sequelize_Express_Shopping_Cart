# Preparing the Database

Do the following as root

```sql
create database shopdb;
CREATE USER 'shopper'@'localhost' IDENTIFIED BY 'shoppass';
use shopdb;
grant all privileges on shopdb to shopper;
grant all privileges on shopdb.* to shopper;
```