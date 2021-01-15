Flycast
===========
Flycast is a multi-platform Sega Dreamcast emulator.

Disclaimer
==========
All code contritbuted to this fork is *not* bound by the Individual Contributor License Agreement of the upstream repository (https://github.com/reicast/reicast-emulator) and shall *not* be considered as a contribution to the upstream repository.

Compile instructions in Ubuntu for Retroarch (64 bit)
=====================================================
`git clone https://github.com/christianhaitian/flycast.git` \
`cd flycast` \
`make clean` \
`make platform=goadvance V=1 VERBOSE=1 -j$(nproc)`
