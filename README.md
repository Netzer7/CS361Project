# CS361 Project

# Microservice

## How to request data
The user requests job data by calling the Client.js when they click on the page that uses the Microservice. That then creates a socket for the server.js file to talk to the client. The client first displays "Connecting to the server", then "Sending data request" indicating that server connection was successful and the request has been sent to the server. 
## How to receive data
The user clicks the page client.js then tells the server to send the job data over by sending its own message with sock.send(). The client then awaits the job data with sock.receive() then the server uses sock.send() to send the data over. The job data is received and is then output after turning it into a string with msg.toString().  The corresponding object can be used within the users program to be displayed as a table, containing the job listings company, position and salary. 

## UML sequence Diagram
![UML](https://user-images.githubusercontent.com/110203117/199165853-32e64d5b-d691-4494-bd92-47ce09ed7d18.png)
