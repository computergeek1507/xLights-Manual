# Linux

## Downloading xLights

The latest release of xLights for Ubuntu Linux can be found at the following link: [https://code.launchpad.net/~chris-debenham/+archive/ubuntu/xlights](https://code.launchpad.net/~chris-debenham/+archive/ubuntu/xlights).  For other Linux distributions, an AppImage executable is available at: [https://www.adebenham.com/xlights-linux/](https://www.adebenham.com/xlights-linux/). You can also download the source from [https://github.com/smeighan/xLights](https://github.com/smeighan/xLights) and compile as per the included README.linux file.\(not recommended\)

## Installing xLights

#### PPA Option

1. Add the xLights package archive by running "sudo add-apt-repository ppa:chris-debenham/xlights" in a terminal window.
2. Update the list of available packages and then install xlights by then running "sudo apt-get update"  and "sudo apt-get install xlights".
3. To enable automatic timing markers you will need to install the Queen Mary Vamp plugins. They can be downloaded from [http://isophonics.net/QMVampPlugins](http://isophonics.net/QMVampPlugins). Once downloaded extract the plugins and copy the files qm-vamp-plugins.so, [qm-vamp-plugins.cat](http://qm-vamp-plugins.cat/) and qm-vamp-plugins.n3 to either $HOME/vamp/ or /usr/lib/vamp/

#### AppImage Builds

1. Download the latest "xLights-xxxx.xx.glibc2.17-x86\_64.AppImage" file from: [https://www.adebenham.com/xlights-linux/](https://www.adebenham.com/xlights-linux/)
2. Set the AppImage file as an executable \(for example ‘chmod +x ./xLights-xxxx.xx.glibc2.17-x86\_64.AppImage’\) and then run the file directly.

