# Tor-on-OSX
native TOR support in OSX 


Preperations:
brew install tor


System Preferences -> Network 
From Location dropdown at the top, select Edit Locations…
Create a new location by hitting the plus button and name it Tor. 
Hitting Done will select the new location which is now ready to be configured
Go to Advanced > Proxies and activate SOCKS Proxy and add those values:
SOCKS proxy server: localhost
Port: 9050

Switching to the Tor location routes all network traffic on your system through Tor. 
Note that you have to repeat those steps for every other network interface if you use, say, Wi-Fi and Ethernet interchangeably.


Link to Alfred:
Workflows -> + -> Templates -> Essential -> Keyword to Terminal Command
Give it a nice name and as Script link to the tor.sh file
Example: sh /Users/USER/tor.sh
