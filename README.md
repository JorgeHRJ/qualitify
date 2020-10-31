# qualitify

This is a set of code quality tools for my PHP Symfony projects. The tools used are:

* [PHP Code Sniffer](https://github.com/squizlabs/PHP_CodeSniffer)
* [PHP Mess Detector](https://github.com/phpmd/phpmd)
* [PHP Stan](https://github.com/phpstan/phpstan)
* [PHPUnit (Symfony bridge)](https://symfony.com/doc/current/testing.html)
* [TwigCS](https://github.com/friendsoftwig/twigcs)

## Usage

Add the 'qualitify' script at your project 'bin' folder. Then just launch it by executing the following:
```bash
bin/qualitify
```

At the beginning it will check if the tools are installed in the project. If they are not installed, they will be
required for your dev environment using composer.

If you do not want some tool, just remove it from the array at the beginning of the script so it will not be installed.