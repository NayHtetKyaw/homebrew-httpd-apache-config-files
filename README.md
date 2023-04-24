# homebrew-httpd-apache-config-files
custom configuration files for homebrew httpd. 

Create a user folder to put your user config file. 
~$ sudo mkdir usr/local/etc/httpd/users     
----------------------------------------------------------------------

Replace the following.

Replace your /usr/local/etc/httpd/httpd.conf with the one here.
Replace your your /usr/local/etc/httpd/extra/httpd-userdir.conf with the one here. 

----------------------------------------------------------------------

LoadModule php_module /usr/local/opt/php@8.2/lib/httpd/modules/libphp.so (to your php version)-> LoadModule php_module /usr/local/opt/php(your php version )/lib/httpd/modules/libphp.so

In httpd.conf file, change 
DocumentRoot "your choosen path"
<Directory "your choosen path">

User yourname
Group staff

----------------------------------------------------------------------











