## Install MySQL on Ubuntu
```
sudo apt update
```
```
sudo apt upgrade
```
```
sudo apt install mysql-server
```
```
sudo mysql_secure_installation
```
```
sudo mysql -u root
```
## mysql
```
select user,authentication_string,plugin,host from mysql.user;
```
```
ALTER USER 'root'@'localhost IDENTIFIED WITH caching_sha2_password BY 'password';
```
```
exit
```
```
FLUSH PRIVILEGES;
```