# laravel-beginners-tutorial
All course files for the Laravel for Beginners playlist on The Net Ninja YouTube channel.

Each lesson in the playlist has it's own branch. To see the code for a lesson, select that branch from the dropdown.


Needs :
- Migration file (to create a table)
- Routes and views
- Controller file (to control routes)
- Model [to communicate with DB (used in the controller file)]


This will generate only a new model :
php artisan make:model Kebab


This will generate a model + controller + migration :
php artisan make:model Kebab -mc

This will create a new table (used after creating a new migration file) :
php artisan migrate

This will check if it is created :
php artisan migrate:status