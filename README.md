# linuxcnc-ethercat
.DEB file for LinuxCNC EtherCAT HAL driver

# build deb file
install all dependencies<br>
sudo apt install dpkg-dev linuxcnc-uspace, ethercat-master and libethercat-dev<br>
dpkg-buildpackage -us -uc<br>

# Install from repositories
'''
curl -s https://packagecloud.io/install/repositories/rodw-au/rodw-au/script.deb.sh | sudo bash<br>
sudo apt-get install linuxcnc-ethercat=0.9.4<br>
'''  
