# easychains-
For those who don't want to buy proxies. I'm only learning, don't judge me too much :) 
This script was developed to let you connect to public proxies automatically
It uses proxies from socks-proxy.net.Remember that these proxies aren't 
reliable and your traffic might be monitored.
To begin using this script you have to do the following:
1) Install proxychains, html2text
	apt-get install proxychains
	apt-get install html2text
2) Download the package and unpack it to root directory
	cd /root/easychains 
	rm /etc/proxychains.conf
3) Now everytime you run ./easychains. the list of your proxies will be
updated. 
4) I recommend you to add easychains to your cron file and get it to
update every 20 or 30 min or everytime you boot up
 e.g. */15 * * * * /root/easychains/easychains
 	  (Proxies are updated every 15 min) 
Happy Hacking ^_^
From krepper1337 with love :*
