# Lampone Pi

Lampone Pi is a live Debian arm64 port for the Raspberry Pi.

**For experts**

How to build the live image: https://github.com/marco-buratto/lamponepi.live-build

How write the live image file onto a SD card so that it's compliant to be booted by a Raspberry Pi: https://github.com/marco-buratto/lamponepi.installer

**Quite for everyone**

A "qemu box" can be setup in order to simplify the build infrastructure; a Vagrant procedure automates the installation of a VirtualBox environment (Debian Buster x86_64) in which a qemu installation of Debian Buster arm64 is present. The qemu box will be used to *build a live image of Debian Buster for arm64* and then *write the image* to a SD card in a way it is compatible with a Raspberry Pi.

See https://github.com/marco-buratto/lamponepi.qemubox
