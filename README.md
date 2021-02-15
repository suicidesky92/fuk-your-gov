# fuk-your-gov - in 8119 you heave tor socks4a-forward. Use privoxy in your browser to be in tor network

How to build this:
1) copy the project via git clone
2) cd fuk-your-gov
3) docker-compose up -d # its build and add service on autoload
4) ???????
5) PROFIT!!!

How use:
curl -L --proxy 127.0.0.1:8119 http://myblockedsite.com

Test:
curl ifconfig.me # get your real IP

curl -L --proxy 127.0.0.1:8119 ifconfig.me # get you proxy IP

Not enough? Need more features?..
OK!!!

go to Firefox browser, and install plugin FoxyProxy
![alt text](http://cloud.hacore.ru/s/TQSA4ZaLt6pjBHi/download)
