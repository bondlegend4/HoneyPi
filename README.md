# HoneyPot
A honey pot raspberry pi. That has a web server running but the OpenCanary checks typical web server ports and web server runs on another random port.
This'll be a full tutorial after booting up your raspberry pi to the end.


# Remote Setup
This is how you can connect your Macbook to your raspberry pi. This is an optional step in case you want a remote GUI.
  https://youtu.be/YP3_gvHZhfw

```linux
sudo raspi-config
```
* Then on RaspberryPi 4 the controls are different so you can follow the video or:
 * Scroll Down to "3 Interface Option"
 * Click Enter
  Scroll Down to "P2 SSH"
  Click Enter and Click YES to Enable
  Get to Interface Option
  Scroll Down to "P3 VNC"
  Click Enter and Click YES to Enable

And reboot

```linux
reboot
```

Then Setup the VNC Server (If you do not switch to VNC PAssword it will not work AND make sure to be on the same network as the Pi)
  Right click on the menu
  Click options
  Close the Pop-up
  Switch Encryption tp prefer off
  Ensure Authentication uses VNC password
  Go to Users & Permissions
  Double Click the Standard user
  Set the password

Connect from Mac
  Open Screen Sharing
  Type the IP Address of your RapsberryPi which can be found using
```linux
ifconfig
```

# openCanary


# Web Server
