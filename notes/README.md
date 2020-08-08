# Table of Contents



# Introduction

1. [Introduction](./introduction/README.md#intro-intro)
2. [Introducing TCP/IP 5-layer model](./introduction/README.md#5-layer-intro)
   1. [Physical Layer](./introduction/README.md#physical-layer)
   2. [Data link layer](./introduction/README.md#data_link_layer)
   3. [Network Layer](./introduction/README.md#network_layer)
   4. [Transport Layer](./introduction/README.md#transport_layer)
   5. [Application Layer](./introduction/README.md#application_layer)
   6. [OSI model](./introduction/README.md#osi)
3. [The Basics of networking devices](./introduction/README.md#basics)
   1. [Cables](./introduction/README.md#cables)
   2. [Network Devices](./introduction/README.md#network_devices)
      1. [Hub](./introduction/README.md#hub)
      2. [Network Switch](./introduction/README.md#network_switch)
      3. [Routers](./introduction/README.md#routers)
      4. [Sever and clients](./introduction/README.md#client_n_server)
4. [OSI model](./introduction/README.md#osi)



# Physical Layer

1. [Moving bits across a wire](./physical-layer/README.md#moving_bits)
2. [Twisted pair-cabling and duplexing](./physical-layer/README.md#duplexing)
3. [Network Ports and Patch Panels](./physical-layer/README.md#network_ports)
   1. [RJ45 plug](./physical-layer/README.md#rj45)
   2. [RJ45 port](./physical-layer/README.md#rj45_port)
   3. [Patch Panel](./physical-layer/README.md#patch_panel)



# Data-link layer

1. [Ethernet and MAC addresses](./data-link-layer/README.md#ethernet_MAC)
   1. [OUI](./data-link-layer/README.md#oui)
2. [Unicast, Multicast, Broadcast](./data-link-layer/README.md#cast)
3. [Dissecting an ethernet frame](./data-link-layer/README.md#dissecting_ethernet_frame)
   1. [preamble](./data-link-layer/README.md#preamble)
   2. [destination address](./data-link-layer/README.md#dest_add)
   3. [source address](./data-link-layer/README.md#source_add)
   4. [vlan tag/header](./data-link-layer/README.md#vlan_tag)
   5. [Ether type field](./data-link-layer/README.md#ether_type_field)
   6. [Payload](./data-link-layer/README.md#payload)
   7. [FCS](./data-link-layer/README.md#fcs)



# Network-layer

1. [IP-address : Introduction](./network-layer/README.md#ip-intro)
2. [IP datagrams](./network-layer/README.md#ipdatagrams)
3. [IP addresses](./network-layer/README.md#ip_addresses)
4. [Address Resolution Protocol](./network-layer/README.md#arp)
5. [Subnetting](./network-layer/README.md#subnetting-intro)
   1. [Subnetting](./network-layer/README.md#subnetting)
   2. [Subnet Masks](./network-layer/README.md#subnet_masks)
   3. [CIDR](./network-layer/README.md#cidr)
6. [Routing](./network-layer/README.md#routing)
   1. [Basic routing concepts](./network-layer/README.md#routing-concepts)
   2. [Routing Tables](./network-layer/README.md#routing-table)
   3. [Interior gateway protocols](./network-layer/README.md#igp)
   4. [Exterior gateway protocols](./network-layer/README.md#egp)



# Transport-layer

1. [Introduction](./transport-layer/README.md#intro)
2. [Dssection of a TCP segment](./transport-layer/README.md#dissecting-TCP-segment)
   1. [Source port](./transport-layer/README.md#source-port)
   2. [Destination port](./transport-layer/README.md#dest-port)
   3. [Sequence number](./transport-layer/README.md#sn)
   4. [Acknowledgement number](./transport-layer/README.md#an)
   5. [Data offset field](./transport-layer/README.md#offset)
   6. [Control flags](./transport-layer/README.md#control)
   7. [TCP window](./transport-layer/README.md#window)
   8. [TCP checksum](./transport-layer/README.md#checksum)
   9. [Urgent](./transport-layer/README.md#urgent)
   10. [Options](./transport-layer/README.md#options)
3. [TCP control flags](./transport-layer/README.md#control-flags)
   1. [3 way handshake](./transport-layer/README.md#3-way-handshake)
   2. [4 way hanshake](./transport-layer/README.md#4-way)
4. [TCP socket states](./transport-layer/README.md#socket-states)
5. [Connection oriented protocols](./transport-layer/README.md#cop)
6. [Connection-less protocols](./transport-layer/README.md#clp)
7. [Firewalls](./transport-layer/README.md#firewalls)



# Application-layer

1. [Introduction](./application-layer/README.md#intro)
2. [OSI model](./application-layer/README.md#osi)
3. [All layers together](./application-layer/README.md#all-layers)



# Network-services

1. [Name resolution](./network-services/README.md#name-resolution)
   1. [Why DNS?](./network-services/README.md#dns)
   2. [The many steps of name resolution](./network-services/README.md#name-resolution-steps)
   3. [DNS and UDP](./network-services/README.md#dns-udp)
2. [Name Resolution in Practice](./network-services/README.md#name-resolution-in-practice)
   1. [Resource record types](./network-services/README.md#rrt)
      1. [A-record](./network-services/README.md#a-record)
      2. [quad-A record type](./network-services/README.md#aaaa)
      3. [CNAME record](./network-services/README.md#cname)
      4. [MX record](./network-services/README.md#mx)
      5. [SRV record](./network-services/README.md#srv)
      6. [TXT record](./network-services/README.md#txt)
      7. [PTR record](./network-services/README.md#ptr)
   2. [Anatomy of a domain name](./network-services/README.md#domain-name-anatomy)
   3. [DNS zones](./network-services/README.md#dns-zones)
3. DHCP
   1. [Overview](./network-services/README.md#DHCP)
      1. [DHCP-dynamic allocation](./network-services/README.md#dhcp-da)
      2. [DHCP-automatic allocation](./network-services/README.md#dhcp-aa)
      3. [DHCP- Fixed allocation](./network-services/README.md#dhcp-fa)
   2. [DHCP working](./network-services/README.md#dhcp-steps)
4. [Network Address Translation](./network-services/README.md#nat)
   1. [Basics of NAT](./network-services/README.md#nat-basics)
   2. [NAT and transport layer](./network-services/README.md#nat-tl)
   3. [NAT, non-routable spaces and limits of IPv4](./network-services/README.md#nat-limits)
5. [VPNs and Proxies](./network-services/README.md#vpns-proxies)
   1. [Virtual Private Networks](./network-services/README.md#vpn)
   2. [Proxy services](./network-services/README.md#proxy)
      1. [Web-Proxies](./network-services/README.md#web-proxy)
      2. [Reverse proxy](./network-services/README.md#rev-proxy)



# Connecting to the internet

1. [POTS and Dial up](./connecting-to-internet/README.md#pots)
   1. [Dial-up, Modems and Point-to-Point Protocols](./connecting-to-internet/README.md#modems)
2. [Broadband](./connecting-to-internet/README.md#broadband)
   1. [T-carrier technologies](./connecting-to-internet/README.md#t-carrier)
   2. [Digital Subscriber lines](./connecting-to-internet/README.md#dsl)
   3. [Cable broadband](./connecting-to-internet/README.md#cable-broadband)
   4. [Fiber connections](./connecting-to-internet/README.md#fiber)
      1. [FTTX](./connecting-to-internet/README.md#fttx)
      2. [FTTN](./connecting-to-internet/README.md#fttn)
      3. [FTTB](./connecting-to-internet/README.md#fttb)
      4. [FTTH](./connecting-to-internet/README.md#ftth)
3. [WAN](./connecting-to-internet/README.md#wan)
   1. [WAN technologies](./connecting-to-internet/README.md#wan-tech)
   2. [Point to point VPN](./connecting-to-internet/README.md#ppvpn)
4. [Wireless networking](./connecting-to-internet/README.md#wn)
   1. [802.11 frame](./connecting-to-internet/README.md#802.11frame)
   2. [Wireless network config](./connecting-to-internet/README.md#wnc)
      1. [Ad-hoc nets](./connecting-to-internet/README.md#adhoc)
      2. [WLANs](./connecting-to-internet/README.md#wlan)
      3. [Mesh nets](./connecting-to-internet/README.md#mesh)
   3. [Wireless Channels](./connecting-to-internet/README.md#wc)
   4. [Wireless Security](./connecting-to-internet/README.md#ws)
      1. [WEP](./connecting-to-internet/README.md#wep)
      2. [WPA](./connecting-to-internet/README.md#wpa)
      3. [WPA2](./connecting-to-internet/README.md#wpa2)
      4. [MAC Filtering](./connecting-to-internet/README.md#mac-filtering)
   5. [Cellular networking](./connecting-to-internet/README.md#cell)



# Troubleshooting network

1. [Introduction](./troubleshooting-and-future-of-net/README.md#intro)
2. [Verifying connectivity](./troubleshooting-and-future-of-net/README.md#vc)
   1. [Ping : Internet Message control Protocol](./troubleshooting-and-future-of-net/README.md#ping-icmp)
      1. [ICMP packet](./troubleshooting-and-future-of-net/README.md#icmp packet)
         1. [Type](./troubleshooting-and-future-of-net/README.md#icmp-type)
         2. [Code](./troubleshooting-and-future-of-net/README.md#icmp-code)
         3. [Checksum](./troubleshooting-and-future-of-net/README.md#icmp-checksum)
         4. [Rest of the header](./troubleshooting-and-future-of-net/README.md#icmp-rest)
         5. [Data payload](./troubleshooting-and-future-of-net/README.md#icmp-payload)
      2. [Ping](./troubleshooting-and-future-of-net/README.md#ping)
   2. [Traceroute](./troubleshooting-and-future-of-net/README.md#traceroute)
   3. [Testing Port Community](./troubleshooting-and-future-of-net/README.md#tpc)
3. [Digging into DNS](./troubleshooting-and-future-of-net/README.md#digging)
   1. [Name Resolution Tools](./troubleshooting-and-future-of-net/README.md#nrt)
   2. [Public DNS servers](./troubleshooting-and-future-of-net/README.md#pds)
   3. [DNS registration and expiration](./troubleshooting-and-future-of-net/README.md#dre)
   4. [Host Files](./troubleshooting-and-future-of-net/README.md#hf)
4. [The cloud](./troubleshooting-and-future-of-net/README.md#cloud)
   1. [Introduction](./troubleshooting-and-future-of-net/README.md#cloud-intro)
   2. [Private cloud](./troubleshooting-and-future-of-net/README.md#private-cloud)
   3. [Hybrid Cloud](./troubleshooting-and-future-of-net/README.md#hybrid-cloud)
5. [IPv6](./troubleshooting-and-future-of-net/README.md#ipv6)
   1. [IPv6 addressing and subnetting](./troubleshooting-and-future-of-net/README.md#ipv6-subnetting)
   2. [IPv6-datagram headers](./troubleshooting-and-future-of-net/README.md#ipv6-header)
   3. [IPv4 and IPv6 harmony](./troubleshooting-and-future-of-net/README.md#ip-harmony)