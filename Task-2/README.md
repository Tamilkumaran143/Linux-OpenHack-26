# Task 2: Access the Hosted HTML Page from Another Computer

## 1. Objective

The objective of this task is to access the custom HTML page hosted on the Nginx web server from another computer connected to the same network.

In Task 1, the Nginx web server was configured on the Linux machine and the custom HTML page provided by the organizers was successfully hosted.

In this task, the same hosted HTML page is accessed remotely from another computer using the network IP address of the Linux machine.

This verifies that the Nginx server is not only accessible locally but can also serve the hosted webpage to another computer on the same network.

---

## 2. Network Setup

The task was performed using two computers connected to the same network.

### Server Computer

The Linux machine acts as the server.

It contains:

- Nginx web server
- Custom HTML page
- Network IP address
- HTTP service running on port 80

### Client Computer

The second computer acts as the client.

It is used to access the HTML page hosted on the Linux machine through a web browser.

The basic communication flow is:

Client Computer
        |
        | HTTP Request
        |
        v
Linux Server
        |
        v
Nginx Web Server
        |
        v
Custom HTML Page
        |
        v
Client Browser

---

## 3. Finding the Linux Machine IP Address

First, the IP address of the Linux machine was identified.

The following command was executed:

```bash
hostname -I
