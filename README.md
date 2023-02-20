# Chatting-Application

Technologies Used: Core Java(Swing, AWT, Socket Programming)

IDE Used: NetBeans

------------------------------------------------------------

This application is a desktop based application and is implemented using Swing and awt. It uses TCP socket communication. Application consists of two programs:

Server and Client

Server
------
The server module of the application waits for the client to connect to it. Then if connection
is granted a client interacts communicates and connects to the server, it can mutually
communicate with the server. The duty of the server is to let clients exchange the messages.

Client
------
The client module is the one that utilizer sends requests to the server. Utilizer utilizes the
client as the means to connect to the server. Once he establishes the connection, he can
communicate to the connected server.

We have a server as well as a client.Both can be run in the same machine or different machines.If both are running in the machine , the adress to be given at the client side is local host address.If both are running in different machines , then in the client side we need to specify the ip address of machine in which server application is running.

Video link for overview of project--
https://youtu.be/iMwB5Tkp_GY
