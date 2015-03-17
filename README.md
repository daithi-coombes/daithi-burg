-------------------
BURG Custom Icons
=================
-------------------
#### Repository of additional icons for missing operating systems and linux distrobutions.

Link to my tutorial on creating custom burg icons: [Cusotmize BURG Boot Loader](https://coombesy.wordpress.com/2015/03/16/customize-burg-boot-loader/)

With the consistent release of linux distributions, propietary versions and also- operating systems I'm only finding out about - rebooting to check out the newly installed distro and finding the `?` icon in burg is starting to bug me.


<ul>note:</ul> Absolutely no attempt is made, yet, to get icon's looking nice. I'm not a graphic designer but if you are and have some icons to contribute then please do ;)

<u>icon sources:</u>
 - `linuxmint` icons, and a lot of the ground work, from this tutorial: [ubuntuhandbook.org - beautiful-boot-menu-burg-ubuntu](http://ubuntuhandbook.org/index.php/2014/02/beautiful-boot-menu-burg-ubuntu/)
 - bohdi icon http://de.wikipedia.org/wiki/Bodhi_Linux
 - studio icon: [http://en.icône.com](http://en.icône.com/images/icones/2/6/distributions-ubuntu-studio.png)

---------------

##Installation

place the contents of the `custom` directory in this repo in `/boot/burg/themes/custom/`

You may need to run:
```
$ sudo update-burg
```

then check everything works with:
```
$ burg-emu
```


##Icon not changing

You may have multiple OS's with the same class name in burg. eg all ubuntu derivitaves might be called ubuntu. See the wiki here on: [how to set OS class names in [Finding or editing the OS class name using the BURB configuration file]

####Roadmap:
 - do custom icons
 - (maybe a .deb installer?)
 - do custom theme
