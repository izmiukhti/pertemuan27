A.	PRAKTIKUM I
1.	Kita buat project baru dengan mengetik perintah berikut pada Terminal atau CMD composer create-project laravel/laravel:^10.0 laravel-auth-app
   
![image](https://github.com/user-attachments/assets/d26a04cc-cba6-43ca-9190-09e585617938)
 
2.	Kemudian kita modifikasi file .env agar dapat terkoneksi dengan SQLite seperti berikut.
   
![image](https://github.com/user-attachments/assets/20df908d-7498-420e-ba9e-d63967233719)

3.	Setelah selesai, selanjutnya kita lakukan migrate dengan perintah berikut php artisan migrate
   
![image](https://github.com/user-attachments/assets/48064785-be44-48f7-aa30-d507316c0ca4)

4.	Sekarang kita unduh starter kit breeze dengan composer melalui perintah berikut composer require laravel/breeze --dev
   
![image](https://github.com/user-attachments/assets/7d946f7f-764b-4dd1-b571-09df921d3c27)

5.	Kemudian install dengan perintah artisan berikut php artisan breeze:install Proses instalasi seperti gambar berikut
    
![image](https://github.com/user-attachments/assets/7e9075c3-4adb-4f1f-add4-8ff1a17fce65)

6.	Selanjutnya jalankan perintah berikut
   
![image](https://github.com/user-attachments/assets/4364cf2e-6673-4a9d-b3d8-1bf897a85599)

7.	Selanjutnya, kita run dengan perintah php artisan serve lalu hasilnya seperti gambar berikut. Perhatikan di pojok kanan atas, terdapat menu untuk Log in dan Register.
   
![image](https://github.com/user-attachments/assets/5720f311-cca9-475c-a87c-72ac30e6059e)


