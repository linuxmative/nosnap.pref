# nosnap.pref

To prevent repository packages from triggering the installation of snap, this file forbids snapd from being installed by APT.

## Download

### Use wget:

    sudo wget https://raw.githubusercontent.com/linuxmative/nosnap.pref/main/nosnap.pref -P /etc/apt/preferences.d

### Use curl:

    sudo curl -o /etc/apt/preferences.d/nosnap.pref https://raw.githubusercontent.com/linuxmative/nosnap.pref/main/nosnap.pref



