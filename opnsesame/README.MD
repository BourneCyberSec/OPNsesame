OPNsesame is a simple script to allow users to spoof their mac address.
Its main purpose is bypassing NAC and Capive portals



Aircrack suite will also need to be installed but is not covered by this script,
Presuming you are running some varient of Kali Linux it may be installed.
To install Aircrack uncomment each line in the installation script: install

Installation of script is easy:

chmod +x install
./install

You can run script form anywhere by typing OPNsesame

Within the tmux session you can filter out airodump scans for open networks by using:

airodump-ng --encrypt opn {interface}
