# homebrew-httpd-apache-config-files
custom configuration files for homebrew httpd. 

Create a user folder to put your user config file. 
~$ sudo mkdir usr/local/etc/httpd/users     
----------------------------------------------------------------------

![image](https://user-images.githubusercontent.com/58430236/233967131-0b5a607c-35b3-43c7-86f6-68499c5595ae.png)

Replace your /usr/local/etc/httpd/httpd.conf with the one here.
Replace your your /usr/local/etc/httpd/extra/httpd-userdir.conf with the one here. 

----------------------------------------------------------------------
![image](https://user-images.githubusercontent.com/58430236/233966989-6267a6fa-0d8a-47b4-ba05-197de8475197.png)


LoadModule php_module /usr/local/opt/php@8.2/lib/httpd/modules/libphp.so (to your php version)-> LoadModule php_module /usr/local/opt/php(your php version )/lib/httpd/modules/libphp.so

In httpd.conf file, change 
DocumentRoot "your choosen path"
<Directory "your choosen path">

User yourname
Group staff

----------------------------------------------------------------------











