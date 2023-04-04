# To make susan-html-website live follow the below commands

sudo yum update -y
sudo yum install git httpd -y
httpd -v
sudo systemctl start httpd
sudo systemctl enable httpd
sudo systemctl status httpd
git clone https://github.com/vickydevo/susan-html-website.git
cd susan-html-website
sudo cp -r * /var/www/html
# whitelist 80
