##How I pages

#... updated nanovna firmware

1) download latest firmware from here:
https://github.com/DiSlord/NanoVNA-D/releases
(.H not .H4)

put nano vna in dfu mode

connect to computer



use dfu-util like so..

dfu-util -a 0 -D NanoVNA.H.v1.2.00.dfu


man page detail here:
https://manpages.ubuntu.com/manpages/xenial/man1/dfu-util.1.html
