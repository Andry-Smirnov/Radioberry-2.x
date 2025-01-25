# Radioberry software installation script

This is a stable release of versions of the Radioberry sofware.

Initialy it was a script where you could select the individual software components.

Nowadays people have to choose too much...hi, the whole software stack will be installed.

https://github.com/pa3gsb/Radioberry-2.x/wiki/Radioberry-Software-stack

This avoids possible problems by selecting the wrong set of software components.

Installation is easy.

Open a command window and executing the following commands:

```sh
cd /tmp
wget https://raw.githubusercontent.com/pa3gsb/Radioberry-2.x/master/SBC/rpi-4/releases/stable/radioberry_install.sh
sudo chmod +x radioberry_install.sh
./radioberry_install.sh
```

Installation of `SOAPY`:

```sh
cd /tmp
wget https://raw.githubusercontent.com/pa3gsb/Radioberry-2.x/master/SBC/rpi-4/releases/stable/soapy_install.sh
sudo chmod +x soapy_install.sh
./soapy_install.sh
```
