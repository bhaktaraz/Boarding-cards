## Task
You are given a stack of boarding cards for various transportations that will take you from a point A to point B via several stops on the way. All of the boarding cards are out of order and you don't know where your journey starts, nor where it ends. Each boarding card contains information about seat assignment, and means of transportation (such as flight number, bus number etc).

## Installation
Using Composer :

```
composer install
```

If you don't have composer, you can get it from [Composer](https://getcomposer.org/)

## Run the application
Note that the source file used for this application is located in "sourcefile" folder.
Only Json format is supported for this example.

```
php index.php
```

## Tests
To run tests make sure you are in the main folder, and then you can run this command line :

```
vendor/phpunit/phpunit/phpunit --bootstrap tests/bootstrap.php tests
```


