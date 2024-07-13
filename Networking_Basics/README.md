# Computer Networking
1. Contents
   - Networking components
   - OSI Model
   - Classification
   - Devices
   - Home Network
   - IP Addresses
   - Protocols
   - DNS and DHCP
   - Networking Commands
  
# What is a Computer Network?
- Communication between two or more network interfaces.

# Components of Computer Network
1. Two or more computer devices
2. Cables as link between the computers
3. A network intefacing card (NIC) on each device (Computers)
4. Switches
5. Routers
6. Software called OS - Operating System

# OSI Model
- People around the world uses computer network to communicate with each other
- For worldwide data communication, system must be developed which are compatible to communicate with each other
- There should be standard communication methods and devices
- ISO (International Organization of Stadardization) has developed this standard for network communication

OSI Model -> This communication model is called an Open System Interconnection OSI

# ISO - OSI model is a seven layer architecture
1. Physical              7. Application Layer
2. Datalink              6. Presentation Layer
3. Network               5. Session Layer
4. Transport             4. Transport Layer
5. Session               3. Network Layer
6. Presentation          2. Datalink Layer
7. Application           1. Physical Layer

# Basic elements of a layered model are:
"--> Services --> Protocols --> and Interface"

1. A service is a set of action that a layer offers to another (higher) layer
2. A protocol is a set of rules that a layer uses to exchange information
3. Interface is communication between the layers

# OSI Model
![image](https://github.com/uzair-ansar/devops/assets/146664651/cf8576f8-e685-469e-b459-52725542e85d)

![image](https://github.com/user-attachments/assets/bf8862f1-385a-4369-a30f-e8213e351d8d)

- Application: To allow access to network
- Presentation: To translate, encypt and compress data
- Session: To establish, manage, and terminate sessions
- Transport: To provide reliable process-to-process message delivery and error  recovery
- Network: To move packets from source to destination to provide internetworking
- Datalink: To organize bits into frames; to provide hop-tohop delivery
- Physical: To transit bits over a medium; to provide mechanical and electrical specifications

# Classification of network by Geography
- LAN: Local Area Network (in a room)
- WAN: Wide Area Network (far, far away, hosted somewhere, internet)
- MAN: Metropolitan Area Network (Municipality, Metro train)
- CAN: Campus Area Network (College campus, office campus)
- PAN: Personal Area Network (Bluetooth, hotspot)

# Switches
- Facilitate the sharing of resources by connecting together all the devices, including computers, printers, and servers, in a small business network
- Example: Like your WiFi router, there's a switch inside that, used to create local area network

# Router
- As switch connects multiple computers together, router connects multiple network together
- Router receives and sends data on computer network
- In CAN, you have one building where you have a switch and some computers connected to it and then you have a second building where you have another switch, if you want to enable communication between these switches or maybe computer from building one to communicate to computer in building two, so there's two different netwoek. You want to connect both network together you need the router.
