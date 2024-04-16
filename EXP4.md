# ARP-Attack-and-Network-Sniffing
# Explore Network Sniffing and ARP Attacks

# AIM:

To explore network sniffing and ARP Attacks

## STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode

### Step 2:

Investigate on the various categories of tools as follows:


### Step 3:
Open terminal and try execute some kali linux commands

## ARP Attacks:  
ARP spoofing: A hacker sends fake ARP packets that link an attacker's MAC address with an IP of a computer already on the LAN. 
Boot kali and Windows7 virtual machines.
In windows 11 give the command arp -a
### OUTPUT:
![1](https://github.com/HariHaranLK/ETHICAL_HACKING_LAB/assets/132996089/a9ccbd51-db7d-4d35-810d-b29c5d6eda39)

From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>


### OUTPUT:

![arpspoof](/image/arpspoof.png)
###  dsniff:

In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
### OUTPUT:

![ftp](/image/ftp.png)


In Kali issue the following commands:
sudo dsnifff
### OUTPUT:

![dsniff](/image/dsniff.png)

Invoke the wireshark and examine the various menus  and controls of the tool:

![wireshark](/image/wireshark.png)
### RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
