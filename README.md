# Under Tor Tunnels

## Want more privacy on the web?
In this repo we'll be in touch with a great solution over VPN and easier setup process than configure your proxy. Using Tor Service.
*And it's completely FREE!!*


## How is Tor different from other proxies? 🧅
A typical proxy provider sets up a server somewhere on the Internet and allows you to use it to relay your traffic. This creates a simple, easy to maintain architecture. The users all enter and leave through the same server. The provider may charge for use of the proxy, or fund their costs through advertisements on the server. In the simplest configuration, you don't have to install anything. You just have to point your browser at their proxy server. Simple proxy providers are fine solutions if you do not want protections for your privacy and anonymity online and you trust the provider to not do bad things. Some simple proxy providers use SSL to secure your connection to them, which protects you against local eavesdroppers, such as those at a cafe with free wifi Internet.

Simple proxy providers also create a single point of failure. The provider knows both who you are and what you browse on the Internet. They can see your traffic as it passes through their server. In some cases, they can even see inside your encrypted traffic as they relay it to your banking site or to ecommerce stores. You have to trust the provider isn't watching your traffic, injecting their own advertisements into your traffic stream, or recording your personal details.

Tor passes your traffic through at least 3 different servers before sending it on to the destination. Because there's a separate layer of encryption for each of the three relays, somebody watching your Internet connection can't modify, or read, what you are sending into the Tor network. Your traffic is encrypted between the Tor client (on your computer) and where it pops out somewhere else in the world.

Doesn't the first server see who I am?
Possibly. A bad first of three servers can see encrypted Tor traffic coming from your computer. It still doesn't know who you are and what you are doing over Tor. It merely sees "This IP address is using Tor". You are still protected from this node figuring out both who you are and where you are going on the Internet.

Can't the third server see my traffic?
Possibly. A bad third of three servers can see the traffic you sent into Tor. It won't know who sent this traffic. If you're using encryption (like HTTPS), it will only know the destination. See this visualization of Tor and HTTPS to understand how Tor and HTTPS interact. <a href="https://support.torproject.org/about/">TorProject</a>


## Anonsurf
* Anonsurf is a script made by the development team at ParrotSec, which included Lorenzo Faletra (@palinuro), Lisetta Ferrero (@sheireen) and Francesco Bonanno (@mibofra), and that is maintained by Nong Hoang Tu (@dmknght).
* This tool offers you a great open-source, secure, and an easier way to enhance your system privacy.
* All traffic goes under the Tor tunnels.
* Works system-wide making everything you do while running Anonsurf almost untrackable.
* Can be used on both Linux and Windows.

## Using Anonsurf in a distro Linux outsides Parrot Os
Will be using this repo: https://github.com/Und3rf10w/kali-anonsurf

### Cloning the repo:

`git clone https://github.com/Und3rf10w/kali-anonsurf.git` 


### Open project's directory

`cd kali-anonsurf` 


### As Root > Give the installler permision to exectue

`# chmod +x ./installer.sh`


### As Root > Run the installer

`# ./installer.sh`


### Anonsurf commands

`Usage:
 anonsurf {start|stop|restart|change|status}

 start - Start system-wide anonymous
          tunneling under TOR proxy through iptables
 stop - Reset original iptables settings
          and return to clear navigation
 restart - Combines "stop" and "start" options
 change - Changes identity restarting TOR 
 status - Check if AnonSurf is working properly
----[ I2P related features ]----
 starti2p - Start i2p services
 stopi2p - Stop i2p services
`


### Under Tor Tunnels
*AS ROOT*
`# anonsurf start`

### View your "new Ip"

`# anonsurf myip`

### Tor Status, node, speed

`#anonsurf status`


### Testing Tor connection
* Go to: https://check.torproject.org/
  
##### If the answer is NO
* Use: `# anonsurf restart`
* Repeat Testing step


### Stop anonsurf

`# anonsurf stop`

##### Anonsurf will stop and clean its traces...



## Using Anonsurf on Windows  *Didn't test myself*:
Repo: https://github.com/ultrafunkamsterdam/AnonSurf

### Cloning the repo

`git clone https://github.com/ultrafunkamsterdam/AnonSurf.git`


### Open AnonSurf.exe



## Anonsurf ParrotSec
* High praises to one of the best tools available to use Tor proxy
* Visit their repo: https://github.com/ParrotSec/anonsurf



## Final Thoughts
* Anonsurf is an arguably user-friendly tool.
* Gives you a good all-around privacy.
* Protect your data from ads, trackers, etc.
* Be prepared to face an army of captchas 😆
* Not harm to anyone or anything using this tool
* Even Tor can be pwned: https://youtu.be/WZtsRSBNhuA?t=260
