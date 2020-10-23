# ITI Open Source Study Guide
## Week 1 - Computer Networks
1) [Introduction to Computer Networks](#introduction-to-computer-networks)

2) [OSI Model](#osi-model)
3) [TCP/IP Model](#tcp/ip-model)
5) [Network Devices](#network-devices)
6) [Network media](#network-media)
7) [Introduction to Wireless Networks](#wireless-networks)
8) [Security Fundamentals](#security-fundamentals) 


### Introduction to Computer Networks
* Basics
1) [Difference between Hubs,Switches,and Routers](https://medium.com/@fiberstoreorenda/do-you-know-the-difference-between-hub-switch-router-b74c2e8a8143#:~:text=A%20hub%20works%20on%20the,link%20layer%20(Layer%202).&text=A%20switch%20can%20join%20multiple,target%20of%20the%20forwarding%20data.) 
2) [Network Topologies](https://www.dnsstuff.com/what-is-network-topology)
3) [What are Peer to Peer networks](https://www.indeed.com/career-advice/career-development/what-is-a-peer-to-peer-network)
4) [What is the Client/Server Architecture](https://medium.com/@anirudh.rajmohan/client-server-architecture-1bbaf457876a)
5) [An Important well rounded summary](https://medium.com/@computerscienceengineering/basics-of-computer-networking-6c7b961f4e14)

### OSI Model
* Review these two lectures here: 
1) [OSI Model from a developer POV](https://www.youtube.com/watch?v=7IS7gigunyI)
2) [OSI Model from an IT POV](https://www.youtube.com/watch?v=HEEnLZV2wGI)
* Summary of the Open systems interconnect
+ Layer 1 Physical :
This is the physical layer, in which 1 and 0 data bytes can be sent as electric signals, wifi, or light via "the wire"

+ Layer 2 Data Link :
These are the separation of the data bytes into frames.
Notably, the frames will identify the source and destination MAC addresses of the devices' network card.
Since electrical signals travel in all directions in a network, the data frames reach all devices in the network.
Once the data frame is able to identify that the device is not the intended destination, the frames drop.
In an unsecured network, this is where a malicious application can choose to not drop the frames, and steal the data.

+ Layer 3 Network :
Once layer 2 is done, it generalizes the frames from MAC addresses to IP addresses.

+ Layer 4 Transport :
This tranport layer further generalizes the network layer IP address into source and destination ports.

+ Layer 5 Session :
Since there may be several TCP connections to one server at a time, with identical packet information from layers 1 through 4, we need a way to distinguish the session by ID to tag it.

+ Layer 6 Presentation :
This is where the resource might be secured/encrypted with HTTPS/TLS by scrambling the HTTP request string.
I didn't know HTTPS encrypted anything. I thought it was only a way to identify the true identity of a website.
Also, encryption might be accomplished via VPN.
At this step, if the data is encrypted, the model decrypts the information to reach step 7.
It might be possible that a malicious attack to steal data can be avoided by encrypting.
"This is where you can get screwed if you are on public wifi...people can sniff your data."

+ Layer 7 Application :
This is where a client device makes a request to a server device, such as a GET request.
This request contains a whole bunch of information, such as headers, cookies, content-type headers, etc, which is summarized into a string, so the string can participate with the rest of the OSI models as byte data.

### TCP/IP Model
+ Review this Lecture:
1) [OSI and TCP/IP Model](https://www.youtube.com/watch?v=3b_TAYtzuho)

* Public IP vs Private IP:
1) [Public IP vs Private IP](https://www.youtube.com/watch?v=92b-jjBURkw
)
2) [Nating from a developer POV](https://www.youtube.com/watch?v=RG97rvw1eUo)

* DHCP server How does it Work?
1) [DHCP Server](https://www.youtube.com/watch?v=jrzYLt7qclI&t=341s)

* [Network ID and Subnet Mask](https://www.youtube.com/watch?v=XQ3T14SIlV4)
* [ARP](https://www.youtube.com/watch?v=mqWEWye-8m8)

### Network Devices
* Network Hardware
1) devices such as computers , printers and phones
2) NIC
3) Repeater
4) Hub
5) Switch
6) Router
7) Splitter
8) Patch Panels

### Network Media
* Network Transmission Media
1) Cable Media
2) Wireless Media
* Cable Media
1) STP (shielded twisted pair)
2) UTP (unshielded twisted pair )
3) Fiber Optics
4) Coaxial Cables
* Wireless Media
1) Wifi
2) Infrared
3) Bluetooth
4) Microwave

[UTP vs STP ](https://medium.com/@julydd/stp-vs-utp-which-one-is-better-96e6fc612afa)
* Advantages of Fiber Optics :
1) Faster than twisted pair and coaxial
2) Send data as light pulses over glass medium
3) Free of electromagnetic interference
3) Highly resistance to Eavesdropping
4) Support extremely high data transfer rate
5) Allow grater cable distances without repeater

### Wireless Networks
* [How Wireless Communication Works](https://medium.com/science-journal/how-wireless-communication-works-a839fc5d41f7)
* [How Wireless Communication integrates in the IOT world](https://medium.com/@hardymunjal/communication-wireless-protocols-in-iot-7da097ebbe96)
* [Virtualization](https://www.redhat.com/en/topics/virtualization/what-is-virtualization)
* [HyperVisors](https://www.redhat.com/en/topics/virtualization/what-is-a-hypervisor)
* [What is cloud computing?](https://azure.microsoft.com/en-us/overview/what-is-cloud-computing/#cloud-deployment-types)
* It is recommended to read the pdf regarding this section for further knowledge

### Security Fundamentals
* [Security in general](https://www.redhat.com/en/topics/security)
* [White hat vs gray hat vs black hat hackers](https://medium.com/@SravanCynixit/whats-the-difference-between-white-hat-gray-hat-and-black-hat-hacking-25a013878a3f)
*  It is recommended to read the pdf regarding this section for further knowledge


