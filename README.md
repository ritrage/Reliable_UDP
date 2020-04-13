# Reliable_UDP

Computer Networks Assignment 3

Problem Statement =>
You are developing an application which can’t tolerate the growth and shrinking of the TCP congestion
window, but requires reliable delivery. Therefore, you are required to use UDP as the transport
protocol, but build reliability in the application layer.
1. Design your own application layer protocol which uses UDP sockets to transfer packets
between a client and a server (or a P2P setup, your choice). Your protocol should be able to
take care of sequence numbers, acknowledgements, retransmissions, and what ever else is
required to run your application smoothly. You are required to submit a pdf file with your
protocol specification. The specification document should contain the assumptions about the
application, the network, the strategies to tackle different situations in the network, etc.
Maximum length of this document is 2-3 pages, 11 point font for non header text.
2. Write a Java class to implement the protocol you designed. Other Java programs should be able
to instantiate your class and use different methods in the class. Some example methods can be:
1. MyReliableUDPSocket.create()
2. MyReliableUDPSocket.read()
3. MyReliableUDPSocket.write()
4. etc…
You need to submit this java file
3. Write a toy network application in Java (chat, messaging, file transfer, etc.) which uses the class
you designed in the previous step. You can choose your own application, it does not need to be
elaborate, it should be able to use and demonstrate the reliability features of your protocol.
You need to submit this(ese) java file(s)
4. Include a readme.txt file with instructions to compile and run your application
5. Submit a pdf file with plots of the performance of your protocol under different network
conditions. e.g. throughput under various packet loss, delays, reordering, packet corruption
conditions (use the netem tool to emulate different network conditions on your localhost, see
the Evaluation heading below for netem).
