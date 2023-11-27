# Hectors Reading notes


## Ops Readings


### Network Traffic Analysis with Wireshark

1. Why this topic matters as it relates to what you are studying

- The OSI model along with Wireshark are basics that we must at least get familiar with since we are going into the field of Cyber Security. 

#### Layers of OSI Model

1. What does “OSI” stand for?

- Open Systems Interconnection

2. List the 7 layers of the OSI model and what each one is responsible for.

- Physical Layer
   - Is what it sounds like the physical part of the layer: It converts the signals received into 1's and 0's to send to the next layer.
- Data Link Layer
  - "The main function of this layer is to make sure data transfer is error-free from one node to another, over the physical layer." (GeeksforGeeks, SEP2023)
- Network Layer
  - Is were data transmission takes place, it also helps with packet routing.
- Transport Layer
  - Is responsible for end to end transportation of complete messages.
- Session Layer
  - "The layer allows the two processes to establish, use and terminate a connection." (GeeksforGeeks, SEP2023)
- Presentation Layer
  - Data is extracted here and used per the format to transmit.
- Application Layer
  - "produce the data, which has to be transferred over the network. This layer also serves as a window for the application services to access the network and for displaying the received information to the user." (GeeksforGeeks, SEP2023)

3. Distinguish which layers are the “hardware layers”, and which layers are the “software layers”. What does that even mean?

- Hardware is the physical part of the process: cables, computers, power cables, etc. and the software is the digital parts that we cannot see, all the 1's and 0's.
- The hardware layers are the Physical layer, the data link layer, and the network layer
- The software layers are the session layer, the presentation layer, and the application layer.

4. How can the OSI model be used in troubleshooting?

- The OSI model can be used when you need to know where to start. If you know the model and if you know what layer the problem is located at you can save time and effort when troubleshooting.

#### What Is Wireshark and How Is It Used?

1. What is Wireshark?

- network packet capture tool

2. What is a packet?

- A packet is a small piece of data, like UDP and TCP

3. What 3 high-level things does Wireshark accomplish? How could these be used for nefarious purposes? For benevolent purposes?

- Packet Capture: Listens for network connections in real time so it could be used to steal or to capture data for either nefarious or benevolent purposes.
- Filtering: If you filter data you get only what you need and again it can be used to steal or to help but that's all dependent on the user.
- Visualization: Lets you see the entire "conversation" and network streams. You can see who or what has been transferring information and use that to steal,interfere, or just collect and sell information instead of catching, helping, or troubleshooting.

## Things I want to know more about

- Is Wireshark the industry standard?
- Are there other, better programs instead of Wireshark
- What layer of the OSI model will I be working on the most.
 
## Resources
https://www.geeksforgeeks.org/open-systems-interconnection-model-osi/
(Used for general understanding and quoted in the reading)

https://www.comptia.org/content/articles/what-is-wireshark-and-how-to-use-it
(Used for general understanding and quoted in the reading)