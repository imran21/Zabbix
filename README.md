# Zabbix

### Monitoring Tool
<br>
Prerequisite

  - In /etc/yum.repo.d/* make enabled=1 in all the repo file. So that we can install all the php modules that are needed.
  - Install the Followings
 
   ``` sh
       $ yum install httpd httpd-devel
       $ yum install mysql mysql-server
       $ yum install php php-devel php-bcmath  php-pear php-gd php-mbstring php-mysql php-xml
   ``` 
Sometimes Mysql dose not work. For That install MariaDB

 ``` sh
     $ yum install mariadb-server
 ```

Then perform this operation
 ``` sh
     $ mysql_secure_installation
 ```
 > In the above step, Enter the database password and remove all the things from database just by giving 'Yes' and 'No'
 
 
 
 

 
