# Laravel Blog
This is a Laravel blog, make with laravel 8 and bootstrap

## How to use
#### Git Clone or Download this Repository and Change Directory
- **Clone**
```
git clone https://github.com/zulfikar-dityaa/laravel-blog.git lara-blog
```
- **Change Directory**
```
cd lara-blog
```

#### Install Composer
```
composer install
```
#### Npm 
```
npm install && npm run dev
```

#### Create a copy of your .env file
```
cp .env.example .env
```
#### Generate an app encryption key
```
php artisan key:generate
```
#### Set up Database
- **setup database**
open file .env change everythings do you need
```
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=lara-blog
DB_USERNAME=root
DB_PASSWORD=
```
- **make a database, the name is lara-blog or somethings else,**
make sure the name of database same as DB_DATABASE=

#### Migrate Database and Load the Seeder
```
php artisan migrate --seed
```

#### Run Serve
```
php artisan serve
```

## Available user for test
- **superuser**
- - > superuser@mail.com
- - > superuserpassword
- **staff**
- - > staff@mail.com
- - > staffpassword
- **reporter**
- - > reporter@mail.com
- - > reporterpassword
- **user**
- - > userone@mail.com
- - > useronepassword
