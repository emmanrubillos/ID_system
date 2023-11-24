# ID_system

run composer install
run cp .env.example. .env
run php artisan key:generate
run php artisan migrate
run php artisan db:seed --class=AdminSeeder
run npm install
run npm run dev
php artisan optimize
php artisan serve
