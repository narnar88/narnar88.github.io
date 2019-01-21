---
layout: essay
type: essay
title: Network Media, OSI Model, and Packet Switching
# All dates must be YYYY-MM-DD format!
date: 2018-0-15
labels:
  - Data Neworks
  - Packet Switching
  - OSI Model
---


Twisted-Pair Copper Wire

This multipurpose medium is commonly known for telephone and LAN connections
(Kurose & Ross, 2017) . According to fs.com, Twisted-Pair, in comparison to other media, has a median price point, but only capable of shorter distances. However, Twisted-Pair is more sensible than media for shorter distance transmissions because of its lower cost in comparison to other media. Twisted-Pair is also easier to install and maintain than other media due to its durability, or lack thereof in other media ( "Fiber Optic Cable vs Twisted Pair Cable vs Coaxial Cable", 2018 ).

Coaxial Cable

Coaxial is constructed similarly to Twisted-Pair but its conductors are concentric, whereas Twisted-Pair conductors are parallel. Coaxial is capable of 5x the distance for data transmission( "Coaxial Cable vs. Twisted Pair" ), and commonly used for cable television  (Kurose & Ross, 2017) . However, Coaxial Cable is more expensive due to its shielding, but its the more sophisticated shielding that allows the cable to transmit data along longer distances.

Fiber Optics

Fiber Optics has gained a lot of popularity because of its high transmission rates. It creates pulses of light, each representing a bit being transferred. It’s preferred for long distance transmissions, especially overseas links (textbook). However, it also requires extra equipment, such as transmitters, receivers, and switches, thus making it more expensive than other media (Kurose & Ross, 2017) . Also, if a company’s network is still centered on coaxial or twisted-pair, branching a fiber optic off of the main line will not have any significant advantages  ("Coaxial Cable vs. Twisted Pair") .

Satellite Radio Channels

Satellite Radio utilizes multiple microwave transmitters and receivers on Earth, that receive signals in one frequency and re-transmit them in another. These signals are sent to a geostationary satellite or a low-earth orbiting satellite. Geostationary satellites are stationary in space, and low-earth orbiting satellites rotate around Earth. These satellites are used in XM radio ("XM Satellite Radio", 2018) . From personal experience, it is available in recent models of cars. My dad and brother each own a Toyota truck, 2017 and 2018 models respectively, and come equipped with XM radio.

7 Layer OSI Model

Application Layer (7)

The Application layer is the topmost layer in the OSI model. In this layer, protocols
dealing with user data are handled. For example, SMTP, HTTP, FTP, and telnet are used at the application level ("What is the Application Layer? - Definition from Techopedia") .
 
 Presentation (6)
 
The Presentation layers primary purpose is to present data to the top layer. This layer
handles tasks such as data compression, which is needed in transferring files via FTP, which is done in the application layer. It also handles encryption and decryption ("What is the Presentation Layer? - Definition from Techopedia") , which is crucial when creating a secret channel and utilizing public and/or private keys.

Session Layer (5)

The Session layer controls the connections, or session, between other computers  ("What
is the Session Layer? - Definition from Techopedia") . For example, the session layer controls the connections between chrome on my laptop and Laulima.

Transport Layer (4)

Lastly, the Transport layer handles the communications between the source and
destination. This layer handles the breaking down, error checking, transmission and reassembly of packets. This allows for data integrity and flow control  ("What is the Transport Layer? - Definition from Techopedia") .

Network Layer (3)

This layer is responsible for selecting the best path between network nodes to transfer the data. This includes utilization of routers and links  ("What is the Network Layer? - Definition from Techopedia") .

Data Link Layer (2)

This layer is responsible for encoding and decoding bits. It’s two sublayers handle source and destination addresses, as well as error checking and data flow  ("What is the Data Link Layer? - Definition from Techopedia") .

Physical Layer (1)

Lastly, this layer handles requirements of the physical media, such as those discussed in question 1. In this level, bit-level transmission is handled, and mechanical interfaces are supported  ("What is the Physical Layer? - Definition from Techopedia") .

Packet Switched vs Circuit Networks

Packet Switching has some implications in use, but is very efficient in terms of constantly
processing and no time wasted by being “reserved” for other connections. Its first implication is the way in which packets are transmitted. A packet switch has to fully receive a given packet before passing it on to the next switch, also known as store-and-forward transmission. This can cause some delays if other connections need to use that same switch to transmit packets.
There are other delays packets may have over the course of their traversal. Each packet switch has links attached, and each link has an output buffer. If a packet reaches a link while another packet is being processed, the waiting packet goes into an output buffer, creating a queue delay. On top of the delay, if the output buffer is full, and packets keep going to the same link, excess packets and/or packets in the queue are “dropped”, resulting in packet loss.
 
 Circuit networks have the benefit of dedicated connections between source and destination, and creates a “bona fide” connection as described by the textbook. Due to this dedicated connection, all the resources needed for processing and transmitting packets, such as buffers and links, are reserved for a given connection. Thus allowing packets to be transmitted much faster.
However, these dedicated connections are not nearly as efficient as packet switching. Because a unique connection is being made between two endpoints, when there is nothing being transmitted, the connection is practically wasted.
The both each have their respective pros and cons, but packet switching remains the more popular choice of the two. Despite the possibility of delays and dropped packets, packet switching does allow for a more efficient flow of data, optimizing the use of its connections. While circuit networks seem great with little to no possibility of losing connection, it’s not nearly as efficient and requires dedicated resources to maintain reliability  (Kurose & Ross, 2017).

Works Cited

Coaxial Cable vs. Twisted Pair. (n.d.). Retrieved from https://business.cableone.net/business-resources/business-internet/coaxial-cable-vs-twiste d-pair
Fiber Optic Cable vs Twisted Pair Cable vs Coaxial Cable. (2018, April 18). Retrieved from
https://community.fs.com/blog/the-difference-between-fiber-optic-cable-twisted-pair-and
-cable.html

Kurose, J. F., & Ross, K. W. (2017).  Computer networking: A top-down approach . Boston: Pearson.

What is the Application Layer? - Definition from Techopedia. (n.d.). Retrieved from

https://www.techopedia.com/definition/6006/application-layer

What is Data Link Layer? - Definition from Techopedia. (n.d.). Retrieved from https://www.techopedia.com/definition/18698/data-link-layer

What is the Network Layer? - Definition from Techopedia. (n.d.). Retrieved from https://www.techopedia.com/definition/24204/network-layer

What is the Physical Layer? - Definition from Techopedia. (n.d.). Retrieved from https://www.techopedia.com/definition/8866/physical-layer

What is the Presentation Layer? - Definition from Techopedia. (n.d.). Retrieved from https://www.techopedia.com/definition/8955/presentation-layer

What is the Session Layer? - Definition from Techopedia. (n.d.). Retrieved from https://www.techopedia.com/definition/9322/session-layer

What is the Transport Layer? - Definition from Techopedia. (n.d.). Retrieved from https://www.techopedia.com/definition/9760/transport-layer

XM Satellite Radio. (2018, July 15). Retrieved from https://en.wikipedia.org/wiki/XM_Satellite_Radio
