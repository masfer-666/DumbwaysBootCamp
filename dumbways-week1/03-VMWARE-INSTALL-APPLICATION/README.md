# VMWARE INSTALL APPLICATION 

1. Update dan upgrade package ubuntu server 
![16](../asset/016.png)

2. Install NGINX sebagai webserver, lalu buat hidupkan service nginx jika restart akan otomatis menyala
![17](../asset/017.png)

3. Setelah itu jalankan service nginx, lalu check status service nginx ,dan pastikan virtual server sudah dapat menggunakan nginx
![18](../asset/018.png)
![19](../asset/019.png)

4. Install package nodejs versi 10   

![20](../asset/020.png)

5. Pastikan Versi nodejs yang sudah terinstall menggunakan versi 10 
![21](../asset/021.png)

6. Lalu clone aplikasi yang akan di deploy menggunakan git, setelah berhasil di clone masuk ke dalam folder tersebut 
![21](../asset/021A.png)

7. Deploy aplikasi tersebut menggunakan command npm install, lalu npm start untuk menjalankan applikasi tersebut  
![22](../asset/022.png)
![23](../asset/023.png)
![24](../asset/024.png)

8. Jika sudah terinstall dan dijalankan, akses aplikasi di web browser dengan ip address virtual mesin dan port 3000
![25](../asset/025.png)

