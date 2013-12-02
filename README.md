coreboot-reference
==================

redsec zone provides reference implementation of coreboot hardening guide in form of coreboot with SeaBIOS payload binary distribution for x86 QEMU (-M pc).

Current version does not support PXE.

Target QEMU build
=================

Currently the only officialy supported and tested underare QEMU Windows builds from: http://homepage3.nifty.com/takeda-toshiya/qemu/index.html

 * For x86 build 0.11.1 is currently used
 * For ARM build 0.13.1 is currently used

QEMU linux binaries are not being used currently however you can still use one and it should work.

Windows folder
==============

Windows folder contains example startup scripts for target QEMU build.
By default gdb server is being enabled so it allows connecting with IDA for debugging purposes for example.


