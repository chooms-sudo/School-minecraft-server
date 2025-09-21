# School-minecraft-server

So I am a 13 yo 8th grader and I recently got into networking,servers,linux,yk all that jazz,and I did this sysadmin experiment where I ran a school Minecraft server for about 2 weeks to see player behavior,complaints,etc. To see what I could fix and make the experience better for the users. And I am making this guide so if you wanted to make your own 24/7 minecraft server you could! making use of old hardware.

#Step 1 Installing the OS.
You will need an old computer or laptop you don't use really anything with a decent amount of ram works. ( > 6 gigabytes of ram)

You will then need to flash a USB thumb drive or a CD/DVD with an image of the Debian 13 distribution of Linux. 
There are plenty of guides online on how to boot into the installer.

Once in the installer you want to click on graphical install or use enter along with the arrow keys.

Next you will want to select a language. (in my case I chose english)

Then select your location since I live in Mexico I obviously chose Mexico but make sure to choose your location.
When you are asked to configure a keyboard layout you will want to choose your keyboard layout if you live in the US then choose American english or really just depending on your keyboard.

Before going on to the next step you will want to connect you future server to ethernet for best performance if you don't have acces to an ethernet port, you can buy cheap $10 USB to lan adapters on amazon or your local best buy.

You will now be asked for a hostname for your server, so how other devices will recognize your server. ex: your router will recognize your server as the hostname you choose.

Next you will be asked for a domain name, you can just skip this and click continue.

Next, for the root password choose something you will remember because the root use basically has all the privileges kind of like the admin account, If you leave it empty, the main account will be able to run root commands by using the command sudo which I recommend.

Alright listen up this step is crucial set up your username and password make them something easy like your name and write it down on a sheet of paper because you will need this.

Now choose your time zone since I live in border to california, I will choose pacific.

In partition disk choose guided-use entire disk, and select your disk DO NOT SELECT YOUR FLASH DRIVE, SELECT YOUR DISK.
DISCLAIMER: YOUR DISK WILL BE WIPED TO INSTALL THE OS SO INSTALL AT YOUR OWN RISK.
Next choose all files in one partition and click finish partitioning and write changes to disk.

Now wait a couple minutes for the base system to install, watch some youtube, relax.

Next in the package manager keep it as no and continue.
Now choose your country or the region closest to you so the mirror works better.
Next choose deb.debian.org and in proxy information leave it blank and continue.
When that's done keep popularity contest as no and continue.
In software selection unselect GNOME and Debian desktop enviorment and only leave standard system utilities checked and SSH server.
Wait a couple of minutes for the sysetm to install packages and come back later.

On Grub bootloader select yes and continue. Then choose your disk not flash drive, disk.
Now you should see INstallation complete, now remove your installation media and Continue.
In the GNU/GRUB screen click on Debian GNU/LINUX.
