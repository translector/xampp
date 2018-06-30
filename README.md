# xampp
Xampp configuration @ local Ubuntu 18.04

File to edit:

/opt/lampp/etc/extra/httpd-vhosts.conf


##### After adding the file restart lamp:

sudo /opt/lampp/lampp restart


##### To start Xampp Manager

sudo /opt/lampp/manager-linux-x64.run

##### I created an alias to make the start processs simple:

alias xampp='sudo /opt/lampp/manager-linux-x64.run'


So now I just need to type xampp in the terminal and the program will start after I type my password.

