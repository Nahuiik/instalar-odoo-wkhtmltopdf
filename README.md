# instalar-odoo-wkhtmltopdf
Instalar wkhtmltopdf en Linux para Utilizarlo en Odoo
<p>Opcional</p>
<pre>sudo apt-get -f install</pre>
<p>Obligatorio</p>
<pre>
<code>
sudo apt-get install libxrender1 fontconfig xvfb libjpeg-turbo8
cd /opt
git clone https://github.com/Nahuiik/instalar-odoo-wkhtmltopdf
cd instalar-odoo-wkhtmltopdf
sudo dpkg -i wkhtmltox-0.12.1_linux-trusty-amd64.deb
sudo cp /usr/local/bin/wkhtmltoimage /usr/bin/wkhtmltoimage
sudo cp /usr/local/bin/wkhtmltopdf /usr/bin/wkhtmltopdf
</code>
</pre>
