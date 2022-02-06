
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
Fedora:
```
yum install lsb
```
openSUSE:
```
yast --install lsb
```

>check your Architecture of your system
```
dpkg --print-architecture
```
After that install `printer utility` of specified printer`.
>If the printer is not installed after installing the printer utility driver, please install `ESC / P`, short for Epson Standard Code for Printers.
>Then go to settings check list printer drivers if you find your printer **Congratulations!!!**

**CANON PRINTER DRIVERS**
- [install canon Drivers](https://in.canon/en/support/)

**Brother Printer**

- [INSTALL Brother DriverS](https://support.brother.com/g/b/productsearch.aspx?c=in&lang=en)

**HPLIP Driver Installation Process**
1.First, download the latest HPLIP(HP Linux Imaging and Printing) driver from [website](https://developers.hp.com/hp-linux-imaging-and-printing/gethplip)
2.Secondly: after downloading the file it needs to be made executable. To do this, the following needs to be done:
>Open a terminal
Browse to the Downloads folder: `cd Downloads`

>
Then type the following command: `sudo chmod +x hplip-*.**.**.run`(*.**.** is where the version number of the file needs to be filed in)

>Press Enter and if required, type the user password and press Enter

>The HPLIP driver is now executable. Keep the terminal open.

>**Do not switch on the printer during the installation procedure!!! If the printer is switched on, make sure it is switched off before starting the installation procedure.**















**Common printer & Scanner issues**

**Brothr HL-L5100DN**
- Reset process
1. Make sure the machine is turned on.
2. Simultaneously Press “Secure” and “Cancel”
3. Select TNSTD
4. RESET^

**HP A3 PRINTER**

PRINT SETUP------>SELECT TRAY1------>A4LEF

PRINT SETUP------>SELECT TRAY2------>A4LEF






