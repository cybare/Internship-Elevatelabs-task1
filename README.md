# Internship-Elevatelabs-task1

## Task 1: Scan Your Local Network for Open Ports

### Objective: 
Learn to discover open ports on devices in your local network to understand network exposure.
### Tools: 
Nmap (free), Wireshark (optional).


### Step 1:-Start the Virtual machine linux 
open the terminal
### Step 2:- find the local ip address 
Use command ifconfig

![Ip address output](Screenshots/Ipconfig.png)

#### IP Address Info:
•	Interface: eth0

•	IP Address: 10.0.2.15

•	Netmask: 255.255.255.0

•	Broadcast Address: 10.0.2.255

Now use ip a command

![Ip range output](Screenshots/iprange.png)

#### IP Range:
• subnet: 10.0.2.0/24

•	Network range: 10.0.2.1 to 10.0.2.254

•	Subnet mask: /24 (or 255.255.255.0)

•	Broadcast address: 10.0.2.255

### Step 3:- Start nmap first scanned own ip.
