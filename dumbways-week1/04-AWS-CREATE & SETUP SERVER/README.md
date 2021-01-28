# AWS-CREATE & SETUP SERVER

## SERVER REVERSE PROXY

1. login account aws yang sudah didaftarkan, setelah itu pilih sistem operasi yang ingin digunakan (sample ubuntu server 18.04)
   ![16](../asset/026.png)
2. Pilih instance untuk server yang akan digunakan, (tentukan sebagaimana kebutuhan)

![27](../asset/027.png)

3. Setelah itu pada menu auto assign public pilih disable agar pada saat server restart ip address tetap static, sehingga tidak akan berubah

![28](../asset/028.png)

4. Memilih storage penyimpanan untuk server yang akan dibuat sebagai contoh disini saya merubah menjadi 15 gb untuk size nya

![29](../asset/029.png)


5. Konfigurasi security group, untuk menentukan port mana yang akan di buka oleh server, adapun port yang akan dibuka sebagai berikut

   * Port 22 (SSH) : untuk akses ssh dari client ke server
   * Port 80 (HTTP) : untuk open port http di server
   * Port 443 (SSL) : untuk open port https pada server

![30](../asset/030.png)

6. Buat key pair yang digunakan untuk mengakses SSH ke server yang sudah dibuat

![31](../asset/038.png)

7. Untuk Proses pembuatan server sudah selesai, setelah itu tambahkan elastic ip agar server dapat mengakses jaringan internet ke luar.

![31](../asset/031.png)

![32](../asset/032.png)

![33](../asset/033.png)

8. Jika sudah coba akses ssh ke server yang sudah dibuat menggunakan key pair

![34](../asset/034.png)

10. server berhasil dibuat
    ![35](../asset/035.png)

## SERVER FOR APPLICATION

1. Untuk pembuatan server for application, stepnya sama dengan proses pembuatan server reverse proxy, namun untuk konfigurasi yang harus dibedakan adalah konfigurasi dari security group yang dimana protokol yang di atur adalah all traffic dan hanya menggunakan ip private saja![38](../asset/037.png)


2. Jika sudah untuk server Reverse Proxy dan Server For App sudah berhasil dibuat![35](../asset/039.png)
