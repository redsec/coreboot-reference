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

Windows folder contains example startup scripts for target QEMU build. Some scripts enable gdb server in QEMU for debugging purposes so you can use IDA to debug it. When using IDA with QEMU remember to enable gdb server for IPv4 since IDA can't use IPv6 to connect. 

When running QEMU with provided scripts you need linux.img disk image file. By default we are using imiges available at: http://wiki.qemu.org/Testing

