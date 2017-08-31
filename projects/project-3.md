---
layout: project
type: project
image: images/cotton-square.png
title: Network Simulator
permalink: projects/networkSimulator
date: 2017
labels:
  - C
  - GitHub
  - Pipes
  - Sockets
summary: Final project for an algorithms computer engineering class which we implemented a network using pipes and sockets.
---

<img class="ui image" src="{{ site.baseurl }}/images/network_topology.jpg">

The network simulator is a program that can be run and downloaded onto any computer. Using a configuration file the user is able to select how many host nodes or computers are on its network. This network is implemented through pipes and a switch. The computers are not directly connected to each other and all traffic is managed by the switch and its port table. Another user running the program on another computer can set up a completely different network with a different configuration file. As long as the ports that the socket connections use are the same these two programs running on separate computers can communicate with each other. Some of the features include ping, upload and download files, check the contents of a directory, and set up domain names for ease of use.

My team had three members and for my part I was in charge of creating the switch object and also the dns server. The network switch node receives packets and forwards it onto the port of the destination. In the beginning the switch node does not know the location of any of the hosts but once a packet is forwarded it logs the information into its routing table. Host nodes are also able to register domain names with the dns server so that they have a easier name to remember when compared to host0, host1, host45... When a host wants to contact another host via its domain name it must first contact the dns server to get the host id associated with the domain name.

This project helped me to get a better understanding of networking concepts like pipes, sockets, and ports. This was also the first project that we used GitHub for version control. 

For more information here is the <a href="https://github.com/joshuaccl/Network-Simulator">GitHub repo</a>
