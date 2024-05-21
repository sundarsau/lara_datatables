# Use jQuery dataTables in Laravel project for pagination
 Laravel 11 Project with jQuery dataTables for pagination

# How To Use
1. Download the repository from https://github.com/sundarsau/lara_datatables

2. Extract it into a folder

3. Create a Database in MySQL

4. Copy .env.example to .env and update database name, username and password. For example, I used the database lara_form and updated database details as below:

   DB_CONNECTION=mysql DB_HOST=127.0.0.1 DB_PORT=3306 DB_DATABASE=lara_lang DB_USERNAME=root DB_PASSWORD=

5. Run composer install from project root

6. Run php artisan key:generate

7. Run php artisan migrate to create Laravel default tables
8. Run php artisan db:seed to create dummy data in users table

9. Run php artisan serve

10. In Browser run localhost:8000


License
This is an MIT license, you can modify the code according to your requirements
