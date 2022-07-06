# freedos_bootstrap
Base image for bootstrapping a FreeDOS project.

QEMU used used to emulate the OS.  I'm using the PCNET network adapter.  You can find the drivers for that adapter [here](http://www.georgpotthast.de/sioux/packet.htm), but I already have them installed on the image for you.

QEMU mounts the /src directory from this archive into the emulator, which FreeDOS will read as the D: drive.  C:\FDAUTO.BAT will run D:\BUILD.BAT if the file exists.  From there it's up to you what you will do.
