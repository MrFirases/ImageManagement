ImagesApplication
=================

A Symfony project created on October 13, 2017, 8:37 pm.


# Image Management

A stock management system to keep information about image and license. There are two type of users: 
Administraor, who care about creating new image, update and delete it, also he have the ability to manage users, update or delete them, and change their roles.
Simple User, who can only visualize the list of stored images, search or sort the images list, and show details.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine.

### Installing

A step by step series of examples that tell you have to get the project running.

After downloading the project and acceding to its directory, run this command to install all required bundle with composer.

```
composer update
```

After that, it will ask you to fill some information like database name, username, password...

Then, run this command to create the database and create your tables.

```
php bin/console doctrine:database:create

php bin/console doctrine:schema:update --force
```

## Running the project

Just run this command 

```
php bin/console server:run
```

