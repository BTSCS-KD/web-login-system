# Web Login Control System

All our software is open source to the public so people can make use and play around with the software we make and use on a daily basis. We always love to hear feedback from the community to help us improve on our systems sand usability.

## Installation

Installing the system is very easy as long as you have the following programs installed.

*Apache2
*Mysql
*Mysql controller like phpmyadmin
*Certbot
*PHP7.2

if not you can use this command. (sudo apt-get install apache2 mysql-client mysql-server phpmyadmin php)

If you have all of them you should be good to go.

upload files to the /var/html/www and make sure all files uploaded without any issues. a good program if your using windows to connect to a linux server is swish and you can use putty to ssh in.

Once you have done this go to this link http://YOUR_IP_ADDRESS/phpmyadmin login with the username and password you set. after you have done this create a new databae called login. after you have done this go into the database and at the top will be some buttons click on import. once you have done this upload the login.sql file in the DB folder in the files you uploaded to the server. once you have done this its ready to try it.

Start with going to http://YOUR_IP_ADDRESS/ and you will be prompted to enter a username and password. Default username and password is admin. once logged in you can enjoy.

## Development Respect
Please respect the time and effort we put into making these websites and applications and always leave credit to us in the footer, it wont hurt to leave it there as we are the original owners of the software and it tkes a long time to create the software. If you do wish to remove it please contact us and send us a copy so we can approve or decline the publishment. We dont ask for any money we just ask for acknowledgment in our software for it not to be removed. Thankyou

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
GNU GENERAL PUBLIC LICENSE
