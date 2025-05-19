# chat-application-caeser-cipher
This project implements a secure chat system consisting of a server and a client application. It uses the Caesar Cipher encryption technique to transmit messages securely over a network. Both server and client applications are built using Python and feature a graphical user interface (GUI) for seamless interaction.
# Features
General
Secure Communication: Messages are encrypted and decrypted using Caesar Cipher with a shift value of 3.
Concurrent Messaging: Allows simultaneous sending and receiving of messages using threading.
GUI Interface: User-friendly graphical interface built with Tkinter.
Message Logs: Displays original, encrypted, and decrypted messages.
Server-Specific
Server Setup: Host the chat server by entering an IP address and port.
Handles Client Connections: Waits for a client to connect and starts secure communication.
Client-Specific
Connect to Server: Join the chat server using the provided IP address and port.
User Identification: Allows users to set their username for personalized interaction.
# Prerequisites
Python 3.x
Required Python libraries:


# Installation
Clone the repository:

git clone https://github.com/yourusername/encrypted-chat-app.git
cd encrypted-chat-app
Ensure Python 3.x is installed on your machine.

Run the server and client scripts in separate terminals.
