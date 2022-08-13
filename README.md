# POS-Socket-Proramming
Implementation of POS (Point of Sale) Transaction using socket programming and capturing and analyzing the packets using Wireshark.
The server is located at a constant IP address. The connection between the client and server is a simple one. UDP is chosen as the transport layer protocol as it is faster than TCP and the data sent over the network is less. Based on the client input the server extracts the necessary data from a CSV file (database.csv) and performs the transaction. The client is reading the UID from serial monitor and transmits it to the server for verification.

Refer client.py and socket.py for the socket programming codes and refer rfid.ino for interfacing the RFID tags with the the microcontroller board and the client and server networks.
