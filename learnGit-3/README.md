* What is the OSI model? 
* Explain the different layers of the OSI model. 
* What do you mean by the TCP/IP Model? 
* What do you mean by HTTP, TCP and UDP 
* What is a Firewall? 
* Explain DNS 
* Serve a simple application running on any random port (eg: 3000) via Nginx 
* Install SSL/TLS certificate in Nginx to load application over HTTPS 

## OSI MODEL :
** Open System Interconnection Model is a conceptual model that categories and standardize the different functions in a network 
** It was created by the International organization for Standardization 
* Functions are divided into seven layers which are :
* Application Layer
* Presentation Layer
* Session Layer
* Transport layer
* Network Layer
* data-Link Layer
* Physical Layer 


## Application layer :
** This layer is the closest to the end user , It interacts with the software application like web browser(Brave,Firefox,Chrome,etc.),Http and Https are part of layer 7 protocols.
### The functions of layer 7 includes
* Identifying Communication partterns 
* Synchronizing Communication

## Presentation layer :
** Data from the application layer are in application format and they are being translated to a different format to be send over the network ,the presentation layer job is to translate between application and network format for example ,encryption of data as it is sent and decrytion of data as it is recieved . 

## Session Layer :
* This layer controls dialogues (sessions) between communicating hosts
* establishes,manages and terminates connections between the local applications (for example web browser) and the remote application (for example youtube)

**Ntework engineers usually work with the top 3 layers**
**Application developers work with the top layer of the OSI model to connect their application over the network**

## Transport Layer:
* This layer segments and reassembles data for communications between end hosts,It breaks large pieces of data into smaller segments which can be more easily sent over the network and are less likely to cause transmission problems if errors occurs .It provides host to host communication 
[DATA + L4 HEADER ]--> segment


## Network Layer:
** This layer provides connectivity between end hosts on different networks (i.e outside the LAN)
** It provides pathh selection between source and destination
** Routers operate at this layer
[DATA + L4 HEADER + L3 HEADER]--.packet

## Data-links Layer:
* Provides node-to-node connectivity and data transfer 
* It defines how data is formatted for transmission over a physical medium e.g UTP cables 
* Detects and (possibly) corrects physical layer errors

## Physical Layer:
* Defines the physical characteristics of the medium used to transfer data between device 
* Digital bits are coverted intp electrical for wired connection or radio for wireless connection signal 

## TCP/IP Model






