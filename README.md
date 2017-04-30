# poovpn
Script for make point to point VPN tunnel with tun device over ssl or ssh

Examples
---------------------

`./poorvpn -P 22 -t vpn0 -s start root@my.server`
Will start a VPN with socat over ssh

`./poorvpn -P 22 -t vpn0 -S start root@my.server`
Will start a VPN with pppd over ssh

`./poorvpn -p 9989 -P 22 -t vpn0 -S start my.server`
Will start a VPN with socat over ssl (DTLS1) on port 9989
