wkhtmltopdf
================

This repository contains the static compiled 64-bit AMD binary from the [wkhtmltopdf project](http://wkhtmltopdf.org/).
More about the functionality of wkhtmltopdf and wkthmltoimage can be found there.

Binaries for __Microsoft Windows__, also installable with composer, can be found here: [github.com/wemersonjanuario/wkhtmltopdf-windows](https://github.com/wemersonjanuario/wkhtmltopdf-windows)

Binaries for __CentOS 7__, also installable with composer, can be found here: [github.com/rvanlaak/wkhtmltopdf-amd64-centos7](https://github.com/rvanlaak/wkhtmltopdf-amd64-centos7)

## Installation

_Hint_:
The version of the binary is equal to the git tag.
To install the latest version, use: '0.12.6'.

### Packagist

This package can be found on [Packagist](http://packagist.org) and installed with [Composer](https://getcomposer.org/).

Require the package with:

    php composer.phar require olsgreen/wkhtmltopdf-amd64 "^0.12.6"

The binary will then be located at:

    vendor/olsgreen/wkhtmltopdf-amd64/bin/wkhtmltopdf-amd64

Also a symlink will be created in your configured bin/ folder, for example:

    vendor/bin/wkhtmltopdf-i386

### Usage

You can use the path constant to easily locate the binary in the PHP codebase: 

``` php
$path = \h4cc\WKHTMLToPDF\WKHTMLToPDF::PATH;
```

For realpath use following script

``` php
$realpath = realpath(\h4cc\WKHTMLToPDF\WKHTMLToPDF::PATH);
```
