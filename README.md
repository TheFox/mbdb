# MBDB.php

Read `.mbdb` files using PHP.

The `.mbdb` file extension is associated with the Apple iTunes, the standard manage application for iOS devices. A `.mbdb` file contains a list of files, that are stored in the backup of the iOS device. The MB database was introduced in iTunes 9.2.

## Project Outlines

The project outlines as described in my blog post about [Open Source Software Collaboration](https://blog.fox21.at/2019/02/21/open-source-software-collaboration.html).

- The main purpose of this library is to provide an interface to Apple's MB database format using PHP.
- The features should not go beyond Apple's features and functions. So the features of this software are limited to those of Apple.
- This list is open. Feel free to request features.

## Installation

The preferred method of installation is via [Packagist](https://packagist.org/packages/thefox/mbdb) and [Composer](https://getcomposer.org/). Run the following command to install the package and add it as a requirement to composer.json:

```bash
composer require thefox/mbdb
```

## Links

- [Packagist Package](https://packagist.org/packages/thefox/mbdb)
- [iphonebackupbrowser](https://code.google.com/p/iphonebackupbrowser/wiki/MbdbMbdxFormat)
- [ITunes_Backup](http://theiphonewiki.com/wiki/ITunes_Backup)
