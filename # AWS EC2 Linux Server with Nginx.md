# AWS EC2 Linux Server with Nginx

## Project Overview

Deployed and configured an Ubuntu Linux server using AWS EC2 and hosted an Nginx web server.

## What I Completed

- Created an Ubuntu EC2 instance
- Connected to the server using SSH
- Worked with Linux CLI commands
- Managed files and permissions
- Checked users and groups
- Managed processes and services
- Configured SSH access
- Configured AWS Security Groups
- Configured HTTP port 80
- Installed and configured Nginx
- Verified Nginx service status
- Tested Nginx using curl
- Accessed Nginx through the EC2 public IP

## Architecture

Laptop
↓
Internet
↓
AWS EC2
↓
Ubuntu Linux
↓
Nginx
↓
HTTP Port 80
↓
Web Browser

## Verification

Nginx service:

```bash
sudo systemctl status nginx