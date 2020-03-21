# qualitify

This is a set of code quality tools for my PHP Symfony projects. The tools used are:

* [PHP Code Sniffer](https://github.com/squizlabs/PHP_CodeSniffer)
* [PHP Mess Detector](https://github.com/phpmd/phpmd)
* [PHP Stan](https://github.com/phpstan/phpstan)
* [PHPUnit (Symfony bridge)](https://symfony.com/doc/current/testing.html)

## Requirements

Before using them, we need to install them in our project. So, launch this in the root of your project:

```bash
composer require --dev "squizlabs/php_codesniffer"
composer require --dev "phpmd/phpmd"
composer require --dev "phpstan/phpstan"
composer require --dev "symfony/phpunit-bridge"
```

Once they are all installed, add the 'qualitify' script to your 'bin' folder. Then you can execute:
```bash
bin/qualitify
```
