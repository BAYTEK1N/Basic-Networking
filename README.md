# Basic Networking
---
## Network devices

<p align="center"><img src="https://github.com/BAYTEK1N/Basic-Networking/blob/main/img/network-device-icons.png"></p>

Equipment that connects directly to a network segment is referred to as a **device**. Device is broken up to two classifications are ender-user devices and network devices.

Examples of end-user devices are(***Computers, printers, scanners, and other devices that provide services directly to the user***)

Example of network devices are(Repeater, Hub, Bridge,group switch,router, cloud, and  all the devices that provide that connects the end-user devices together to allow them to communicate)

- **Repeaters** : are used in transmission systems to regenerate digital signals distorted by transmission loss.  repeaters frequently can only amplify the signal while   digital repeaters can reconstruct a signal to near its original quality.

- **Hub**: to broadcast the network for every computer(over) now we using switches(Work group switch)

- **Router**: allow to connect two separate machines from LAN

- **Work group switch**: add more intelligence to data transfer management, A network switch is a small hardware device that transfer the data to the connection that needs that data. Joins multiple computers together within one local area network (LAN).

- **The Cloud**: is the internet
---

## Networking concept

concept of network like Local area network (LAN) is a group of computers and as associated devices that share a a common **communication line** or **wireless link**. Typically connected devices share the resources of single processor or server within a small geography area.

network purpose is to share the sources. devices are broken up into two : end-user devices and network devices.

Cable **RJ45** to access network for Computer and laptop

**WLAN**: Wireless Local Area Network

### **Network diference**

<p align="left"><img src="https://github.com/BAYTEK1N/Basic-Networking/blob/main/img/peer-to-peer.png"></p>


**Peer to Peer:**


All computer are same authority and  no server,limit 10 PC, if you need people to use your network, you need authentication, you need to create account username and password for everyone to use the network.

| Advantages of peer to peer networking | Disadvantages of peer to peer |
| :---:| :---:|
|  Easy to set up   |  No centralized administrator   | 
| Less complexity | Not secure |
| Lower cost | no server |
| Can be used for simple tasks such as **transferring files** and **sharing printers.** | All devices have same authority |

<p align="left"><img src="https://github.com/BAYTEK1N/Basic-Networking/blob/main/img/client-server1.png"></p>

Client/ server network( share network):  network operation system refers to software that implements an operation system of kind that oriented to computer networking. As security the three factors are authentication , fingerprint, credit card and the collection of user information are user ID, password, permissions.

For example one that run a server and enables the server to manage data, users, groups, security,applications and other networking functions.`NOS: e.g Microsoft, Unix, Window 1998, Window 2003,Window XP

WLAN: Acronym for wireless local area network. A type of local area network that uses hight frequency radio-waves rather than wires to communicate between nodes.

 

### Communication channels can be:

Simplex, meaning unidirectional communication from one sender to one receiver; E.g T.V, Radio, Megaphone.

Half duplex, meaning bidirectional communication but only in one direction at a time;  E.g walkie-talkie two-way radio that has a “push-to-talk” button

Full duplex, meaning bidirectional communication, potentially in both directions simultaneously; E.g Mobile phone

## UPT and STP (cable for Ethernet network)

- Unsheided twisted pair(UTP)
- Shielded twisted pair(STP)

### UTP

- Cat3-10Mbps
- Cat5-100Mbps
- Cat5e-1Gbps
- Cat6-up to 2.5Gbps

Cat5 needs repeater signal it’s going to lose strength and  ***the terminator*** allows to stop data going back to avoid collision.

Coax connector has Cat5 TP , RJ-45, RJ-II connectors (cable). the terminating cable to an RJ-45 plugging (prepare the cable) 1cm off small cable with different colour.

**Fibre optic type of cable:** the best cable in the network very fast , back borne, specialist of prepare the cable ( very careful).

### **Linking computes**

- RS-232
- IEE I 394/fire wine
- USB 2,0
- Network interface card

### **Ethernet**

Type of connection: NIC, MAC addresses(Media access control addresses) Package address deal with more computer.

### **Wireless LAN (limitations)**

##Ethernet topology

Network topologies are categorized as either a ***physical network topology*** or ***logical network topology***. The physical topology of a network is the physical layout of nodes and connections. Connections include the lines in diagrams that connect nodes, such as **Ethernet** or **Digital Subscriber Line wires**, **fiber optics** and **microwaves**. Logical network topologies define how a network is set up, including which nodes connect and how, as well as the pattern of data transfers.

<p align="center"><img src="https://github.com/BAYTEK1N/Basic-Networking/blob/main/img/whatis-network_topology_02-f.png"></p>

### There are several types of topologies. For example, physical topologies include the following:

- **Bus network.** In the bus network topology, every node is connected in series along a single cable. This arrangement is found today primarily in cable broadband distribution networks.

- **Star network.** In the star network topology, a central device connects to all other nodes through a central hub. Switched local area networks based on Ethernet switches and most wired home and office networks have a physical star topology.

- **Ring network.** In the ring network topology, the nodes are connected in a closed-loop configuration. Some rings pass data in one direction only, while others are capable of transmission in both directions. These bidirectional ring networks are more resilient than bus networks since traffic can reach a node by moving in either direction. Metro networks based on Synchronous Optical Network technology are the primary example of ring networks.

- **Mesh network.** The mesh network topology links nodes with connections so that multiple paths between at least some points of the network are available. A network is considered to be fully meshed if all nodes are directly connected to all other nodes and partially meshed if only some nodes have multiple connections to others. Meshing multiple paths increases resiliency but also increases cost. However, more space is needed for dedicated links.

- **Tree network.** The tree network topology consists of one root node, and all other nodes are connected in a hierarchy. The topology itself is connected in a star configuration. Many larger Ethernet switch networks, including data center networks, are configured as trees.

- **Hybrid network.** The hybrid network topology is any combination of two or more topologies. Hybrid topologies typically provide exceptional flexibility, as they can accommodate a number of setups. For example, different departments in the same organization may opt for personalized network topologies that are more adaptable to their network needs.

A logical topology for a network refers to the relationship between nodes and logical connections -- defining how data should transfer.

A logical connection differs from a physical path when information can take an invisible hop at intermediate points. In optical networks, optical add-drop multiplexers create logical optical paths because the ADM hop is not visible to the endpoint nodes. Networks based on virtual circuits or tunnels have a physical topology based on the real connection medium -- fiber, for example -- and a logical topology based on the circuits and tunnels.

Sometimes, the logical topology refers to the topology as the user sees it. Internet Protocol (IP) and Ethernet networks are two common examples. They are fully meshed at the connection level since any user can connect with any other user. This is true unless some means of blocking unwanted connections, like a firewall, is introduced. Full connectivity is a property of the network protocols used -- IP and Ethernet -- not of the network topology itself.

As an example, logical bus and logical ring topologies can be used to define data transmission flows. A logical bus topology features nodes that broadcast data to the entire network. Other nodes on the network check to see if the data is meant for them. Logical ring topology only allows one node to transfer data at a time.


### <a href="https://github.com/BAYTEK1N">BAYTEK1N</a>
