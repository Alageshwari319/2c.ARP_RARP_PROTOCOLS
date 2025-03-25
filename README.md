# 2c.SIMULATING ARP /RARP PROTOCOLS
## AIM
To write a python program for simulating ARP protocols using TCP.
## ALGORITHM:
## Client:
1. Start the program
2. Using socket connection is established between client and server.
3. Get the IP address to be converted into MAC address.
4. Send this IP address to server.
5. Server returns the MAC address to client.
## Server:
1. Start the program
2. Accept the socket which is created by the client.
3. Server maintains the table in which IP and corresponding MAC addresses are
stored.
4. Read the IP address which is send by the client.
5. Map the IP address with its MAC address and return the MAC address to client.
P
## PROGRAM - ARP

Client:

![image](https://github.com/user-attachments/assets/7ac7baef-8822-4a66-be40-c20119f68e3b)

Server:

![image](https://github.com/user-attachments/assets/0dfa4e5f-03fb-4077-b021-246bee9f9e67)

## OUPUT - ARP

Client:

![image](https://github.com/user-attachments/assets/70978d4b-3845-48a0-9122-997719c57ed5)

Server:

![image](https://github.com/user-attachments/assets/419914f5-3153-46f1-b08d-b36630608fcb)


## PROGRAM - RARP

Client:

![image](https://github.com/user-attachments/assets/25b40aa9-9a83-41bc-8c76-baa7af5d708a)

Server:

![image](https://github.com/user-attachments/assets/90ce5fe9-832e-4fca-a0bb-e7042c3ab178)

## OUPUT -RARP

Client:

![image](https://github.com/user-attachments/assets/0dbe1fb3-5335-40e2-b5a3-b9c176e81a1a)

Server:

![image](https://github.com/user-attachments/assets/fc8760db-507f-4633-b0aa-d888a36d0bc8)


## RESULT
Thus, the python program for simulating ARP protocols using TCP was successfully 
executed.
