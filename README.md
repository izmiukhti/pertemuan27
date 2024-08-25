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

B.	PRAKTIKUM II
1.	Kita akan menggunakan Laravel Blog Starter Kit yang dibangun dengan Laravel 10, Tailwind CSS, AlpineJS, dan Livewire.
2.	Lakukan git clone dengan perintah berikut di Terminal 
git clone https://github.com/jti-polinema/laravel-blogkit 
![image](https://github.com/user-attachments/assets/cda0ceab-9697-479f-b1cf-5a16223d3a6a)

3.	Kemudian buka project laravel-blogkit dengan code editor favorit Anda, lalu install dependensi dengan perintah composer install
![image](https://github.com/user-attachments/assets/38927690-ef50-4f67-b4e2-736ed2a967fc)

4.	Pada bagian config file config/blog.php ubahlah demoMode menjadi true
![image](https://github.com/user-attachments/assets/6491aaf4-8474-4d31-afa2-17465cd739b2)

5.	Lalu rename file .env.example menjadi .env 
6.	Sesuaikan DB config dengan menggunakan SQLite seperti pada praktikum 1 sebelumnya. 
![image](https://github.com/user-attachments/assets/5d5bca40-1c4b-40af-b118-064bf2bfcfc2)

7.	Kemudian jalankan perintah berikut untuk menggenerate key pada .env 
php artisan key:generate 
![image](https://github.com/user-attachments/assets/a4daaff9-fd34-4875-896b-73421d71fcff)
 
8.	Lalu lakukan migration dengan perintah berikut php artisan migrate 
![image](https://github.com/user-attachments/assets/2dd8684d-5f87-4d14-b474-0beef65c6bdd)
 
9.	Selanjutnya kita buat akun admin dengan cara menjalankan perintah berikut php artisan admin:create 
![image](https://github.com/user-attachments/assets/687e659d-ab11-4b00-8ab0-a443e9e650c4)

Hasilnya seperti gambar berikut Terakhir coba running dengan perintah php artisan serve 
![image](https://github.com/user-attachments/assets/b98ea87d-0947-423d-867b-9b77faf79481)

10.	Coba login dengan akun admin, pelajari setiap menu dan tampilan yang ada.
![image](https://github.com/user-attachments/assets/e398b34e-c30c-43ff-8603-eb9e3f36b6f8)


11.	Buatlah akun dengan cara register, lalu ubah otorisasi antara admin, guest, author, dan akun yang diblokir (banned).
![image](https://github.com/user-attachments/assets/850e5f37-b130-4511-b10f-bde8650a1459)

![image](https://github.com/user-attachments/assets/25ce3e4a-7b8f-4868-ae0a-06abeebe0262)


