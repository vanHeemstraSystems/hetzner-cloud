# 300 - Building our Application

Based on "Hetzner Cloud Documentation" at https://docs.hetzner.com/cloud/

## 100 - Servers

See [README.md](./100/README.md)

## 200 - Internet Protocol (IP) Addresses

Cloud servers do not have a public network interface unless at least one Primary IP is assigned to them. 

Both resources can be managed independently. 

- This means that it is possible to create Primary IPs without assigning them to a cloud server. 
- And you can create cloud servers with or without assigning public IP addresses (Primary IPs) to them.

Hetzner does not charge for their Primary IPv6s, up to 1 Primary IPv6 per server.

## 200 - Networks

## 300 - Volumes

See also "Rclone" at https://github.com/rclone/rclone

See also "Managing Multiple Cloud Remotes with Rclone" at https://community.hetzner.com/tutorials/rclone-basics

Rclone ("rsync for cloud storage") is a command-line program to sync files and directories to and from different cloud storage providers.

NOTE: We could connect from Hetzner Cloud to and from our home volumes to be synched.

## 400 - Load Balancers

## 500 - Backups

## 600 - Snapshots

## 700 - Placement Groups

## 800 - Names

## 900 - Labels
