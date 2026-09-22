
# Lab 01 – Linux Network Troubleshooting

## Objective
Build an Ubuntu Server virtual machine and practice a systematic approach to troubleshooting network connectivity using Linux networking commands.

## Lab Environment
- Ubuntu Server 24.04 LTS
- Oracle VirtualBox
- VirtualBox NAT networking
- Network interface: `enp0s3`
- IPv4 address: `10.0.2.15/24`
- Default gateway: `10.0.2.2`

## Commands Practiced

### 1. Check IP Configuration
```bash
ip addr show

### 2. Check Routing
bash
ip route

### 3. Test Default Gateway
bash
ping  -c 4 10.0.2.2

### 4. Test Internet COnnectivity
bash
ping  -c 4 8.8.8.8

### 5. Test DNS Resolution
bash
ping  -c 4 google.com

### 6. Examine the neighbor table
bash
ip neigh

### 7. Trace the Network Path
bash
traceroute 8.8.8.8


