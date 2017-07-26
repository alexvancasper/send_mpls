This example of how to send RAW ethernet frame via RAW socket.

tcpdump -i eth0 -tttnee "ether host 00:11:22:33:44:55"
...
00:00:02.258305 52:54:00:91:74:00 > 00:11:22:33:44:55, ethertype MPLS unicast (0x8847), length 18: MPLS (label 1, exp 0, [S], ttl 255)
