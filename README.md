# MultipleClient-ServerChat

## Server:
Compile with: g++ Server.cpp -o server
Execute with: ./server 1234
here 1234 is <desired port number>
Sender Thread actively looks for the messages to be sent.
Send Message to Client  : <clientID> <message>
View active clientIDs   : show


## Client:
Compile with: g++ Client.cpp -o client
Execute with: ./client 127.0.0.1 1234
here 127.0.0.1 is <the Server IP Address>
  you can view your IP Address with command: hostname -I
here 1234 is <desired port number>
Send Message to other Client  : <clientID> <message>
Send Message to Server        : <message>
View active clientIDs         : online
