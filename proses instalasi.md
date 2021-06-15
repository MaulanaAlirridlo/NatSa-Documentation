proses instalasi
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

