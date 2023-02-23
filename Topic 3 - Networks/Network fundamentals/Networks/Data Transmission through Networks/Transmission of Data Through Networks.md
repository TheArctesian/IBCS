1.  Systems must connect to the network through an address and/or port
2.  Data is encoded by the client or the server in the protocol’s format.
3.  Data is broken up into small groups called **packets.** Each packet should also contain information about the sender and the destination.
4.  **Packets** travel through the network, either wirelessly or through cables, to their destination.
5.  Switches/routers make sure the data is sent to the correct destination.
6.  The destination application receives the data and decodes it into the desired form. The **packets** will contain binary data and the destination should be able to convert it into strings, objects or primitive types.

## Standards protocls
- [[OSI]]
- [[TCP]]

Why do we need protocols
  
1. Rules about the message format  
2. Rules about the way intermediary devices should facilitate communication  
3. Rules about initiation and termination of a communication session  
4. Rules about the type of error checking to be used  
5. Rules about the data compression methods and algorithms (if compression takes place)  
6. Rules about an error detection and correction mechanism Rules about recovery and resending of data

## Compression
- [[Lossy Data Compression]]
- [[Lossless Data Compression]]

## Different Transmission Media
- [[Wired Communication]]  
- [[Wireless Communication]]
