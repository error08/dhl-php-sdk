# DHL PHP SDK

This *unofficial* library is wrapping some functions of the DHL SOAP API in order to easy create/delete shipments and labels.
Please note, that this is a fork of Petschko/DHL-PHP-SDK (https://github.com/Petschko/dhl-php-sdk). Many thanks to develop the initial version of that SDK.

## Requirements

- You need a [DHL developer Account](https://entwickler.dhl.de/) and - as long as you want to use the API in production systems.
- PHP-Version 7.2 or higher
- PHP-SOAP-Client installed + enabled on your Server. [More information on php.net](http://php.net/manual/en/soap.setup.php)

## Installation

### Composer

You can use [Composer](https://getcomposer.org/) to install the package to your project:

```
composer require error08/dhl-php-sdk
```

The classes are then added to the autoloader automatically.

### Without Composer

If you can't use Composer (or don't want to), you can also use this SDK without it.

To initial this SDK, just require the [_nonComposerLoader.php](https://github.com/Petschko/dhl-php-sdk/blob/master/includes/_nonComposerLoader.php)-File from the `/includes/` directory.

```php
require_once(__DIR__ . '/includes/_nonComposerLoader.php');
```

## Compatibility

This Project is written for the DHL-SOAP-API **Version 2 or higher**.

## Usage / Getting started

- [Getting started (Just a quick guide how you have to use it)](https://github.com/error08/dhl-php-sdk/blob/master/examples/getting-started.md)

Please have a look at the `examples` [Directory](https://github.com/error08/dhl-php-sdk/tree/master/examples). There you can find how to use this SDK also with Code-Examples, else check the _(Doxygen)_ [Documentation](http://docs.petschko.org/dhl-php-sdk/index.html) for deeper knowledge.

## Code Documentation

You find Code-Examples with explanations in the `examples` Directory. I also explain how it works.

## Motivation

Update that inactive SDK to the newest API version to make it useable for new projects.

## Contact

- You can Report Bugs here in the "[Issue](https://github.com/Petschko/dhl-php-sdk/issues)"-Section of the Project.
	- Of course you can also ask any stuff there, feel free for that!
	- If you want to use German, you can do it. Please keep in mind that not everybody can speak German, so it's better to use english =)
