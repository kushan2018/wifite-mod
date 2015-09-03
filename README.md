# wifite-mod

## Change log
https://github.com/derv82/wifite/issues/54

## Change list

#### Change all [tshark] param -R to -Y
cuz: tshark: -R without -2 is deprecated. For single-pass filtering use -Y.

####Disable config strip_handshake
cuz: so it can be valid by ESWA or WIFIPR
