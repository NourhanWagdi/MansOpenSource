# Internet Border Patrol

> Internet border patrol: preventing congestion collapse and promoting fairness in the Internet.

![net_border_patrol](icon.jpg)

Internet supports various features such as scalability and that too at a lowest possible cost; a part of this includes congestion control over the internet. Well a variety of congestion control algorithms are available these days but yet prove unworthy in controlling congestions over busy networks. These algorithms are not capable of alone handling congestions over the network. In order to define an efficient algorithm that helps to control any type of network congestions an innovative approach known as internet border patrol would be developed in this project .It controls and monitors various packets and unresponsive data at each border of the network to check for chances of network congestion. This helps preventing congestions over a network. Well to further increase its efficiency, this system is supplemented with enhanced core-stateless fair queuing (ECSFQ) algorithm that allows for even bandwidth flow through resource allocation handling.

## How it works
The basic principle of NBP (Network Border Patrol) is to compare, at the borders of a network, the rates at which packets from each application flow are entering and leaving the network. If a flow’s packets are entering the network faster than they are leaving it, then the network is likely buffering or, worse yet, discarding the flow’s packets. In other words, the network is receiving more packets than it is capable of handling. NBP prevents this scenario by patrolling the network’s borders, ensuring that each flow’s packets do not enter the network at a rate greater than they are able to leave the network. This patrolling prevents congestion collapse from undelivered packets; because unresponsive flow’s otherwise undeliverable packets never enter the network in the first place. 

## Goals
1. Eliminate congestion collapse resulting from undelivered packets
2. Necessary for discovering source, communicate per-flow bit rates & detect network congestion by estimating RTT
3. Backward feedback packets can be generated asynchronously.(RTT cannot be calculated in this case).

*****

__For more information about "Network Border Patrol" and how it works, follow__ [this link.](https://scialert.net/fulltextmobile/?doi=itj.2006.427.432)

*Nourhan Wagdi*
