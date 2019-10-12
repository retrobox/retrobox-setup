
# RetroBox Console - Modules
<div align="center" color="#0094D2">
	<img src="https://static.retrobox.tech/img/logo/illustration.png" height="180" alt="W" /><br><br>

    La console retro, open-source !
</div>


## ⚠ Only for the v3.06 !

#### Install all in one :

```bash
sudo wget -N https://raw.githubusercontent.com/retrobox/console-modules/master/allinone.sh && sudo chmod +x /home/pi/allinone.sh && sudo ./allinone.sh
```
#### Install the overlay :
```bash
sudo wget -N https://raw.githubusercontent.com/retrobox/console-modules/master/installoverlay.sh && sudo chmod +x /home/pi/installoverlay.sh && sudo ./installoverlay.sh
```
-----

##### Install screen driver (for 3.2inch screen) :
```bash
sudo wget -N https://raw.githubusercontent.com/retrobox/console-modules/master/installdisplaydriver.sh && sudo chmod +x /home/pi/installdisplaydriver.sh && sudo ./installdisplaydriver.sh
```

##### Install audio driver (MAX98357) :
```bash
curl -sS https://raw.githubusercontent.com/adafruit/Raspberry-Pi-Installer-Scripts/master/i2samp.sh | bash
```

##### Install Node JS (10.15) :
```bash
sudo wget -N https://raw.githubusercontent.com/retrobox/console-modules/master/installnode.sh && sudo chmod +x /home/pi/installnode.sh && sudo ./installnode.sh
```

##### Install displaySwitch (HDMI or lcd display) + automatic theme change based on screen resolution (needs retroboxtheme to work) :
```bash
sudo wget -N https://raw.githubusercontent.com/retrobox/console-modules/master/installdisplayswitch.sh && sudo chmod +x /home/pi/installdisplayswitch.sh && sudo ./installdisplayswitch.sh
```

##### Install RetroBox theme for RetroPie :
```bash
sudo wget -N https://raw.githubusercontent.com/retrobox/console-modules/master/installretroboxtheme.sh && sudo chmod +x /home/pi/installretroboxtheme.sh && sudo ./installretroboxtheme.sh
```

##### .bashrc (New MOTD when you login with SSH, based on RetroPie script) :
```bash
sudo wget -N https://raw.githubusercontent.com/retrobox/console-modules/master/installbashrc.sh && sudo chmod +x /home/pi/installbashrc.sh && sudo ./installbashrc.sh
```

##### Install the driver of inputs (Joysticks etc) :
```bash
sudo wget -N https://raw.githubusercontent.com/retrobox/console-modules/master/installinputsdriver.sh && sudo chmod +x /home/pi/installinputsdriver.sh && sudo ./installinputsdriver.sh
```

##### Install splashscreen :
```bash
sudo wget -N https://raw.githubusercontent.com/retrobox/console-modules/master/installsplashscreen.sh && sudo chmod +x /home/pi/installsplashscreen.sh && sudo ./installsplashscreen.sh
```

##### Install all config (config.txt & cmdline.txt) :
```bash
sudo wget -N https://raw.githubusercontent.com/retrobox/console-modules/master/installbootconfig.sh && sudo chmod +x /home/pi/installbootconfig.sh && sudo ./installbootconfig.sh
```

##### Install loading games splashscreen :
```bash
sudo wget -N https://raw.githubusercontent.com/retrobox/console-modules/master/installloadinggames.sh && sudo chmod +x /home/pi/installloadinggames.sh && sudo ./installloadinggames.sh
```

__License :__

<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/3.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/3.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/3.0/">Creative Commons Attribution-NonCommercial-ShareAlike 3.0 Unported License</a>.

__Copyright :__

RetroBox & StoneSet & Wabfall & Lefuturiste & Pizzacus

~ - ~

Site officiel : https://retrobox.tech
Official website : https://retrobox.tech
Made with ❤️ in France