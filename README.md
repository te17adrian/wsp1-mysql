# wsp1-mysql

## Starta servern
öppna ubuntu och kör

	sudo apt service mysql restart
  
  
	sudo apt service apache2 restart

om apache 2 inte startar pga port80: stäng av branchcache i device manager!

## MYSQL

**setup**
Kör
	sudo mysql -u root

 grant all privileges on *.* to 'account'@'localhost' indentified by 'password';
 
 pass: a

create database sqlintro
