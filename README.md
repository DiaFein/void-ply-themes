## Plymouth theme for Void Linux

* Install Plymouth via `xbps-install -S plymouth`.
* Download or clone this repo and move the extracted void-logo folder to the Plymouth themes folder located under `/usr/share/plymouth/themes`.
* Make sure the void-logo theme is enabled via `plymouth-set-default-theme --list`.
* Set the Plymouth theme to void-logo via `plymouth-set-default-theme -R void-logo`.
* Reboot and enjoy!

### CREDITS

Void-logo is an adaptation of the debian-logo and ubuntu-logo theme, all credits goes to Alberto Milone for the original coding.
