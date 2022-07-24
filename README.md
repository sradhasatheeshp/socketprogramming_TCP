# socketprogramming_TCP

//ALGORITHM 

//Steps to create a server using TCP/IP API 

1.Create a socket with the socket() system call.

2.Initialize the socket address structure and bind the socket to an address using the bind() system call.

3.Listen for connections with the listen() system call.

4.Accept a connection with the accept() system call. This call typically blocks until a client connects to the server.

5.Receive and send data by using the recv() and send().

6.Close the connection by using the close().


//Steps to create a client using TCP/IP  API

1.Create a socket with the socket() system call.

2.Initialize the socket address structure as per the server and connect the socket to the address of the server using the connect() system call.

3.Receive and send the data using the recv() and send().

4.Close the connection by calling the close() function.
