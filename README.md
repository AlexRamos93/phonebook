# Phonebook

> CRUD application using Symfony 4.

## Getting Started

``` bash
# Install dependencies
composer install

# Edit the env file and add DB params

# Create Article schema
php bin/console doctrine:migrations:diff
# Run migrations
php bin/console doctrine:migrations:migrate

# Build for production
npm run build

# To start the application
php bin/console server:run
```
### Prerequisites

You need MySQL installed and php.

## Built With

* [PHP](http://php.net/) - Language used.
* [Symfony Framework](https://symfony.com/) Framework used.
* [MySQL](https://www.mysql.com/) - The relational database used in the project.


## Authors

* **Alexandre Ramos** - [Portifolio Page](http://alexramos.esy.es)
