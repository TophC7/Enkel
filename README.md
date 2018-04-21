# lighdm-webikit-theme-Enkel
Lightdm Webkit2 greeter theme I edited
Derived from:
- https://github.com/nomad23541/lightdm-webkit-simply-theme.git

# Screenshot
![alt text]()

# How to Install:
  1. Install LightDM `sudo apt-get install lighdm`
  2. [Install Webkit2-greeter](https://software.opensuse.org/download.html?project=home:antergos&package=lightdm-webkit2-greeter "webkit2-greeter")
  3. Set Webkit2 as your lightdm engine: `sudo nano /etc/lightdm/lightdm.conf` Then set`[LightDM] greeter-session = lightdm-webkit2-greeter`
  4. Select lighdm as your display manger: `sudo dpkg-reconfigure lightdm`
  5. Copy this repository to `cd /usr/share/lightdm-webkit/themes` using `sudo git clone REPOSITORIES_URL`
  6. Change Webkit2-Greeter theme to Enkel: `sudo nano /etc/lightdm/lightdm-webkit2-greeter.conf` Then set `[greeter]
  webkit-theme = Enkel`
  7. And done you should have your theme ready

# #
To change wallpaper chage `the background.jpg` file
