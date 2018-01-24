This page contains a list of common causes of the Rainmeter and browser plugins not being able to connect and update info. It is split up into issue that affect just one browser or all.

## Firefox
### Firefox block the connection on most sites with default settings.
Firefox by default does not have an exception for unencrypted websockets for localhost like all other browsers. Thus you will need to go to the about:config page and set network.websocket.allowInsecureFromHTTPS to true by double clicking it.
<img src="https://github.com/tjhrulz/WebNowPlaying-BrowserExtension/raw/master/.wiki/firefoxOptionTweak.png" width="800">

## All versions
### Windows firewall is blocking Rainmeter requests
While this can affect more than just WebNowPlaying if Rainmeter is blocked by your firewall then it will not work at all. The quickest way to change this for most people is to type "Allow an app through the Windows Firewall" into start and open the program. Hit change settings in the top right and go down to Rainmeter in the list and allow it on both private and public networks.  
<img src="https://github.com/tjhrulz/WebNowPlaying-BrowserExtension/raw/master/.wiki/firewallTweak.png" height="400">

### Try rebooting
It is possible, although unlikely, for you machine to believe that WebNowPlaying is still setup from before when closing and opening Rainmeter in quick succession. If this happens no connection will connect until you do a reboot.