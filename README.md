# pijarr-setup.sh
Simple automated setup and configuration of Jackett, Sonarr, Lidarr and Radarr on Raspberry Pi Raspbian OS

[ Tested January 2020 Raspberry Pi 3 Raspbian Buster ]

Version of packages used are at the top of the script with the exception of Sonarr which will get the latest version for Linux.The initial required foundation packages such and Mono (Cross platform, open source .NET framework) may take a while to download and install.

With minor modification the script would likely work for other Debian or Ubuntu linux systems. To do this some sources may need to be changed as the the LinuxARM32 version is currently used for Jackett.

# Usage
**Method 1:** Clone and run locally. You can edit and modify script to suit using this method.

`git clone https://github.com/piscripts/pijarr.git`

`sudo bash pijarr/pijarr-setup.sh`

**Method 2:** Just use the curl or wget command lines shown below for a one-step install.

`sudo bash -c "$(curl -fsSL https://raw.githubusercontent.com/piscripts/pijarr/master/pijarr-setup.sh)"`

`sudo bash -c "$(wget -O- https://raw.githubusercontent.com/piscripts/pijarr/master/pijarr-setup.sh)"`
