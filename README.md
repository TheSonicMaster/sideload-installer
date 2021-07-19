# sideload-installer
Command-line installer for mcpelauncher sideload versions, written in Python.
# Obtaining
```
curl -Os https://raw.githubusercontent.com/TheSonicMaster/sideload-installer/main/sideload-installer
chmod 755 sideload-installer
```
# Running locally
```
./sideload-installer
```
# Installing system-wide
```
sudo install -vDm755 sideload-installer /usr/local/bin/sideload-installer
```
After installing system-wide, you can run the installer simply with:
```
sideload-installer
```
# Uninstalling system-wide
```
sudo rm /usr/local/bin/sideload-installer
```
