A.	PRAKTIKUM I
1.	Kita buat project baru dengan mengetik perintah berikut pada Terminal atau CMD composer create-project laravel/laravel:^10.0 laravel-auth-app
   
![image](https://github.com/user-attachments/assets/e5fdaae7-edb1-4493-b013-1f3a7c40005a)
 
2.	Kemudian kita modifikasi file .env agar dapat terkoneksi dengan SQLite seperti berikut.
   
 ![image](https://github.com/user-attachments/assets/86660066-5f3e-4e5e-aca9-21c750d56413)

3.	Setelah selesai, selanjutnya kita lakukan migrate dengan perintah berikut php artisan migrate
   
 ![image](https://github.com/user-attachments/assets/2b954805-efb7-4dc4-895e-bc7a793f29ca)

4.	Sekarang kita unduh starter kit breeze dengan composer melalui perintah berikut composer require laravel/breeze --dev
   
 ![image](https://github.com/user-attachments/assets/76958367-7b99-4696-a87f-940cac399450)

5.	Kemudian install dengan perintah artisan berikut php artisan breeze:install Proses instalasi seperti gambar berikut
    
 ![image](https://github.com/user-attachments/assets/21eef793-cace-476a-8db7-6b8a72e7fd5b)

6.	Selanjutnya jalankan perintah berikut
   
 ![image](https://github.com/user-attachments/assets/16b87c38-5eea-44ae-a5a3-8a89d16244a8)

7.	Selanjutnya, kita run dengan perintah php artisan serve lalu hasilnya seperti gambar berikut. Perhatikan di pojok kanan atas, terdapat menu untuk Log in dan Register.
   
 ![image](https://github.com/user-attachments/assets/0b71fd55-0dd1-4221-ac2e-b61ccc9e7463)

