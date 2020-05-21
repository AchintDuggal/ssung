# ssung(To create database)
mysql  --user-root -p
(PASSWORD)
create database PLMregistration
use PLMregistration
show tables
create table LoginUsers (username VARCHAR(20) , password VARCHAR(20), email VARCHAR(50))
describe LoginUsers

sudo apt-get install python-MySQLdb
python 
import MySQLdb
