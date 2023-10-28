# Dynamic sessions in the QuickFIXJ server
### Basic setup
The repository contains the example code for the server and client applications uses QuickFIXJ library

Server is running in the dynamic mode, so multiple clients can create sessions. The main exception - Session and Target IDs has to be uniq

To start the example stack execute the next command:
```sh
docker-compose -f docker-compose.yml up -d
```
To stop the stack
```sh
docker-compose -f docker-compose.yml down --volumes
```
