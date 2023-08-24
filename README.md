# linuxcnc-ethercat
.DEB file for LinuxCNC EtherCAT HAL driver

# build deb file
install all dependencies including
sudo apt install dpkg-dev linuxcnc-uspace, ethercat-master and libethercat-dev
dpkg-buildpackage -us -uc

# Install from repositories
'''
curl -s https://packagecloud.io/install/repositories/rodw-au/rodw-au/script.deb.sh | sudo bash
sudo apt-get install linuxcnc-ethercat=0.9.4
'''  
