# Installation de PHP

## Fichier de configuration  : php.ini


````conf
[PHP]

extension=openssl
extension=pdo_mysql
extension=fileinfo
extension=curl
extension=gd
extension=mbstring
````

## Installation de xdebug

- [](https://xdebug.org/docs/install)

suivez les instructions :

- https://xdebug.org/wizard


````conf
[PHP]

zend_extension = xdebug
xdebug.mode = debug
xdebug.start_with_request = yes


extension=openssl
extension=pdo_mysql
extension=fileinfo
extension=curl
extension=gd
extension=mbstring
````