# fuk-your-gov - in 8119 you heave tor socks4a-forward. Use privoxy in your browser to be in tor network

### How to build this:
1) copy the project via git clone
2) cd fuk-your-gov
3) docker-compose up -d # its build and add service on autoload
4) ???????
5) PROFIT!!!

### How use:
curl -L --proxy 127.0.0.1:8119 http://myblockedsite.com

### Test:
curl ifconfig.me # get your real IP

curl -L --proxy 127.0.0.1:8119 ifconfig.me # get you proxy IP

### Not enough? Need more features?..
### OK!!!

go to Firefox browser, and install plugin FoxyProxy.
![alt text](https://raw.githubusercontent.com/suicidesky92/fuk-your-gov/master/tutorialpics/icon.svg)

click Options on you plugin

Add your proxy. Click add button. 

![alt_text](https://github.com/suicidesky92/fuk-your-gov/raw/master/tutorialpics/Screenshot%20from%202021-02-16%2000-40-51.png)

If you haven't changed the project elevation settings, just copy my settings. Title or Description you can make your own. The username and password are empty (since the service listens on 127.0.0.1).

![alt_text](https://github.com/suicidesky92/fuk-your-gov/raw/master/tutorialpics/Screenshot%20from%202021-02-16%2000-41-13.png)

click save and edit patterns. Then add your white list. Below I gave an example of how to build patterns white list for specific addresses and site names.

![aly_text](https://github.com/suicidesky92/fuk-your-gov/raw/master/tutorialpics/Screenshot%20from%202021-02-16%2000-44-10.png)

This plugin has 3 modes of operation:

1) passes all traffic bypassing the proxy and lets your patterns pass through the proxy. This mode is the best for me, as I can open any sites without reducing the speed and only blocked through a proxy. 
2) disables the proxy in the browser. 
3) all traffic through the proxy (there will be small decreases in speed and response time increases, but if you do not know how to make patterns, this can help you)


That's all. For more information about FoxyProxy plugin, please contact the plugin developer.

## IMPORTANT!! Attention! This method does not guarantee the anonymity of visiting sites, moreover, it is not suitable for all sorts of dirty things. It just gives you access to content blocked by your favorite government :)

# USE THIS AND FUCK YOUR GOV!
