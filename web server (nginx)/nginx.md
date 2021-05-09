					Web (NGINX) server
1.sudo apt update " sistemani yangilab olish "
2.sudo apt install nginx " serverni ustanovka qilish "
3.systemctl status nginx server holatini ko'rish 
4.curl -4 icanhazip.com   
http://IP_адрес_вашего_сервера (192.168.1.15)
sudo systemctl stop nginx
sudo systemctl start nginx
sudo systemctl restart nginx
sudo systemctl reload nginx
sudo systemctl enable nginx
sudo mkdir -p /var/www/example.com/html
sudo chown -R $USER:$USER /var/www/example.com/html  ?????
sudo chmod -R 755 /var/www/example.com
nano /var/www/example.com/html/index.html ???????
sudo ln -s /etc/nginx/sites-available/example.com /etc/nginx/sites-enabled
sudo nano /etc/nginx/nginx.conf
sudo systemctl restart nginx 
    					remove
  xamma paketlarni o'chirishda oldin stop ( 1.sudo systemctl stop "service_nomi " 2.  sudo service stop "service_nomi ")  kamandasini bajarib kiyin remove kamandasi bajariladi.

