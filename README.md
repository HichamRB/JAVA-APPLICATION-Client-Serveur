# JAVA-APPLICATION-Client-Serveur

The goal of this project is to become familiar with the use of Threads, Sockets, and Java RMI, and developing a Client/Server application based on these tools.
The requested application consists in creating services on several machines (servers) and making them accessible to clients either by Java RMI or by sockets. Each time a client requests a service from a server, a thread will be created to deal with this client and respond to its request.
To illustrate the idea of this project, consider the image processing domain where a user (customer) wishes to apply several filters in parallel to an original image. To do this, it sends this original image to servers so that each of them applies the desired filter in parallel. The example below presents a client i which solicits 4 servers in order to receive 4 different results from its filtered image.
