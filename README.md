# IAAC
sudo -i 
     apt-get update
     apt-get upgrade
     sudo apt-get install wget unzip apache2 -y
     cd /tmp/
     wget https://www.tooplate.com/zip-templates/2120_ben_resume.zip
     unzip -o 2120_ben_resume.zip
     cp -r 2120_ben_resume/* /var/www/html/
     systemctl restart apache2
