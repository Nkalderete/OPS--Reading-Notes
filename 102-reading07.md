# **SSH Protocol**

### What is the Secure Shell (SSH) Protocol?

- A method for secure remote login from one computer to another. Provides alternate options for more secure authentication and protects communications security and integrity with strong encrytion.


### What are the typical uses of the SSH protocol?

- Providing secure access for users and automated processes

- Interactive and automated file transfers

- Issuing remote commands

- Managing network infrastructure and other mission-critical system components.


### How does the SSH protocol work?

- The protocol works in the client-server model, which means that the connection is established by the SSH client connecting to the SSH server. The SSH client drives the connection setup process and uses public key cryptography to verify the identity of the SSH server. After the setup phase the SSH protocol uses strong symmetric encryption and hashing algorithms to ensure the privacy and integrity of the data that is exchanged between the client and server.


### How is the data kept safe when transmitted between the SSH client and server?

- Once a connection has been established between the SSH client and server, the data that is transmitted is encrypted according to the parameters negotiated in the setup. During the negotiation the client and server agree on the symmetric encryption algorithm to be used and generate the encryption key that will be used. The traffic between the communicating parties is protected with industry standard strong encryption algorithms (such as AES (Advanced Encryption Standard)), and the SSH protocol also includes a mechanism that ensures the integrity of the transmitted data by using standard hash algorithms (such as SHA-2 (Standard Hashing Algorithm)).


### What is SFTP?

- A  SSH file transfer protocol that is the most widely used secure file transfer protocol today.


# **What is RDP? And how to use it**

### What is Windows Remote Desktop Connection?

- A tool that allows Windows users to connect a remote PC or server over the internet or on a local network, giving access to the tools and software installed on it. 


### What is RDP?

- The Remote Desktop Protocol allows remote users to see and use Windows on a device in another location. Key peripherals like your keyboard and mouse are shared with the remote machine, allowing you to use and control it as if you were sat right in front of it.




### What is the RDP port number?

- TCP 3389