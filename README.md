bon10Asm
========

PIC16F84A assembly programs for [bon10 (Japanese)]( http://www.inrof.org/toro/bonten/index.html )

For OSX/Linux, use gpasm from gputils and pk2cmd (tarball: <http://ww1.microchip.com/downloads/en/DeviceDoc/pk2cmdv1.12.0LinuxMacSource.tar.gz>)


Compilation
========

avoidBlock
--------

    gpasm -p p16f84a avoidBlock.asm
    pk2cmd -PPIC16F84A -F avoidBlock.hex -M -R

DIP1 on to start.
