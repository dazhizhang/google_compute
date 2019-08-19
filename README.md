# google_compute

gcloud init <br>
gcloud compute ssh george@gedion <br>
https://cloud.google.com/compute/docs/tutorials/basic-webserver-apache?refresh=1  <br> 
https://cloud.google.com/appengine/docs/standard/php7/quickstart <br> 

php extension 安装：
simplexml ： ubuntu安装sudo apt-get install php-xml /centos安装yum install php-xml

====================================================

zip 安装
先安装libzip：

sudo wget https://nih.at/libzip/libzip-1.2.0.tar.gz
 sudo tar -zxvf libzip-1.2.0.tar.gz 
cd libzip-1.2.0 
sudo ./configure 
sudo make && sudo make install
安装zip：

sudo wget http://pecl.php.net/get/zip-1.13.5.tgz
sudo tar -zxvf zip-1.13.5.tgz
cd zip-1.13.5
sudo usr/local/php/bin/phpize
sudo ./configure --with-php-config=/usr/local/php/bin/php-config
sudo make && make install

=====================================================

make ：
sudo apt-add-repository ppa:ubuntu-desktop/ubuntu-make 
sudo apt-get update 
sudo apt-get install ubuntu-make 
