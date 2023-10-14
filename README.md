hping3 -S 203.109.232.21
HPING 203.109.232.21 (eth0 203.109.232.21): S set, 40 headers + 0 data bytes
ICMP Network Unreachable from ip=10.0.2.2 name=UNKNOWN   
ICMP Network Unreachable from ip=10.0.2.2 name=UNKNOWN   
ICMP Network Unreachable from ip=10.0.2.2 name=UNKNOWN   
^C
--- 203.109.232.21 hping statistic ---
13 packets transmitted, 13 packets received, 0% packet loss
round-trip min/avg/max = 0.0/0.0/0.0ms 

—-------------------------------------------------------------------------------------------------------------------------


hping3 -A 203.109.232.21
HPING 203.109.232.21 (eth0 203.109.232.21): A set, 40 headers + 0 data bytes
len=46 ip=203.109.232.21 ttl=255 id=32 sport=0 flags=R seq=0 win=0 rtt=8.6 ms
len=46 ip=203.109.232.21 ttl=255 id=33 sport=0 flags=R seq=1 win=0 rtt=10.7 ms
len=46 ip=203.109.232.21 ttl=255 id=34 sport=0 flags=R seq=2 win=0 rtt=8.4 ms
len=46 ip=203.109.232.21 ttl=255 id=35 sport=0 flags=R seq=3 win=0 rtt=5.9 ms
len=46 ip=203.109.232.21 ttl=255 id=36 sport=0 flags=R seq=4 win=0 rtt=11.8 ms
len=46 ip=203.109.232.21 ttl=255 id=37 sport=0 flags=R seq=5 win=0 rtt=5.4 ms
len=46 ip=203.109.232.21 ttl=255 id=38 sport=0 flags=R seq=6 win=0 rtt=4.8 ms
len=46 ip=203.109.232.21 ttl=255 id=39 sport=0 flags=R seq=7 win=0 rtt=34.0 ms
len=46 ip=203.109.232.21 ttl=255 id=40 sport=0 flags=R seq=8 win=0 rtt=12.0 ms
len=46 ip=203.109.232.21 ttl=255 id=41 sport=0 flags=R seq=9 win=0 rtt=17.6 ms
len=46 ip=203.109.232.21 ttl=255 id=42 sport=0 flags=R seq=10 win=0 rtt=9.1 ms
len=46 ip=203.109.232.21 ttl=255 id=43 sport=0 flags=R seq=11 win=0 rtt=16.4 ms
^C
--- 203.109.232.21 hping statistic ---
15 packets transmitted, 15 packets received, 0% packet loss
round-trip min/avg/max = 2.0/11.7/34.0 ms


—----------------------------------------------------------------------------------------------------------------------------
hping3 -P 203.109.232.21
HPING 203.109.232.21 (eth0 203.109.232.21): P set, 40 headers + 0 data bytes
len=46 ip=203.109.232.21 ttl=255 id=54 sport=0 flags=RA seq=0 win=0 rtt=7.8 ms
len=46 ip=203.109.232.21 ttl=255 id=55 sport=0 flags=RA seq=1 win=0 rtt=9.9 ms
len=46 ip=203.109.232.21 ttl=255 id=56 sport=0 flags=RA seq=2 win=0 rtt=8.7 ms
len=46 ip=203.109.232.21 ttl=255 id=57 sport=0 flags=RA seq=3 win=0 rtt=9.9 ms
len=46 ip=203.109.232.21 ttl=255 id=58 sport=0 flags=RA seq=4 win=0 rtt=10.5 ms
len=46 ip=203.109.232.21 ttl=255 id=59 sport=0 flags=RA seq=5 win=0 rtt=5.6 ms
len=46 ip=203.109.232.21 ttl=255 id=60 sport=0 flags=RA seq=6 win=0 rtt=7.1 ms
len=46 ip=203.109.232.21 ttl=255 id=61 sport=0 flags=RA seq=7 win=0 rtt=1.3 ms
len=46 ip=203.109.232.21 ttl=255 id=62 sport=0 flags=RA seq=8 win=0 rtt=9.6 ms
len=46 ip=203.109.232.21 ttl=255 id=63 sport=0 flags=RA seq=9 win=0 rtt=11.2 ms
len=46 ip=203.109.232.21 ttl=255 id=64 sport=0 flags=RA seq=10 win=0 rtt=10.6 ms
len=46 ip=203.109.232.21 ttl=255 id=65 sport=0 flags=RA seq=11 win=0 rtt=1.7 ms
len=46 ip=203.109.232.21 ttl=255 id=66 sport=0 flags=RA seq=12 win=0 rtt=12.1 ms
len=46 ip=203.109.232.21 ttl=255 id=67 sport=0 flags=RA seq=13 win=0 rtt=6.3 ms
len=46 ip=203.109.232.21 ttl=255 id=68 sport=0 flags=RA seq=14 win=0 rtt=8.1 ms
len=46 ip=203.109.232.21 ttl=255 id=69 sport=0 flags=RA seq=15 win=0 rtt=1.9 ms
len=46 ip=203.109.232.21 ttl=255 id=70 sport=0 flags=RA seq=16 win=0 rtt=10.4 ms
len=46 ip=203.109.232.21 ttl=255 id=71 sport=0 flags=RA seq=17 win=0 rtt=7.0 ms
len=46 ip=203.109.232.21 ttl=255 id=72 sport=0 flags=RA seq=18 win=0 rtt=5.6 ms
^C
--- 203.109.232.21 hping statistic ---
19 packets transmitted, 19 packets received, 0% packet loss
round-trip min/avg/max = 1.3/7.6/12.1 ms

—----------------------------------------------------------------------------------------------------------------------------
Cant understand below command -c and destination in wireshark
hping3 10  -c 203.109.232.21
HPING 10 (eth0 0.0.0.10): NO FLAGS are set, 40 headers + 0 data bytes
len=46 ip=0.0.0.10 ttl=255 id=84 sport=0 flags=RA seq=0 win=0 rtt=2.6 ms
len=46 ip=0.0.0.10 ttl=255 id=85 sport=0 flags=RA seq=1 win=0 rtt=15.0 ms
len=46 ip=0.0.0.10 ttl=255 id=86 sport=0 flags=RA seq=2 win=0 rtt=16.3 ms
len=46 ip=0.0.0.10 ttl=255 id=87 sport=0 flags=RA seq=3 win=0 rtt=10.7 ms
len=46 ip=0.0.0.10 ttl=255 id=88 sport=0 flags=RA seq=4 win=0 rtt=7.6 ms
len=46 ip=0.0.0.10 ttl=255 id=89 sport=0 flags=RA seq=5 win=0 rtt=5.2 ms
len=46 ip=0.0.0.10 ttl=255 id=90 sport=0 flags=RA seq=6 win=0 rtt=24.3 ms
len=46 ip=0.0.0.10 ttl=255 id=91 sport=0 flags=RA seq=7 win=0 rtt=15.6 ms
len=46 ip=0.0.0.10 ttl=255 id=92 sport=0 flags=RA seq=8 win=0 rtt=12.5 ms
^C
--- 10 hping statistic ---
9 packets transmitted, 9 packets received, 0% packet loss
round-trip min/avg/max = 2.6/12.2/24.3 ms

—----------------------------------------------------------------------------------------------------------------------------
To find version
hping3   -v 203.109.232.21 
hping3 version 3.0.0-alpha-2 ($Id: release.h,v 1.4 2004/04/09 23:38:56 antirez Exp $)
This binary is TCL scripting capable
—----------------------------------------------------------------------------------------------------------------------------







