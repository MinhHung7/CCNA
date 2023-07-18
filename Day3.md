# Networking model
- Networking models categorize and provide a structure for networking **protocols** and standard
# Protocol
- A set of rules defining how network devices and software should work
# OSI Model
- **Open Systems Interconnection** model
- Created by the International Organization for Standardization(ISO)
# Application Layer (Layer7)
- Interacts with software applications
- **HTTP** and **HTTPS** are layer 7 protocols
- Functions:
  - Identifying communication partners
  - Synchoronizing communication
  - The communication between the application layers of the two different systems, is called same-layer interaction
# Presentation Layer (Layer 6)
- Data in the application layer is in "application format"
- It needs to b translated to different format to be sent over the network
- The **Presentation** layer's job is to translate between application and network formats
# Session Layer (Layer 5)
- Control dialogues (sessions) between communicating hosts
- Establishes, manages, and terminates connections between the local application
  - Your web browser and the remote application (Youtube, ...)
# Transport Layer (Layer 4)
- Segments and reassembles data for communications between end hosts
- Breaks large pieces of data into smaller segments which can be more easily sent over the network and are less likely to cause transmission problems if errors occur
- Provide **host to host** communication(or **end to end**)
# Network Layer (Layer 3)
- Provides connectivity between end hosts on different networks (ouside of the LAN)
- Provide logical addressing (IP addresses)
- Provide path selection between source and destination
- Routers operate at Layer 3
# Data link Layer (Layer 2)
- Provide **node to node** connectivity and data transfer (PC to switch, switch to router, router to router)
- Switch operate at Layer 2
- Data at Layer 2 called **Frame**
# Physical Layer (Layer 1)
# TCP/IP Suite
- Conceptual model and set of communications protocols used in the Internet and other networks
- Developed by the United States Department of Defense through DAPRA (Defense Advanced Research Projects Agency)
- 4 Layers
- This is the model actually in use in modern networks
