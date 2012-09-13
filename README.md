# Ash Fire

Ash Fire provides FirePhp debugging for Magento v-1.7.0.2.

## FirePHP

FirePHP is Firefox add-on that enables you to log to your Firebug Console, which makes it great debugging tool for any web developer.

[FirePhp Official website](http://firephp.org)

## Instalation

Simple copy the contents of the app folder to your Magento installation.

## Usage

```php

$firephp = Mage::helper('firephp')->getinstance(true);
        
$firephp->warn('This is a warning debug message.'); 

$firephp->info('This is a information debug message.');

$firephp->error('This is a error debug message.');

$firephp->warn($object);

```