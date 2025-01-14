## Meetme backend
Build status: [![Build Status](https://travis-ci.org/dsd-meetme/backend.svg?branch=master)](https://travis-ci.org/dsd-meetme/backend) [![Scrutinizer Code Quality](https://scrutinizer-ci.com/g/dsd-meetme/backend/badges/quality-score.png?b=master)](https://scrutinizer-ci.com/g/dsd-meetme/backend/?branch=master) [![Code Coverage](https://scrutinizer-ci.com/g/dsd-meetme/backend/badges/coverage.png?b=master)](https://scrutinizer-ci.com/g/dsd-meetme/backend/?branch=master) [![Build Status](https://scrutinizer-ci.com/g/dsd-meetme/backend/badges/build.png?b=master)](https://scrutinizer-ci.com/g/dsd-meetme/backend/build-status/master) [![Latest Stable Version](https://poser.pugx.org/dsd-meetme/backend/v/stable)](https://packagist.org/packages/dsd-meetme/backend) [![Total Downloads](https://poser.pugx.org/dsd-meetme/backend/downloads)](https://packagist.org/packages/dsd-meetme/backend) [![Latest Unstable Version](https://poser.pugx.org/dsd-meetme/backend/v/unstable)](https://packagist.org/packages/dsd-meetme/backend) [![License](https://poser.pugx.org/dsd-meetme/backend/license)](https://packagist.org/packages/dsd-meetme/backend)


This application uses laravel 5.1.* 

Api example web server: http://api.plunner.com. It is just an example, so we don't guarantee that everything works

# How to install

1. Clone repository
1. Install dependencies with composer `composer install` (http://getcomposer.org)

or simply

`composer create-project dsd-meetme/backend`

# How to develop
Use phpstorm is one of the best solution, since it has laravel plugin.

After cloning and installing repository:

1. Run `php artisan ide-helper:generate` and `php artisan ide-helper:meta`, so you create meta files for autocomplete in the IDE.
1. Run `php artisan ide-helper:models` each time models are updated (not in other case) and only if models are updated.
1. Install [laravel plugin](https://github.com/Haehnchen/idea-php-laravel-plugin)
 
# How to test with phpstorm
* Use phunit 4.* not 5
* execute as test phpunit.xml

# Notes
You should insert your name as author in composer file

# Credits
* [laravel framework](http://laravel.com/)
* [laravel ide helper](https://github.com/barryvdh/laravel-ide-helper)
* [laravel phpstorm plugin](https://github.com/Haehnchen/idea-php-laravel-plugin)
* [laravel noredirect traits for JWT](https://github.com/thecsea/jwt-auth)
* [laravel cors library](https://github.com/barryvdh/laravel-cors)