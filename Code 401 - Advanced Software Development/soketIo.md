# Reading Notes

1. OSI Model: The Open Systems Interconnection (OSI) model describes seven layers that computer systems use to communicate over a network:
  - Physical layer : convert data to 010101
  - Data Link layer : make coding and decoding , Flow control.
  - Network layer : set ip address for sender and receiver and choose for best path to send data.
  - Transport layer :it is responsible for the transfer of data and consists of two protocols UDP and TCP
  - session layer : This layer establishes, maintains, and terminates sessions.
  -  presentation layer: in this layer will occurs compression data, encryption and decryption 
  -  Application layer : The application layer is used by end-user software such as web browsers and email clients. It provides protocols that allow software to send and receive information and present meaningful data to users.


2. Socket.IO is a library that enables low-latency, bidirectional and event-based communication between a client and a server.




3. The bidirectional channel between the Socket.IO server (Node.js) and the Socket.IO client (browser, Node.js, or another programming language) is established with a WebSocket connection whenever possible, and will use HTTP long-polling as fallback.
The Socket.IO codebase is split into two distinct layers:
   - the low-level plumbing: what we call Engine.IO, the engine inside Socket.IO
   - the high-level API: Socket.IO itself

