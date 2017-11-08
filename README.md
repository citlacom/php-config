# php-config
Customized php configuration files for development.

# Instructions

Rename the default PHP settings files:
- mv /Applications/MAMP/bin/php/php5.6.31/conf/php.ini /Applications/MAMP/bin/php/php5.6.31/conf/php.ini.back
- mv /Applications/MAMP/bin/php/php7.1.8/conf/php.ini /Applications/MAMP/bin/php/php7.1.8/conf/php.ini.back

Create a symbolic links on MAMP environments:
- ln -s ~/php-config/php-56.ini /Applications/MAMP/bin/php/php5.6.31/conf/php.ini
- ln -s ~/php-config/php-71.ini /Applications/MAMP/bin/php/php7.1.8/conf/php.ini
