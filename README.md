# M2 Magewire with Breeze theme Module

This module has been developed for Magento => 2.4.6

Orangecat_MagewireBreeze allows you to use [Magewire](https://github.com/magewirephp/magewire) with [Breeze](https://github.com/breezefront/module-breeze) theme

## Installation

The extension must be installed via `composer`. To proceed, run these commands in your terminal:

```
composer require orangecat/magewire-breeze
php bin/magento module:enable Orangecat_MagewireBreeze
php bin/magento setup:upgrade
php bin/magento setup:di:compile
php bin/magento setup:static-content:deploy
