bon10Asm
========

PIC16F84A assembly programs for [bon10 (Japanese)]( http://www.inrof.org/toro/bonten/index.html )

For OSX/Linux, use gpasm from gputils and pk2cmd (tarball: <http://ww1.microchip.com/downloads/en/DeviceDoc/pk2cmdv1.12.0LinuxMacSource.tar.gz>)


Compilation
========

    gpasm -p p16f84a foo.asm
    pk2cmd -PPIC16F84A -M -R -F foo.hex

DIP1 on to start.


avoidBlock
========

Avoid obstacles using IR LED.


backNForth
========

Only move back and forth.
