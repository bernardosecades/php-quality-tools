# PHP Quality Tools

It is a metapackage that contains requirements related with PHP Static Code Analysis Tools.

## Tools

* sensiolabs/security-checker: The SensioLabs Security Checker is a command line tool that checks if your application uses dependencies with known security vulnerabilities.
* squizlabs/php_codesniffer: PHP_CodeSniffer is an essential development tool that ensures your code remains clean and consistent.
* friendsofphp/php-cs-fixer: The PHP Coding Standards Fixer tool fixes most issues in your code when you want to follow the PHP coding standards as defined in the PSR-1 and PSR-2 documents and many more.
* sebastian/phpcpd: It is a Copy/Paste Detector (CPD) for PHP code.
* pdepend/pdepend: PHP_Depend is an adaption of the established Java development tool JDepend. This tool shows you the quality of your design in the terms of extensibility, reusability and maintainability.
* phploc/phploc: It is a tool for quickly measuring the size and analyzing the structure of a PHP project
* sstalle/php7cc: It is a command line tool designed to make migration from PHP 5.3-5.6 to PHP 7 easier
* phpmd/phpmd: It is a spin-off project of PHP Depend and aims to be a PHP equivalent of the well known Java tool PMD.


## Usage

```
php vendor/bin/<tool-name>
```

Example:

```
php vendor/bin/phpcpd test.php
...

```

## Installation

```
composer require bernardosecades/php-json --dev
```
