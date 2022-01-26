`Reference` : `The Official CompTIA Network+ Study Guide`
# 𝐍𝐞𝐭𝐰𝐨𝐫𝐤+ 𝐂𝐞𝐫𝐭𝐢𝐟𝐢𝐜𝐚𝐭𝐢𝐨𝐧 𝐍𝐨𝐭𝐞𝐬

## 𝐒𝐭𝐚𝐫𝐭𝐢𝐧𝐠 𝐭𝐢𝐦𝐞

- Started: `22nd Jan 2022`
- End date: ``

`𝟐𝟐𝐧𝐝 𝐉𝐚𝐧 𝟐𝟎𝟐𝟐`

## 𝐀𝐢𝐦

- Explain the OSI and TCP/IP models
- Explain properties of network traffic
- Install and configure switched networks
- Configure IP networks
- Install and configure routed networks
- Configure and monitor ports and protocols
- Explain network application and storage issues
- Monitor and troubleshoot networks
- Explain network attacks and mitigations
- Install and configure security devices
- Explain authentication and access control
- Deploy and troubleshoot cabling solutions
- Implement and troubleshoot wireless technologies
- Compare and contrast WAN technologies
- Use remote access methods.
- Identify site policies and best practices.

# 𝐄𝐱𝐩𝐥𝐚𝐢𝐧𝐢𝐧𝐠 𝐭𝐡𝐞 𝐎𝐒𝐈 𝐚𝐧𝐝 𝐓𝐂𝐏/𝐈𝐏 𝐌𝐨𝐝𝐞𝐥𝐬

## 𝐎𝐛𝐣𝐞𝐜𝐭𝐢𝐯𝐞𝐬

- Describe the functions of layers of the OSI Model.
- Describe the functions of layers of the TCP/IP Model.

## 𝐎𝐒𝐈 𝐌𝐨𝐝𝐞𝐥

- Stands for *Open System Interconnection* (OSI) Model
- What is network?
> - Two or more devices interconnected to each other are called as network.
> - Devices connected to each other are called as **nodes.**
> - The pathway by which they are connected is called as **links.**

- Local Area Network (LAN):
> A network in single geographical location is called as Local Area Network/LAN

- Wide Area Network (WAN):
> A network connecting large geographical location is called as Wide Area Network (WAN)

## 𝐎𝐒𝐈 𝐌𝐨𝐝𝐞𝐥 𝐋𝐚𝐲𝐞𝐫𝐬

```
+---+    +----------------------------------+
| 7 |    |        Application Layer         |
+---+    +----------------------------------+
+---+    +----------------------------------+
| 6 |    |        Presentation Layer        |
+---+    +----------------------------------+
+---+    +----------------------------------+
| 5 |    |        Session Layer             |
+---+    +----------------------------------+
+---+    +----------------------------------+
| 4 |    |        Transport Layer           |
+---+    +----------------------------------+
+---+    +----------------------------------+
| 3 |    |        Network Layer             |
+---+    +----------------------------------+
+---+    +----------------------------------+
| 2 |    |        Data Link Layer           |
+---+    +----------------------------------+
+---+    +----------------------------------+
| 1 |    |        Physical Layer            |
+---+    +----------------------------------+

```
- Mnemonic To remember all seven layers: `All People Seem to Need Data Processing`
- OSI model is not a standard or specification; it serves as a functional guideline to troubleshoot networks, and design network protocols, software's and appliances.

## 𝐏𝐫𝐨𝐭𝐨𝐜𝐨𝐥 𝐃𝐚𝐭𝐚 𝐔𝐧𝐢𝐭𝐬 (𝐏𝐃𝐔𝐬)

- What are protocols?
> - So, protocols are the set of rules which enables communication by exchanging data in structured format.
> - Two most basic functions of protocols are to:
>   - Describe where the data should go (addressing)
>   - Describe how the data should be packaged for transmission (encapsulation)

- At each layer, for two nodes to communicate they must be operating on same protocols.
- What is same layer interaction? Interaction between two nodes on same layer is called as same layer interaction.
- For adjacent layers, it is called as adjacent layer interaction.
- At each layer of data transmission except physical layer, the sending node adds a header to the data payload, forming a chunk of data called as protocol data unit (PDU). And the process is known as encapsulation.

![image](https://user-images.githubusercontent.com/68887544/150631014-d03f37a7-466c-4b2d-865b-7d625b6b04a3.png)

- The receiving node performs a reverse process called as de-encapsulation or decapsulation


## 𝐏𝐡𝐲𝐬𝐢𝐜𝐚𝐥 𝐋𝐚𝐲𝐞𝐫 (𝐋𝐚𝐲𝐞𝐫 𝟏)

- A node is the term used to describe devices that can communication on a network.
- On a wireless network, the term is called as station.
- Term host is used in TCP/IP networking
- Physical layer is responsible for physically transform data either using cables or wireless using radio transmission.
- Devices operating at physical layers are:
    - Transceivers : it is a part of network interface that sends and receives signals over the network media
    - Repeater : A device that amplifies electronic signal to extend the maximum allowable distance for a media type.
    - Hubs : A multiport repeater.
    - Media Converters : Converts one media signaling type to another.
    - Modems : converts between digital and analog signal transmission


---

`26th January 2022`
## 𝐓𝐨𝐩𝐢𝐜 𝐀 - 𝐎𝐒𝐈 𝐌𝐨𝐝𝐞𝐥 : 𝐐𝐮𝐞𝐬𝐭𝐢𝐨𝐧𝐬

- What is a network?
- What is nodes, what is links?
- What are LANs and WANs?
- what's the full form of OSI?
- What are the seven layers of OSI model?
- What is protocol?
- What is protocol data units?
- Describe physical layer?
- Which devices operates at the physical layer?
- What is data link layer?
- What is local/hardware addresses?
- What's the structured units where the streams of 1s and 0s arriving from the physical layer are organized in data link layer?
- Connectivity Devices in data link layer?
- What is network layer?
- What is transport layer?
- What is session layer?
- Describe session modes?
- what is Presentation layer?
- What is application layer?
- Summarize osi model.

## 𝐓𝐨𝐩𝐢𝐜 𝐀 - 𝐎𝐒𝐈 𝐌𝐨𝐝𝐞𝐥 : 𝐍𝐨𝐭𝐞𝐬

- What is network?
> - Two or more devices connected to each other where they can share information is called as a network.
> - There are two components of a network:
>   - Nodes: Devices connected in a network  
>   - Links: Pathway by which they are connected

-------------------------------------------------------------------

- What is LAN and WAN?
> - Network can be classified into different kind of networks depending on the size:
>   - In a single location : LAN (Local Area Network)
>   - connecting more than one location : WAN (Wide Area Network)

-------------------------------------------------------------------

- Full form of OSI : `Open System Interconnection`
- Different layers of OSI:
> - All people seem to need data Processing
> - Application layer
> - Presentation layer
> - Session layer
> - Transport layer
> - Network layer
> - Data link layer
> - Physical layer

------------------------------------------------------------------

#### 1 pomodoro done! Summary:
> - I learned network, node and links
> - OSI model full form
> - LAN & WAN
> - Layers of OSI Model

-------------------------------------------------------------------

- Why OSI model and why layering?
> - Because it adds structure to the data transmission.
> - For example, when we divide a problem into steps on the basis of their functionality, understanding the problem becomes much easier, similar is the approach of OSI model.
> - troubleshooting becomes much easier when a problem arises and it problem won't be able to affect other layers.

------------------------------------------------------------------

- What is protocol?
> - Protocol is a set of rules which enables communication using structured exchange of data.

-------------------------------------------------------------------

- What is PDU?
> - PDU stands for Protocol data unit.
> - When we have to transmit the information, we need to pass the data between each layer one by one. During this process, at each layer (except physical layer), the sending device add a header to the data payload in the form of a chunk, this chunk is called as Protocol data unit i.e. PDU. And the process is called as `encapsulation`. The reverse is called as `de-encapsulation` or `decapsulation`.

-------------------------------------------------------------------

- Describe the physical layer?
> - this is the layer at which the data transmission begins
> - Nodes in a computer network is connected using a physical media, this physical media can be cables or it can be wireless, this media is called as physical layer.

------------------------------------------------------------------

- Devices operating in the physical layer:
> - Transceivers
> - Repeater
> - Hubs
> - Media converters
> - Modems

-------------------------------------------------------------------

- Describe data link layer:
> - Data link layer facilitates node to node data transmission.
> - Data transmission from one physical device address to another.

-------------------------------------------------------------------

- Connectivity Devices in data link layer:
> - Network adapters or network interface cards (NICs)
> - Bridge
> - Switches
> - Wireless access points (APs)

-------------------------------------------------------------------

#### 2 Pomodoro done: Summary:

- Physical layer done
- Data link layer done
- Why we use OSI model also done
- Protocol and PDU also understood

-------------------------------------------------------------------

- What is network layer?
> - It is a layer responsible for moving the data along the network of networks.

-------------------------------------------------------------------

- Describe transport layer:
> - Transport layer is also known as host-to-host or end-to-end layer.
> - It is responsible for identifying each type of network application by assigning it a port number.
> - It is responsible for reliable data delivery.

-------------------------------------------------------------------

- Describe session layer:
> - it is responsible for establishing, managing and terminating communication between nodes.

------------------------------------------------------------------

- 3 modes a session can work:
> - One-way/simplex => Only one sends and other receives
> - Two-way alternate(TWA)/half-duplex: Hosts can send messages but not simultaneously
> - Two-way simultaneous (TWS)/duplex: Hosts can send messages simultaneously

-------------------------------------------------------------------

- Describe presentation layer:
> - Presentation layer is responsible for converting data from network layer to a suitable format which can be used in application layer (and vice versa.)

-------------------------------------------------------------------

- Describe application layer:
> - application layer provides interface between software and network.

-------------------------------------------------------------------

#### 3 Pomodoro done: summary

- network layer
- transport layer
- session layers
- presentation layer
- application layer

-------------------------------------------------------------------

- OSI Model Summary:

```
+---+  +-----------------------+    +-----------------------+  +---------------------+  +-----------------+
| 7 |  |   Application         |    |    Application        |  |     Stateful/       |  |                 |
+---+  +-----------------------+    |    Protocol           |  |    Application      |  |                 |
+---+  +-----------------------+    |  (Web, Email, File    |  |       Layer         |  |                 |
| 6 |  |   Presentation        |    |       Transfer...)    |  |     Security        |  |                 |
+---+  +-----------------------+    |                       |  |     Appliance       |  |   Multilayer    |
+---+  +-----------------------+    |                       |  |                     |  |    switch       |
| 5 |  |     Session           |    |                       |  |                     |  |                 |
+---+  +-----------------------+    +-----------------------+  |                     |  |                 |
+---+  +-----------------------+    +=======================+  |                     |  |                 |
| 4 |  |       Transport       |    |      Segment          |  |                     |  |                 |
+---+  +-----------------------+    +=======================+  +---------------------+  +-----------------+
+---+  +-----------------------+    +=============+  +================+  +====================+ +==============+
| 3 |  |     Network           |    |   Datagram  |  |  IP Address    |  |  Basic Firewall    | |   Router     |
+---+  +-----------------------+    +=============+  +================+  +====================+ +==============+
+---+  +-----------------------+    +==========+  +========================+ +============+ +=========+
| 2 |  |       Data link       |  --|  Frame   |  |    MAC Address / EUI   | |  Bridge    | | Switch  |
+---+  +-----------------------+  | +==========+  +========================+ +============+ +=========+
                                  |  Network |          |  Access  |
                                  |  Adapter |          |  point   |
+---+  +-----------------------+  | +=============+ +=========+ +=================+ +=====+
| 1 |  |    Physical           |  --| Transceiver | |  Cable  | | Media Converter | | Hub |
+---+  +-----------------------+    +=============+ +=========+ +=================+ +=====+

```
