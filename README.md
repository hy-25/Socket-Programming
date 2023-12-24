# Bank Management System


Bank Management System
This repository contains a simple implementation of a Bank Management System with a server-client architecture. It includes two files: one for the server-side (server.c) and one for the client-side (client.c).

# Server
### Execution
gcc server.c -o server
./server


# Client
### Execution
gcc server.c -o server
./server

The server listens for incoming connections on port 28223.

### Description
The server handles multiple client connections and performs various banking operations based on user authentication.

## Key functions include:

- ministat: Retrieves the mini statement for a given customer.
- Alldet: Retrieves details of all customers.
- update: Updates the balance for a customer.
- getBAL: Retrieves the current balance for a customer.
- usr: Handles user operations.
- plc: Handles police operations.
- adm: Handles admin operations.
- othenticate: Authenticates users based on login credentials.
- talk: Manages the communication between the server and clients.

### Compilation and Execution
gcc client.c -o client
./client


The client interacts with the server and performs operations based on user input. It supports user, police, and admin roles with functionalities such as mini statements, balance enquiries, and updates.
