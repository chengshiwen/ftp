linux-ftp
=========

A simple ftp software including server and client in Linux operating system


## Usage

1. start ftp server (default host: 127.0.0.1) <br>
```
gcc -o ftp_server ftp_server.c
```<br>
```
./ftp_server <port>
```
2. start ftp client <br>
```
gcc -o ftp_client ftp_client.c
```<br>
```
./ftp_client <host> <port>
```

## Client commads

```
get     get a file from server.
put     send a file to server.
pwd     get the present directory on server.
dir     list the directory on server.
cd      change the directory on server.
?/help  help to know how to use the commands.
quit    quit client.
```
