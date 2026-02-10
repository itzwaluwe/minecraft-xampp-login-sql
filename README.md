Vanilla Minecraft XAMPP Project – First Release

This is the first public release of my Minecraft XAMPP Project, designed to be easy to use and accessible for everyone who wants to run a simple Minecraft-related web setup locally.

Features

Easy setup using XAMPP

Web-based interface via localhost

Includes database structure (see README)

Suitable for beginners

Requirements

XAMPP (Apache + MySQL/MariaDB)
Navicat for easy login edit
Open port 25565 (TCP & UDP)

Installation
xamp Download official website: https://www.apachefriends.org/download.html
Unzip the entire project into:
C:\xampp\htdocs
(or your custom XAMPP htdocs directory)

Start XAMPP and enable:

Apache

MySQL

Open your browser and go to:
http://localhost

Make sure port 25565 TCP/UDP is open on your system/router.

Check the README file for:

SQL database setup
create new database in xamp mysql using phpmyadmin with the name loginpagina and import sql file
SQL.sql

Database username and password
(credentials are currently stored in plain text)
so connect your navicat to your mysql database and create ur login like id 1 username: yourname password: yourpassword
Notes

This is an early release.

Feedback and improvements are welcome.
if there is a newer version just download the new server.jar and place it in the folder Server inside the htdocs of xampp ;)
