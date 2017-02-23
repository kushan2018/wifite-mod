# wifite-mod

## Notice

*Plz pay a attension on new version*
https://github.com/darkr4y/wifite2plus


## Change log
https://github.com/derv82/wifite/issues/54

## Change list

#### Change all [tshark] param -R to -Y
cuz: tshark: -R without -2 is deprecated. For single-pass filtering use -Y.

####Disable config strip_handshake
cuz: so it can be valid by ESWA or WIFIPR


## Best Practices

1. Only test on Kali Linux
2. cd /opt && git clone https://github.com/darkr4y/wifite-mod/
3. ln -s /opt/wifite-mod/wifite.py /usr/local/bin/wifite && chmox +x /usr/local/bin/wifite
4. cd /opt && git clone https://github.com/gabrielrcouto/reaver-wps
5. cd /opt/reaver-wps/src && ./configure ; make ; make install
6. restart the Terminal check the bin path
7. Now lets fucking WIFI protection
