php-simple-twig
==============

[![Build Status](https://travis-ci.org/WyriHaximus/php-simple-twig.png)](https://travis-ci.org/WyriHaximus/php-simple-twig)
[![Latest Stable Version](https://poser.pugx.org/WyriHaximus/simple-twig/v/stable.png)](https://packagist.org/packages/WyriHaximus/simple-twig)
[![Total Downloads](https://poser.pugx.org/WyriHaximus/simple-twig/downloads.png)](https://packagist.org/packages/WyriHaximus/simple-twig)
[![Code Coverage](https://scrutinizer-ci.com/g/WyriHaximus/php-simple-twig/badges/coverage.png?b=master)](https://scrutinizer-ci.com/g/WyriHaximus/php-simple-twig/?branch=master)
[![License](https://poser.pugx.org/wyrihaximus/simple-twig/license.png)](https://packagist.org/packages/wyrihaximus/simple-twig)

Wrapping event loop ticks into a promise. 

## Install ##

To install via [Composer](http://getcomposer.org/), use the command below, it will automatically detect the latest version and bind it with `~`.

```
composer require wyrihaximus/wyrihaximus/simple-twig 
```

## Usage ##

```php
use WyriHaximus\Twig\render;

$template = '{{ name }}';
$data = [
    'name' => 'Cees-Jan',
];

$result = render($template, $data);
echo $result; // Echos "Cees-Jan"
```

## License ##

Copyright 2018 [Cees-Jan Kiewiet](http://wyrihaximus.net/)

Permission is hereby granted, free of charge, to any person
obtaining a copy of this software and associated documentation
files (the "Software"), to deal in the Software without
restriction, including without limitation the rights to use,
copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the
Software is furnished to do so, subject to the following
conditions:

The above copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES
OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND
NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT
HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY,
WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING
FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR
OTHER DEALINGS IN THE SOFTWARE.
