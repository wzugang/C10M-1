C10M
====

The project purpose is to test some packet filtering method that can handle 
10Mp/s (10 000 000 packet per second) on a standard userland linux.

Of course, many thx to http://c10m.robertgraham.com/p/manifesto.html

Linux Appliance : not done 
==========================

Boot a linux with only 2 core for linux and 4 others for specifics threads
that will handle the program


Linux Kernel patch PF_RING : not done
=====================================

Start the linux kernel on the appliance with the PF_RING_ZC patch :

http://www.ntop.org/products/pf_ring/pf_ring-zc-zero-copy/

Which is really easy (just a modeprobe) :-)

Program that use PF_RING_ZC to count SRT and CRT : not done 
===========================================================

This program (which will really be in this repository) as to calculate the 
server (SRT)  and client (CRT) response time during the TCP handshake
