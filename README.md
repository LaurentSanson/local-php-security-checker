Local php security checker
==========================

Since Symfony has deprecated their online version of security checker, we supply our own composer package containing : https://github.com/fabpot/local-php-security-checker

Install
-------

```sh
composer require laurentsanson/local-php-security-checker
```


Usage
-----

```sh
./vendor/bin/security-checker --path=$PWD
```
