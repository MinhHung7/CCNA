# Ethernet Trailer
  - FCS (Frame Check Sequence (4 bytes)
    - Detects corrupted data by running a "CRC" algorithm over the received data
    - CRC = **Cyclic Redundancy Check**
# Ethernet Header
  - Preamble (7 bytes)
    - 10101010 * 7
    - Allows devices to synchronize their receiver clocks
  - SFD (Start Frame Delimiter) (1 bytes)
    - 10101011
    - Marks the end of the preamble and the begining of the rest of the frame
  - Destination
  - Source
  - Type (IPv4 or IPv6) (2 bytes)
    - A value of **1500 or less** in this filed indicates the **LENGTH** of the encapsulated packet (in bytes)
    - A value of **1536 or greater** in this filed indicates the **TYPE** of the encapsulated packet
# MAC Address
- BIA = **Burned-In Address**
- Globally unique
- Dynamic MAC addresses are removed from the MAC address table after 5 minutes of inactivity
- 
