# Remote-Code-Publisher
This project builds a communication mock channel between the server and clients using sockets.

## Communication Channel
Both server and clients share the same structure: contains a Receiver, a Sendr and a independent part to process messages

Receiver and Sendr only deal with HTTP messsage and file transmission

## Server
Server can deal with file uploading from clients, performing dependency analysis regarding source files, publishing html files regarding source file contents

## Client
Provide client GUI for users, which contains all operations for this system

Client has access to upload source files, browse visible contents of server's repository, select web pages to display by browser and delete published web pages
