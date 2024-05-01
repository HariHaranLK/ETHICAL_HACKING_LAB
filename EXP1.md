# EX.No : 1 Simple echo server and client using Python socket
## DATE : 17/02/2024
## REG NO : 212221040051

# Echoserver
Echo server and client using python socket

# AIM:
To develop a simple webserver to serve html programming pages.

## DESIGN STEPS:

### Step 1:

Design of echo server and client using python socket

### Step 2:

Implementation using Python code

### Step 3:

Testing the server and client 
<br><br><br><br><br><br><br><br><br>
## PROGRAM:
### SERVER CODE
```
#echo-server.py
import socket
HOST = "127.0.0.1"  # Standard loopback interface address (localhost)
PORT = 65432  # Port to listen on (non-privileged ports are > 1023)
with socket.socket(socket.AF_INET, socket.SOCK_STREAM) as s:
    s.bind((HOST, PORT))
    s.listen()
    conn, addr = s.accept()
    with conn:
        print(f"Connected by {addr}")
        while True:
            data = conn.recv(1024)
            if not data:
                break
            conn.sendall(data)
```
### CLIENT CODE
```
# echo-client.py
import socket
HOST = "127.0.0.1"  # The server's hostname or IP address
PORT = 65432  # The port used by the server
with socket.socket(socket.AF_INET, socket.SOCK_STREAM) as s:
    s.connect((HOST, PORT))
    s.sendall(b"Hello, world")
    data = s.recv(1024)
print(f"Received {data!r}")
```
<br><br><br><br><br><br><br><br><br><br><br><br>
## OUTPUT:
### SERVER OUTPUT
![serv](https://github.com/HariHaranLK/ETHICAL_HACKING_LAB/assets/132996089/5ad1e211-f275-4497-b3a2-dd83cd40bbf7)
### CLIENT OUTPUT
![clie](https://github.com/HariHaranLK/ETHICAL_HACKING_LAB/assets/132996089/dd61c636-79db-4c5a-93f7-3a02c253a4f9)
<br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br>
## RESULT:
The Simple Echo Server and Client Using Python Socket is created, executed and output is verified successfully.
