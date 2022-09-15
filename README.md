SecureCRT/SecureFX Bundle Flatpak
=================================
The files in here allow you to convert the Ubuntu 20.04 LTS build of SecureCRT/SecureFX bundle into a flatpak.

To build
========
You must have the scrt-sfx-9.2.3.2829.ubuntu20-64.tar.gz file in the directory this file is in. As we cannot
redistribute SecureCRT or SecureFX, you must provide the binaries yourself. This just puts the correct Ubuntu
dependencies in /app/lib and put files where they belong

Just build like you would any other flatpak

Some bugs
=========
At the moment, the History tab in the About Box and help do not work as they are hardcoded in /usr/share. 
I beleve also other languages dont work as well due to the same /usr/share hardcoding.
