
Que es Xampp.

Es un paquete de software libre que incluye una serie de herramientas necesarias para ejecutar aplicaciones PHP en un ambiente local, las herramientas son:

Servidor Web Apache
Base de Datos MariaDB
Interprete de PHP/Perl
PhpMyAdmin
Es fácil de usar y esta disponible para GNU/Linux, Windows y OS X.

¿Como instalar Xampp?

Lo primero es descargar desde la página oficial el ejecutable de Xampp según nuestro sistema operativo y la versión de PHP que necesitamos, para este caso PHP XAMPP-VM / PHP 7.2.12

Pasos 
Ejecutar los comandos uno después de otro

$ wget  https://www.apachefriends.org/xampp-files/7.2.12/xampp-linux-x64-7.2.12-0-installer.run
 

sudo chmod +x xampp-linux-x64-7.2.12-0-installer.run
$ sudo ./xampp-linux-x64-7.2.12-0-installer.run
 
sudo /opt/lampp/lampp start
sudo apt install net-tools
$ sudo /opt/lampp/lampp start
$ sudo /opt/lampp/lampp stop

$ sudo /opt/lampp/lampp security

sudo nano /opt/lampp/etc/extra/httpd-xampp.conf
 

sudo /opt/lampp/lampp restart



# XamppOnUbuntu
Configuración de Servidor Xampp en ubuntu 18
