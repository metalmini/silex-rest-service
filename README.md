New and improved version of:
- https://github.com/fjalvarezdd/SilexRestServer


first things first:

curl -sS https://getcomposer.org/installer | php

create composer.json

{
    "require": {
        "silex/silex": "1.0.*@dev",
        "doctrine/dbal": "2.3.3",
        "doctrine/common": "2.3.0"
    }
}

run composer to install base

./composer.phar install

