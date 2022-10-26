# 300 - Building our Application

Based on "Hetzner Cloud Documentation" at https://docs.hetzner.com/cloud/

## 100 - Servers

### Server Types:

**Standard**

- For best performance, hypervisors are used to distribute usage rights of CPU resources among several virtual servers
- Ideal for individual applications or development environments

|Name|vCPUs|Ram|SSD|Traffic|Price per hour*|Price per month*|
|--|--|--|--|--|--|--|
|CX11|1 Intel|2 GB|20 GB|20 TB|€ 0.0052 / h|€ 3.29 / mo| 

\* All prices excl. VAT

## 200 - Internet Protocol (IP) Addresses

Cloud servers do not have a public network interface unless at least one Primary IP is assigned to them. 

Both resources can be managed independently. 

- This means that it is possible to create Primary IPs without assigning them to a cloud server. 
- And you can create cloud servers with or without assigning public IP addresses (Primary IPs) to them.

Hetzner does not charge for their Primary IPv6s, up to 1 Primary IPv6 per server.

## 200 - Networks

## 300 - Volumes

## 400 - Load Balancers

