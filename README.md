# Tugas Personal 2

Tugas Personal 2 Moch Freskha Fauzi R - Authentication Page

Requirement:
XAMPP, PHP,
Composer,
Laravel,
Node.js

### Isi Project
1. Login Page:
- Validasi User dan Pass 3x, Jika lebih maka cooldown selama 30 detik
- Captcha Client Side (reCaptcha Google V3)
- ~~Captcha Server Side Integration / Rules~~ (Error)
2. Register Page
- Password minimal 10 karakter
- Password terdiri dari huruf kapital dan kecil, angka, simbol. Jika tidak terpenuhi maka muncul alert.
3. Forgot Password Page
4. Reset / Update Password Page

### Running Project

Untuk tugas kedua saya menggunakan laravel dan reactjs

File yang saya lampirkan dalam bentuk zip agar menghindari error.

command yang dijalankan:

```npm install```

``npm run dev`` 

dan

```php artisan migrate```

``php artisan ser``

dan untuk server yang dibuka adalah php artisan ser

Jika terjadi error Permission Denied saat menjalankan ``npm run dev`` , Jalankan command berikut:

``npm rebuild``

Jika terjadi error ``file_put_contents: Failed to open stream, no such file or directory``

jalankan command berikut:
```
composer dump-autoload
composer install
php artisan cache:clear
php artisan config:clear
php artisan optimize
php artisan clear-compiled
```
