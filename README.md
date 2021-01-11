# UDP-Socket-Communication-P1

Develop two small network applications used the so-called Berkeley Socket APIs to send and receive UDP datagrams.  The project produces two network programs named, sender and receiver, that send and receive data through the network.  The P1 code will be vulnerable to lost, duplicate, out-of-order delivery, and overrun issues.

You could paste any words into the send.txt ffile. 
Send.txt might need to be updated or changed in sender.c file
to any .txt file you wish, and then the words inside of the .txt file 
will be transfered to recieve.txt. The recieve.txt file replaces the words
everytime you run.

To compile
1. gcc sender.c -o sender
2. gcc receiver.c -o receiver

To run
run from receiver, then run sender. Reciever will response you. 
./receiver 4547
./sender localhost 4547
