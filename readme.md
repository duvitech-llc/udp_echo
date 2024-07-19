# Build

```
gcc udp_client.c -o udp_client
gcc udp_echo_server.c -o udp_echo_server

```

# Run

Open terminal to run the server which will open a UDP server on port 7

```
sudo ./udp_echo_server
```

Open terminal to run the client

```
./udp_client <lwip_device_ip>
```
