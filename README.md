# google_compute

gcloud init <br>
gcloud compute ssh george@gedion <br>
https://cloud.google.com/compute/docs/tutorials/basic-webserver-apache?refresh=1  <br> 
https://cloud.google.com/appengine/docs/standard/php7/quickstart <br> 
<br>
php extension 安装：<br>
simplexml ： ubuntu安装sudo apt-get install php-xml /centos安装yum install php-xml<br>

====================================================<br>
<br>
zip 安装<br>
先安装libzip：<br>
<br>
sudo wget https://nih.at/libzip/libzip-1.2.0.tar.gz<br>
 sudo tar -zxvf libzip-1.2.0.tar.gz <br>
cd libzip-1.2.0 <br>
sudo ./configure <br>
sudo make && sudo make install<br>
安装zip：<br>
<br>
sudo wget http://pecl.php.net/get/zip-1.13.5.tgz<br>
sudo tar -zxvf zip-1.13.5.tgz<br>
cd zip-1.13.5<br>
sudo usr/local/php/bin/phpize<br>
sudo ./configure --with-php-config=/usr/local/php/bin/php-config<br>
sudo make && make install<br>
<br>
=====================================================<br>
<br>
make ：<br>
sudo apt-add-repository ppa:ubuntu-desktop/ubuntu-make <br>
sudo apt-get update <br>
sudo apt-get install ubuntu-make <br>
<br>
使用：<br>
umake ide eclipse <br>

=====================================================<br>
curl: <br>
For those who use php7.2, etc <br>
sudo apt-get install php7.2-curl<br>
