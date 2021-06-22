Frequently Asked Question
-------------------------

Can I install Pinecraft on a distro that has a desktop environment?
No.

Can I use any distro?
No. It has to be a Debian-based distro. Please observe the Base Distro information in the docs.

How do I become admin?
See https://www.youtube.com/watch?v=1A4FtaiNkrg

How do I add plugins?
Stop your server with ~/minecraft/stop and then place the plugin file in ~/minecraft/plugins folder. Reboot or restart your server.

Does Insert Plugin Name work with Pinecraft?
Pinecraft Installer simply installs Minecraft server. If you chose a flavor that works with said plugin, then yes, it should work - but that has nothing to do with Pinecraft (which is only an installer).

How do I let my friends connect?
I speak about this in https://www.youtube.com/watch?v=1A4FtaiNkrg - of course you'll need some networking knowledge to open the port in your firewall. If you're not sure how to do that, please get a geek friend to help. It can be a security risk opening ports without actually knowing what you're doing. You can play on your LAN immediately by adding your Pinecraft server's local IP address. If you don't know it (weird, since you're ssh'd into it?) type this on your Pinecraft server and look for the INET address that corresponds with your home network (probably starts with 192.168, for example): ip a

Does it have to be a Raspberry Pi 4?
No. But Pinecraft is a new project, and has very little funding thus far. I'm focusing on the Pi 4 since it is powerful enough and can be overclocked, but keeps it so I can focus support on a single device for now. You're welcome to try Pinecraft Installer on other devices, but troubleshooting will be up to you. Just keep in mind you need at least 4 GB RAM, fast media, a decently fast CPU, and a Debian-based distro with no desktop environment. Our Patron-exclusive Pinecraft server is running on Debian 10 in a virtual machine.
