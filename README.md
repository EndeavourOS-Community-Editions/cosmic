i used the user_pkglist option on EndeavourOS installer installing Cosmic alone not on top of other Desktop… but not using greetd and taken GDM as DM the packages list is this:

run this before starting the installer on the liveSession of teh EndavourOS ISO:

` wget -qN --show-progress -P -O /home/liveuser/user_pkglist.txt https://raw.githubusercontent.com/EndeavourOS-Community-Editions/cosmic/main/user_pkglist.txt` 

And make sure to install online choosing no-desktop ! 
