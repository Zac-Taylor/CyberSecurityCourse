## Week 9 Lab - Into The Packets

Milestone 1: Security-Flavored Net Tools

NCAT

![ncat](https://user-images.githubusercontent.com/5544526/40698469-0a419908-6384-11e8-8328-4603fedc903f.JPG)

NMAP

![nmap](https://user-images.githubusercontent.com/5544526/40698527-471ecb7a-6384-11e8-9468-f8bb45126469.JPG)

Challenge 1: Run nmap against your localhost IP to see all open ports

See how many of the ports you can match to services: 2 Ports are open 80: 5432

Challenge 1: Run nmap against your localhost IP to see all open ports

See how many of the ports you can match to services 8 ports are opened : 135 139 443 445 902 912 1433 2383

Milestone 2: Grabbing Packets with TCPdump

![tcpdump1](https://user-images.githubusercontent.com/5544526/40698645-e58c4b16-6384-11e8-87a2-084d0f75dfe5.JPG)

How many requests to load the main codepath.com page? 227 

What type of resource accounts for most of the requests?HTTP

![tcpdump2](https://user-images.githubusercontent.com/5544526/40698686-2415fa94-6385-11e8-982d-3cd5f32fb33b.JPG)

Now try the same exercise with https://security.codepath.com. What differences do you see in the output? What accounts for those differences?

Much less packets it took to load the page 

Milestone 3: Hello, Wireshark

![wireshark](https://user-images.githubusercontent.com/5544526/40698728-6a110cdc-6385-11e8-8229-1022f813b4f5.JPG)

Now for the rest of the rest of the MileStones I ran into a big problem. The problem is that I am living on camous and I am not allowed to sniff the traffic via LAN also for MileStone 5 -7 it requires to buy an externall WI-FI adapter
