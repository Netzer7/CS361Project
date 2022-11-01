# CS361Project

# Microservice

## How to request data
The user requests data by calling the Client.js when they click on the page that uses the Microservice. That then creates a socket for the server.js file to talk to the client. 
## How to receive data
The user revives data from the client.js it then tells the server to send the data over by sending its own message. The client then awaits the data with sock.receive() then when the data is received it outputs it by turning it into a string with variableName.toString().  

## UML sequence Diagram
![UML](https://user-images.githubusercontent.com/110203117/199165853-32e64d5b-d691-4494-bd92-47ce09ed7d18.png)
