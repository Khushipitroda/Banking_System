# Banking_System
Banking Managment System using Socket Programming


## How to Run
* Compile the server and client
```
gcc serverside.c -o server

gcc clientside.c -o client
```
* Run the server in one terminal instance with the port as the first argument
```
./server $PORT
```
* Run the client in a different terminal tab with the IP and port of the server instance as its arguments.
```
./client $IP $PORT
```
For local debug environment IP = 127.0.0.1
* Create a login credentials file named ***login_file***. The format of an example *login_file* is given below
```
Customer1 Pass1 C
Customer2 Pass2 C
Admin Admin A
Police Police P
```
The format is 
```
$USERNAME $PASSWORD $AUTH_TYPE
```
where AUTH_TYPE can be **A** for admin, **P** for police and **C** for customers.

