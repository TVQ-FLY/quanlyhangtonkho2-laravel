Clone Project dengan perintah terminal `gitbash` sebagai berikut:
```
git clone git@github.com:radhiant/laravel-inventoryweb.git
```
Atau bisa klik tombol download Zip dan extrak file tersebut
#### :arrow_right: Buat Database
Import file name Database `db_inventoryweb`

Setting `DB_DATABASE`, `DB_USERNAME`, `DB_PASSWORD` yang ada di file `.env` sesuai Nama Database mysql kalian

#### :arrow_right: Set Up
Run Terminal:
```
composer install
```
```
php artisan storage:link
```
#### :arrow_right: Import Database
Import file database `db_inventoryweb.sql` yang ada di folder `database/db` ke phpmyadmin 

#### :arrow_right: Jalankan Aplikasi
```
php artisan serve
```
copy & paste `http://127.0.0.1:8000/` ke browser anda.

#### :arrow_right: Login Default
username: `superadmin` password: `12345678`
<br>
username: `admin` password: `12345678`
<br>
username: `operator` password: `12345678`
<br>
username: `manajer` password: `12345678`

