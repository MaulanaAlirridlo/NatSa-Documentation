# cara menginstal / menjalani natsa2.0_website
# Clone the repository from GitHub and open the directory:
git clone https://github.com/MaulanaAlirridlo/natsa2.0_Website

# cd into your project directory
cd natsa2.0_Website

#install composer and npm packages
composer install
npm install && npm run dev

# Start prepare the environment:
cp .env.example .env // setup database credentials
php artisan key:generate
php artisan migrate
php artisan storage:link

# Run your server
php artisan serve

selesai

Project ini Dibuat dengan bantuan template
Admin Template oleh Miten5 Larawind
e-commerce oleh tailwindcomponents

Project made possible thanks to:
Miten5 Larawind - https://github.com/miten5/larawind
tailwindcomponents - https://tailwindcomponents.com/
Laravel Jetstream - https://jetstream.laravel.com/
Tailwind CSS - https://tailwindcss.com/
Windmill Dashboard - https://windmillui.com/dashboard-html