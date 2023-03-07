+++
order = 69 #order of the project
uri = "shibeship" #name of the folder
date = "2023-02-01" #date creation
title = "ShibeShip" #name of the project
aliases = ["ShibeShip"] # name of the project
type = "gettingstarted" # getting-started
subtype = "install" # introduction, install, contents
version = "v69.420"
[ author ]
  name = "qlpqlp (twitter.com/inevitable360)"
+++
<h2 id="quick-start">Quick start</h2>

1- Get an Linux Hosting Account or Web Server that supports PHP (V. 7.3 =>) + MySQL/MariaDB (also works locally with Docker or Xampp for exemple)

2- Upload all files (excluding shibeship.sql and readme.md) to your Hosting Account.

3- Now edite the file inc/config.php and add your database conections and settings

4- Create a cron task to run every minute to poin to inc/cron.php

5- Make sure the file inc/vendores/libdogecoin-php/libdogecoin-json-php have CHMOD 0755

<h4 id="via-npm">Notes:</h4>

This is a Beta Version so can be some bugs that are not fixed yet
It generates real Dogecoin Wallets and it stores on the DataBase to send to all Sellers wen a Buy is detected.
