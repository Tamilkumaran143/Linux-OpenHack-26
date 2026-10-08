# Task 3 – Modify Hosted HTML Page from Another Device

## Objective

Modify the custom HTML page hosted on the Linux Nginx server from another device and verify that the changes are reflected on the hosted webpage.

## Server Details

- Server OS: Kali Linux
- Web Server: Nginx
- Server IP: `10.10.145.108`
- Web Server Port: `80`
- Hosted Page: `/var/www/html/index.html`

## Procedure

1. Connected the mobile device to the same network as the Linux server.
2. Accessed the Nginx hosted webpage using:

   `http://10.10.145.108`

3. Enabled SSH access on the Linux server.
4. Connected to the Linux server from another device using SSH.
5. Opened the hosted HTML file:

   ```bash
   sudo nano /var/www/html/index.html

