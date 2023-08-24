# linuxcnc-ethercat
.DEB file for LinuxCNC EtherCAT HAL driver<br>

# build deb file
git clone https://github.com/rodw-au/linuxcnc-ethercat<br>
git checkout adapt_debian<br>
install all dependencies (linuxcnc and libethercat must be installed<br>
sudo apt install dpkg-dev linuxcnc-uspace, ethercat-master and libethercat-dev<br>
dpkg-buildpackage -us -uc<br>

# Install from repositories
```
curl -s https://packagecloud.io/install/repositories/rodw-au/rodw-au/script.deb.sh | sudo bash
sudo apt-get install linuxcnc-ethercat=0.9.4
``` 
