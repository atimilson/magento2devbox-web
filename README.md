# Intro

This repository forked from Magento DevBox - Web magento/magento2devbox-web, 
as way to install a Magento 2 development environment.

### Should be able to replace this image in your DevBox docker-compose.yml

#
Using Magento DevBox and needed
 - support for PHP 7.3 with required extensions
 - updated unision to prevent issues on windows with mismatch versions
 - opcache enabled by default
  ```
 /usr/local/etc/php/conf.d/docker-php-ext-xdebug.ini
 ```
 - xdebug disabled by default
 ```
/usr/local/etc/php/conf.d/docker-php-ext-xdebug.ini
```

Reload php-fpm after updating PHP config
```
sudo kill -USR2 {PHP-FPM PID}
```


 
 #
 - 2.0.0 upgrade to php-7.3, opcache enabled, xdebug disabled by default
 - 1.1.0 added support for Magento 2.3.2 by adding sodium
 - 1.0.0 updated fork for php-7.2
