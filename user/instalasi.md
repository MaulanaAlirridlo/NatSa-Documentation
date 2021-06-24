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

# registrasi
disini kita harus registrasi terlebih dahulu 
kita membutuhkan ktp untuk data diri 
ikuti semua persyaratan yang diperlukan pada saat registrasi tersebut

#login
pertama kita harus memasukan email dan password
jika belum login dipersilahkan untuk registrasi terlebih dahulu
jika sudah baru kita login ke email tersebut
setelah login disitu anda dipersilahkan memilih apa yang anda perlukan