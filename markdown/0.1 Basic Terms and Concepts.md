# Basic Terms and Concepts

## Communication Basics
Communication in general terms needs at least 2 subjects which have to share some point in common to be effective
- Common Medium: 
- Common Rules: 

## Network
- **Node** single element connected in a network  
  *pc, smartphone, printer*
- **Link** physical inter-connection medium 
  *cables, waves*
- **Network** series of linked nodes  
  *LAN, WAN, Internet*

### Client & Server Paradigm
All computers connected to a network that participate directly in network communication are classified as **hosts**.
Depending on the software installed, hosts can act as
- **Client** host using software requesting, receiving and rendering informations from servers *browser,ftp,web mail*
- **Server** host using software providing informations to clients' requests *websites,video service* 
  serving more than 1 client and providing more than 1 service
- or __both__ hosts with software installed for both roles

Client-Server paradigm foresees a client requesting informations and a server storing and providing those informations to whoever requesting it.

### Peer-to-Peer
*Type of network where all hosts act as both Client and Server when necessary*  
*more than 2 hosts need network devices (switch)*

a P2P network is made possible by using a specific **application** requiring each end device a

- User Interface
- Background Service

Communication Type: **Full Duplex**  
*Both clients can simultaneously send and receive messages*

---

## Protocols
Set of __shared rules__ used during communication of whatever type,  
Protocols are essential for a successful communication.

Protocols are required to properly communicate across the network.  
The use of networking protocols depends on the __type of message__ and communication __channel__ used

Networking protocols defines **Message**'s:

- **Format** *specific structure*
- **Size** *strict rules, may be necessary to break a long mesg in smaller chunks*
- **Timing** *speed of transmitted bits*
- **Encoding** *converting bits in physical elements, depending on the media, for transmission*
- **Encapsulation** *process of including headers with addressing informations*
- **Pattern** *acknowledgments required by request/response pattern - most common*

Protocols are the rules that govern network communications

## Standards

A standard is a set of rules that determines how something must be done. Networking and internet standards ensure that all devices connecting to the network implement the same set of rules or protocols in the same manner.

---

## Communication types

There are different ways to communication with other devices.  
Transmition communication types are:

- **Unicast** *one-to-**one***  
  message sent to __one network's host__
- **Broadcast** *one-to-**all***  
  message sent to __all network's hosts__
- **Multicast** *one-to-**many***  
  message sent to a __selected network's group__ . 
  - Multicast clients *represented by one IPv4 destination address*

::: info
in IPv4 address range:  
__Unicast__      1.1.1.1 - **223**.255.255.255  
__Munticast__ **224**.0.0.0 - 239.255.255.255  
__Broadcast__ **255**.255.255.255

:::

---

## Network types

- [ ] Intranet
