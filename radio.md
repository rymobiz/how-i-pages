## How I pages

# ... updated nanovna firmware

1) download latest firmware from here:
https://github.com/DiSlord/NanoVNA-D/releases
(.H not .H4)

put nano vna in dfu mode

connect to computer



use dfu-util like so..

dfu-util -a 0 -D NanoVNA.H.v1.2.00.dfu


man page detail here:
https://manpages.ubuntu.com/manpages/xenial/man1/dfu-util.1.html

# wsjt-x

1. set time synch with ntp:

https://www.maketecheasier.com/sync-linux-time-with-ntp-server/


2. open serial device ttyUSB0

https://askubuntu.com/questions/112568/how-do-i-allow-a-non-default-user-to-use-serial-device-ttyusb0

(i used this one KERNEL=="ttyUSB[0-9]*",NAME="tts/USB%n",SYMLINK+="%k",GROUP="uucp",MODE="0666")


3. enable/disable flow control on a USB

https://forums.raspberrypi.com/viewtopic.php?t=265273

https://www.linux-magazine.com/Issues/2016/182/Ethtool

arecord -l

dmesg

how to listen to ft8 on hackrf one

https://www.youtube.com/watch?v=ovPrc2KVFJw


