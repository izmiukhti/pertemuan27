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
![image](https://github.com/user-attachments/assets/50ad00ac-c170-4bca-a1b0-de60e041e6e9)


11.	Buatlah akun dengan cara register, lalu ubah otorisasi antara admin, guest, author, dan akun yang diblokir (banned).
![image](https://github.com/user-attachments/assets/bdef0466-5ffc-4d42-a776-7174bdc3f6d7)
![image](https://github.com/user-attachments/assets/1d3dc6b7-ff2e-4a6b-8184-21c34177145e)


