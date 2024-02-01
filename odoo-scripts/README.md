This file will teach you how to run Odoo project using Docker and
 accepting custom_addons

1 - Clone Odoo source code:
- git clone git@github.com:odoo/odoo.git

2 - Create a folder at odoo/ folder called "custom_addons"
- If you are on Linux system or Mac you can run: mkdir custom_addons

3 - Create a folder at odoo/ folder called "config"
- If you are on Linux system or Mac you can run: mkdir config

4 - Create a file at config/ folder called "odoo.conf"
- If you are on Linux system or Mac you can run: touch odoo.conf or
touch config/odoo.conf if you aren't out of config/ folder

5 - Copy "docker-compose.yml" to odoo/ folder
- If you are on Linux system or Mac you can run: cp docker-compose.yml
to odoo/ folder - If you have any Docker issue, please go to the
Docker official documentation 

6 - Execute docker-compose.yml with the command:
- docker compose up -d

And you can execute Odoo normally. If you want to test a plugin
or create a plugin, just add it to "custom_addons" folder ;)
