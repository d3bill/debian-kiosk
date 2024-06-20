Kiosk installer for Debian based Linux distros

Small installer script to setup a minimal kiosk with Chromium for Debian based Linux distros. This installer is heavily based on the excellent instructions by Will Haley 
and modified script https://raw.githubusercontent.com/josfaber/debian-kiosk-installer/master/kiosk-installer.sh
Usage

Setup a minimal Debian netinstall

Login as root or with root permissions (sudo su)

Download this installer, make it executable and run it

wget https://github.com/d3bill/debian-kiosk/blob/main/debian-kiosk-installer.sh; chmod +x debian-kiosk-installer.sh; ./debian-kiosk-installer.sh


What will it do?

It will create a normal user kiosk, install software (check the script) and setup configs (it will backup existing) so that on reboot the kiosk user will login automaticaly and run chromium in kiosk mode with one url. It will also hide the mouse.
Change the url


