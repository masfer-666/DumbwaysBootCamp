# SETUP DATABASE
1. Membuat 2 instance di aws untuk server backend & database
![10](../asset/010.png)

2. Update package ubuntu server 
![11](../asset/011.png)

3. install mariadb 10.2 & galera sebagai clustering database pada dua node server
![12](../asset/012.png)

4. setup user password untuk maariadb sebgai root dengan perintah mysql_secure_installation
![13](../asset/013.png)

5. config galera pada dua node server pada file /etc/mysql/my.cnf
![14](../asset/014.png)

6. test hasil clustering database di kedua nodes dengan perintah "SHOW STATUS LIKE "wsrep_cluster_size";

![15](../asset/015.png)
