# vusb-xmega
XMEGA port of V-USB

Enumerates OK, not extensively tested yet.

Requires a virtual port, GPIO01 and GPIO1. See main.c for hints. 16MHz clock required, RC oscillator probably isn't good enough so use a crystal (and maybe the PLL, untested).