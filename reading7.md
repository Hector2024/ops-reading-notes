# Hectors Reading notes

## Ops Readings

### Reading #7

SSH Protocol

1. What is the Secure Shell (SSH) Protocol?

- SSH protocol is used so that you can securely remote into a computer over the web.

2. What are the typical uses of the SSH protocol?

- "providing secure access for users and automated processes" (SSH, 1996)

- "interactive and automated file transfers" (SSH, 1996)

- "issuing remote commands" (SSH, 1996)

- "managing network infrastructure and other mission-critical system components." (SSH, 1996)

3. How does the SSH protocol work?

-It has a server and a client. The computer reaches out to the server using a "public key" to make sure its talking to the server, then they make or agree upon a mutual "key". Once that happens the protocol protects the traffic between the client and server.

4. How is the data kept safe when transmitted between the SSH client and server?

- Before the the client and the server are connected they agree "on the symmetric encryption algorithm to be used and generate the encryption key that will be used." (SSH, 1996) and the protocal also protects the transmission using hash algorithms.

5. What is SFTP?

- SFTP is SSH's file transfer protocol



What is RDP? And how to use it

1. What is Windows Remote Desktop Connection?

- Remote desktop connection is a tool made for windows that helps us remote into another computer.

2. What is RDP?

- RDP is a windows specific protocol that supports their remote desktop connection tool.

3. What is the RDP port number?

- "TCP/UDP port 3389" (comparitech, 2023)

## Things I want to know more about

- How did we get Windows to work with Linux since it's a windows only program
- Why that specific port number?
- How can we remotley turn on a machine?

## Resources

https://www.ssh.com/academy/ssh/protocol
(general information and quoted for readings)

https://www.comparitech.com/net-admin/what-is-rdp/
(general information and quoted for readings)

https://chat.openai.com/c/97bc976b-6438-4c98-93ff-6a7de8fe9bcc
(used to understand SSH Protocol)
Conversation with ChatGPT 

- ME: what is SSH protocol

- ChatGPT: SSH stands for Secure Shell, and it's a protocol used for securely connecting to and communicating with remote computers over an unsecured network, like the internet. It provides a secure way to access and manage remote devices or servers. Here are some key aspects of the SSH protoco
