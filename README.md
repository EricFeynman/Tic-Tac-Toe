# Multiplayer Tic-Tac-Toe

A Multiplayer Tic-Tac-Toe game written in C++ based on the client-server model using the basics of socket programming.

## Installation and Setup

### Server (Player 1)

1. Compile the server:

    ```bash
    g++ server.cpp -o server.out
    ```

2. Run the server:

    ```bash
    ./server.out
    ```

### Client (Player 2)

1. Compile the client:

    ```bash
    g++ client.cpp -o client.out
    ```

2. Run the client, specifying the server's IP address:

    ```bash
    ./client.out <Server_IP_Address>
    ```

Replace `<Server_IP_Address>` with the actual IP address of the server.

## Notes

- Ensure that the server is set up before connecting the client.

## Find Your IP Address in Linux

To find your IP address in Linux, you can use several commands. Here are a few of them:

- Use the `hostname` command to display the local IP address:

    ```bash
    hostname -I
    ```

- Use the `ifconfig` or `ip` command to show information about network interfaces, including IP addresses:

    ```bash
    ifconfig
    ```

    or

    ```bash
    ip addr show
    ```

- Use the `curl` command to get your external IP address:

    ```bash
    curl ifconfig.me
    ```

Make the necessary changes to the code according to your needs and enjoy playing Tic-Tac-Toe with your friends!
