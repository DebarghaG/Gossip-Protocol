# Gossip-Protocol
Simple version of gossip protocol enhancing fault tolerance and scalability. 

It has a parent class namely Gossip which is responsible of all the work. 
It uses fundamental concepts of Socket programming, UDP(DGRAM) has been used to send(sendto) and recieve(recvfrom) data 
from different nodes that are the base classes of this Gossip namely Nodexyz.
In this way, it uses Object Oriented features of creating multiple instances of something with common properties. 
For continuously receiving and sending data between different nodes, two threads have been used, which makes this 
project make use of some concept of multithreading as well. 
And it has been coded in Python 3,
Python 3 is good for algorithmic purpose and it has good readability as well.
Easy to understand. 
