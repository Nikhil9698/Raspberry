sudo apt update

sudo apt upgrade



sudo apt install apache2

sudo chown -R pi:www-data /var/www/html/

sudo chmod -R 770 /var/www/html/

sudo apt install php php-mbstring

sudo apt install mysql-server php-mysql mysql-client

sudo apt-get install phpmyadmin

sudo nano /etc/apache2/apache2.conf
  in last add this line
  Include /etc/phpmyadmin/apache.conf
  
sudo /etc/init.d/apache2 restart
