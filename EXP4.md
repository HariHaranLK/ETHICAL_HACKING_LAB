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
Boot kali and Windows11 virtual machines.
In windows 11 give the command arp -a
### OUTPUT:
![1](https://github.com/HariHaranLK/ETHICAL_HACKING_LAB/assets/132996089/a9ccbd51-db7d-4d35-810d-b29c5d6eda39)

From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>


### OUTPUT:

![image](https://github.com/HariHaranLK/ETHICAL_HACKING_LAB/assets/132996089/8fcd5095-b08c-4dd9-8b40-5ec033bc9779)

###  dsniff:

In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
### OUTPUT:

![image](https://github.com/HariHaranLK/ETHICAL_HACKING_LAB/assets/132996089/49bb7298-af00-4e43-8181-cd4000a27989)


In Kali issue the following commands:
sudo dsnifff
### OUTPUT:

![image](https://github.com/HariHaranLK/ETHICAL_HACKING_LAB/assets/132996089/ec26f1b7-8a64-456a-bd07-332158a7fef1)

Invoke the wireshark and examine the various menus  and controls of the tool:

![image](https://github.com/HariHaranLK/ETHICAL_HACKING_LAB/assets/132996089/b78ad25c-97f7-4e56-b01e-16b0854f94f1)

### RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
