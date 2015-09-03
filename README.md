# wifite-mod

Change list:
1. Change all [tshark] param -R to -Y
cuz: tshark: -R without -2 is deprecated. For single-pass filtering use -Y.
2. Disable config strip_handshake
cuz: so it can be valid by ESWA or WIFIPR
