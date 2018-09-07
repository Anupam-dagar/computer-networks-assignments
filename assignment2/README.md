# Assignment 2

Check respective question folder for running instructions.

## Ques 1
Write a simple client-server program that uses stream socket and provides chat
facility. Your application allows a user on one machine to type in and send text to a
user on another machine.

## Ques 2
a. Create three programs, two of which are clients to a single server using datagram
socket. Client1 will send a character to the server process. The server will
decrement the letter to the next letter in the alphabet and send the result to client2.
Client2 prints the letter it receives and then all the processes terminate. Compile
and run this exercise.  

b. Send a C structure that includes data of type character, integer and float from
client1 to the server. The server should change the values so that client2 receives
a structure with entirely different data. It is not permitted that the data should be
converted to any other data type before transmission.

## Ques 3
You need to build a very simple client-server operation using the Stream capabilities.
You are to build a client and server pair, to implement your own little directory
service. Suppose that the server has the following database:

0 Bob  
3 Anne  
5 Barb  
7 Ray  
9 Denbigh  
10 Terri  
104 John

This can be in a file that is read. The client is to read a request, which is a numeric
address to be sent to the server. The servers look up the matching name and send it
back to the client to be printed out. If the address isn't found, the server should send
back an error message. For example, "Address not found".