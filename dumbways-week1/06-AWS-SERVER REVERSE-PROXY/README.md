# AWS-SERVER REVERSE PROXY

1. Update dan upgrade library os packages
   ![text](../asset/48.png)
2. install nginx dan check service nginx
   ![text](../asset/49.png)
3. Test nginx apakah sudah berhasil terinstall menggunakan command curl
   ![text](../asset/50.png)
4. Membuat file serv.conf pada directory nginx di `etc/sites-available/`
   ![text](../asset/51.png)
5. jika sudah jalankan file.conf dengan symbolic link ke directory /etc/sites-enable/ dengan perintah `ln -s /etc/nginx/sites-available/serv.conf /etc/nginx/sites-enabled/`
   ![text](../asset/52.png)
6. setelah itu test konfigurasi nginx yang sudah dibuat dengan perintah `nginx -t` lalu restart service nginx dan chech statusnya
   ![text](../asset/52.png)
7. akses ke browser dengan ip public apakah aplikasi berhasil
   ![text](../asset/53.png)
