# CS361Project

# Microservice

## How to request data
The user requests data by calling the Client.js when they click on the page that uses the Microservice. That then creates a socket for the server.js file to talk to the client. 
## How to receive data
The user clicks the page client.js  then tells the server to send the data over by sending its own message with sock.send(). The client then awaits the data with sock.receive() then the server uses sock.send() to send the dataover. Then when the data is received it outputs it by turning it into a string with variableName.toString(). Then able to use for the page. 

## UML sequence Diagram
![UML](https://user-images.githubusercontent.com/110203117/199165853-32e64d5b-d691-4494-bd92-47ce09ed7d18.png)
