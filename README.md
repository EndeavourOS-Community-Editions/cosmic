# **EndeavourOS Cosmic Desktop install helper**

I used the user_pkglist option on EndeavourOS installer installing Cosmic alone not on top of other Desktop.

Run this before starting Installer on the liveSession of EndavourOS ISO (from a terminal):


With GDM as Login Manager (DM):

```
wget -qN --show-progress -O /home/liveuser/user_pkglist.txt https://raw.githubusercontent.com/EndeavourOS-Community-Editions/cosmic/main/user_pkglist.txt
```

Using SDDM as Login Manager (DM:

```
wget -qN --show-progress -O /home/liveuser/user_pkglist.txt https://raw.githubusercontent.com/EndeavourOS-Community-Editions/cosmic/main/user_pkglist-sddm.txt
```

And Lightdm Slick Greeter Login Manager (DM):

```
wget -qN --show-progress -O /home/liveuser/user_pkglist.txt https://raw.githubusercontent.com/EndeavourOS-Community-Editions/cosmic/main/user_pkglist-lightdm.txt
```

![3f95dec7bb0bf96a940c27632b199c69adb68523](https://github.com/user-attachments/assets/4d927a9a-01d1-4964-8d46-192563e2412a)


And make sure to install online choosing no-desktop ! 
![dc72ab749d3863f5a84157121c33601e6baaaa19](https://github.com/user-attachments/assets/7a0ba1de-dfde-4309-ad27-33a6977fe806)

If GDM is used it comes with a minimal GNOME session so --- 
On first boot change session to cosmic:
![2024-08-29_14-58](https://github.com/user-attachments/assets/5535cc8a-ed34-43c4-8292-45f63d44aca5)

and enjoy tinkering:
![2024-08-29_14-56](https://github.com/user-attachments/assets/84773cc4-f945-4069-b4c8-454098a9dace)
