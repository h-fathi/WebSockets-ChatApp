# WebSockets-ChatApp
Chat App with WebSockets in ASP.NET Core


This is a chat app developed in order to demonstrate the use of WebSockets for a real-time application. It has a WebSocket middleware implemented in ASP.NET Core and a very simple client in HTML and JavaScript.

The application was developed in ASP.NET Net 5, using MS Visual Studio 2019. Only native libraries are used, since our goal is to demonstrate the low-level functioning of WebSockets.

# Basic functioning
A chat service consists in a server that allows simultaneous connection from different clients for message exchange. Before connecting, the user must choose a unique nickname and then enter a chat room, where they will be able to send and receive messages to other connected users.

# Instructions
Download and build the solution with MS Visual Studio. Open a console window, navigate to the project folder and run command dotnet run. Open file `.\Client\index.html` and use the application. You can open several instances of clients, each one in a different browser tab.

The client is configured to connect to port 58078 in `localhost`; see file `.\Client\index.html`. In case of any troubles, check if server and client are using the same port.
