**Brothr HL-L5100DN**
- Reset process
1. Make sure the machine is turned on.
2. Simultaneously Press “Secure” and “Cancel”
3. Select TNSTD
4. RESET^

**HP A3 PRINTER**

PRINT SETUP------>SELECT TRAY1------>A4LEF

PRINT SETUP------>SELECT TRAY2------>A4LEF

**KODAK i2620 Scanner**

- [i2620Scanner ubuntu16.04 32bit](https://resources.kodakalaris.com/docimaging/drivers/LinuxSoftware_i2000_v4.14.i586.deb.tar.gz)
- [i2620Scanner Ubuntu16.04 64bit](https://resources.kodakalaris.com/docimaging/drivers/LinuxSoftware_i2000_v4.14.x86_64.deb.tar.gz)

"Expand the file (e.g., tar -xf *.gz) and then run the setup script (i.e. sudo ./setup)"

-[i2620Scanner Ubuntu18.04 64bit](https://resources.kodakalaris.com/docimaging/drivers/LinuxSoftware_i2000_v4.14.x86_64.deb.tar.gz)
<p>the following command must be entered in a terminal window:</p>

```
sudo ln -sfr /usr/lib/sane/libsane-kds* /usr/lib/x86_64-linux-gnu/sane

```

**EPSON Printer Driver**
- [Download Epson drivers and Software](http://download.ebz.epson.net/dsc/search/01/search/?OSC=LX)


>[Notice]
In order to install these drivers, you need to install LSB package (version 3.2 or later) beforehand.

Ubuntu:
```
sudo apt-get install lsb
```
After that install `printer utility` of specified printer and Download Printer Driver  ESC/P Driver (full feature).

Fedora: # yum install lsb
openSUSE: # yast --install lsb

```





