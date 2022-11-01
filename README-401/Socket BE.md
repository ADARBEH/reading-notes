### 1. The Physical Layer
##### The physical layer is where the raw bitstream is physically transmitted over a physical medium. The Layer 1 PDU is the “symbol”. This includes translating bits to electricity, light, or radio signals and controlling the rates at which they are sent over the chosen medium.

### 2. The Data Link Layer
##### The data link layer breaks data to be transmitted into frames for transmission at the physical layer. It also manages connections between two different nodes, including setting up the connection, identifying and correcting any bit errors that occur at the physical layer, and terminating the connection once the session is complete.

### 3. The Network Layer
##### At the network layer, the focus expands from a point-to-point link to include many interconnected nodes within a network. Network-layer devices operate on packets and are responsible for routing traffic to its destination based on IP addresses. 

### 4. The Transport Layer
##### The transport layer is the first of four “host” layers with the rest referred to as “media” layers. The transport layer PDU is the “segment” or “datagram”. This layer manages the transmission of data between nodes, including ensuring that data arrives in the correct sequence and that any errors are corrected. The Transmission Control Protocol (TCP) operates at Layer 4

### 5. The Session Layer
##### The session layer manages sessions between nodes and acts on the “data” PDU. Session management includes setup, authentication, termination, and reconnections.

### 6. The Presentation Layer
##### The presentation layer is primarily responsible for translating data from network data to the formats expected by an application. For example, data encodings and encryption are managed at Layer 6.

### 7. The Application Layer
##### The application layer includes protocols designed for end-users. For example, HTTP is a Layer 7 protocol designed to transmit data between a web server and a client.


---

### Socket.IO 
##### is an event-driven library for real-time web applications. It enables real-time, bi-directional communication between web clients and servers. It consists of two parts: a client-side library that runs in the browser, and a server-side library for Node.js. Both components have a nearly identical API.