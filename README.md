"# addressbook"

bash下指令:<br/>
git clone https://github.com/CODEbyPoHsiang/addressbook<br/>
cd addressbook<br/> 
composer install --no-plugins --no-scripts<br/>
cp .env.example .env<br/>


在 phpmyadmin 手動建立同名資料庫或另用DB指令新增<br/>
"# phpmyadmin create database, only doing once" <br/>
DB name:marathon select:utf8mb4_unicode_ci mysql -u root -p <br/>
--> create database if not exists marathon default character set utf8mb4 collate utf8mb4_unicode_ci; <br/>
--> exit<br/>

php指令:<br/>
php artisan migrate (自動建表)<br/> 
php artisan db:seed (自動寫入假資料)<br/>

php artisan key:generate (創立key) <br/>
php artisan serve (運行)<br/>