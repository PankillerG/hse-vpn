# Simple OpenVPN Server Script
### Requirements
This script tested and works properly on **Ubuntu 18.04**
### Installation
Run the following commands as root:
```bash
sudo apt update
sudo apt install git
https://github.com/PankillerG/hse-vpn
./hse-vpn/setup.sh
```
### Usage
Start, stop and restart server:
```bash
restart_openvpn
start_openvpn
stop_openvpn
```
Create OpenVPN client:
```bash
create_openvpn_user username
```
This script creates a file named username.ovpn