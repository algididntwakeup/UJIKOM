# UJIKOM
enjoy
git clone https://github.com/algididntwakeup/UJIKOM
cd ujikom
composer install
cp .env.example .env
edit .env lalu sesuaikan setting database
php artisan key:generate
php artisan migrate
php artisan db:seed
php artisan serve
buka http://localhost:8000
