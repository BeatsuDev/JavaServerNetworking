# Connecting to TCP Server
You can use telnet for TCP connections.

`Server Terminal:`
    javac Server.java
    java Server

`Client Terminal:`
    telnet 127.0.0.1 1234

# Connecting to TCP WebServer
`Server Terminal:`
    javac WebServer.java
    java WebServer

Go to http://127.0.0.1:1234 in your web browser.

# Connecting to UDP Server
You can use netcat for UDP connections.

`Server Terminal:`
    javac ServerUDP.java
    java ServerUDP

`Client Terminal:`
    nc -u 127.0.0.1 1234