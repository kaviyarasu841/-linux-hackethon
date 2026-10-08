# Task 2 - Nginx Web Server

## Objective

Set up and test an Nginx web server using Ubuntu WSL.

## Tasks Completed

- Installed and configured Nginx.
- Started and verified the Nginx service.
- Configured the web page using index.html.
- Tested the website using curl.
- Configured Windows port forwarding to access the WSL Nginx server.
- Tested the website from Windows.
- Tested the website from a mobile phone.

## Commands Used

```bash
sudo service nginx status
sudo ss -ltnp | grep ':80'
curl http://localhost
hostname -I
