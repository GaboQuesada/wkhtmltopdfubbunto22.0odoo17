Ubunto: 24/22.04 jammy / 20.04 focal / 18.04 bionic / 16.04 xenial



conocer version de ubunto   lsb_release -a


primero verificar cual tiene / si es instalada desde el script

wkhtmltopdf --version


ELIMINANDO 
sudo apt-get remove --purge wkhtmltopdf

sudo dpkg -r wkhtmltox

sudo apt-get purge wkhtmltox

sudo apt-get autoremove
sudo apt-get clean

INSTALACION

EN /usr/bin


ubunto 24/22.0

sudo wget https://github.com/GaboQuesada/wkhtmltopdfubbunto22.0odoo17/raw/main/wkhtmltox_0.12.6.1-2.jammy_amd64.deb

ubunto 20.04

sudo wget https://github.com/GaboQuesada/wkhtmltopdfubbunto22.0odoo17/raw/main/wkhtmltox_0.12.5-1.focal_amd64.deb

sudo apt-get update
sudo apt-get install -y xfonts-75dpi xfonts-base

apt --fix-broken install

ubunto 24/22.0

sudo dpkg -i wkhtmltox_0.12.6.1-2.jammy_amd64.deb

ubunto 20.04

sudo dpkg -i wkhtmltox_0.12.5-1.focal_amd64.deb

VERIFICAR

wkhtmltopdf --version


sudo find / -name wkhtmltopdf

sudo ln -s /usr/local/bin/wkhtmltopdf /usr/bin/wkhtmltopdf



/usr/local/bin/wkhtmltopdf --version


