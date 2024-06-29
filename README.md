**Odoo Environment**

This is an Odoo environment running version 16.0.

**Requirements**

Ubuntu 20.04 LTS or later

Python 3.10 or later

PostgreSQL 14 or later

Git

**Setup Installation**

Installing linux  through USB boot using rufus 

checking python3 --version

installing pip3: sudo apt install python3-pip

installing git: sudo apt install git

Adding email to git: git config --global user.email "areejchaudary807@gmail.com"

Adding username to git: git config --global user.name "Areej07"

Making directory: mkdir programming

Changing path to directory: cd programming

Making subdirectory: mkdir src

Making another subdirectory: mkdir env

Changing path to src subdirectory: cd src

Cloning odoo github repository: git clone https://github.com/odoo/odoo.git

Installing postgresql database: sudo apt install postgresql postgresql-client

creating postgresql user: sudo -u postgres createuser areej

opening postgresql interactive shell: sudo -u postgres psql

creating database: create database realestate_db;

Once the Odoo repository has been cloned, we’ll install some more dependencies sudo apt install python3-pip libldap2-dev libpq-dev libsasl2-dev virtualenv

Return to the programming directory and then cd into env: $ cd /home/areej/programming/ $ cd env/

Now make a Python virtual environment with your project name: sudo apt install python3-virtualenv $ virtualenv learning_env $ cd ..

Now to activate your virtual environment: $ source env/learning_env/bin/activate

Once  virtual environment is activated, install all the packages/libraries you will need for working with Odoo: $ pip3 install -r src/odoo/requirements.txt

Addons Estate

**Estate Addon Directory Structure**

Data

Models

Security

Views

init.py

Manifest.py
