# Server
Latest apache php mysql server that just works

This is a 64 bit version of apache mysql server
Apache/2.4.20 (Win64) 
PHP/7.0.7
Mysql  5.5.50
phpmyadmin 4.6.2
mysql workbench 6.3
All passwords and usernames are root and root.

This will work on any drive including a USB stick

I have configured the apache to work with pretty permalinks’ and pictures of SMF 2, wordpress, joomla, and prestashop all working on this system can be seen in the folder server progs. there is also some files configured for wordpress multisite and these can be found under the folder website/wp-multisite/. 

This is so simple to install just unzip the package to your hard drive, your secondary drive or your USB Stick.
All the apache mysql and php files have been configured to work from "/" 

If you wish to use curl you must copy the file libssh2.dll in the folder /server-progs/ to your windows directory IE c:\windows\

open ssl is configured by apache to only work from your master drive so you must copy the folder /openssl-1.0.2h-win64/ to your system hard drive ie c:\openssl-1.0.2h-win64\ and you must use this exact folder description not c:\openssl\ it must be "openssl-1.0.2h-win64"

That’s basically it, it’s a simple unzip to a selected drive installation.
It has been tested with Joomla, Wordpress, Wp multisite, Prestashop, SMF 2 not smf 2.1 as Smf have not upgraded their system to work with MYSQLi.

you will also need a temp and tmp folder in windows or you will get erors, so just create a windows/ temp and a windows/tmp folder/ one of these will exist and the other must be created...

Enjoy 

John




