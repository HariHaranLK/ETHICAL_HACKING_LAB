# InformationGathering
Information Gathering Techiques
```
HARI HARAN L K
212221040051
CSE (III)
```
# To perform information gathering techniques

# AIM:

To perform information gathering techniques using kali linux 

## STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode

### Step 2:

Investigate on the various categories of tools as follows:

### Step 3:
Open terminal/browser and try execute necessary commands/use url to perform information gathering

# Pen Test Tools Categories:  

Following Categories of pen test tools are identified for information gathering:

Footprinting is a part of the reconnaissance process which is used for gathering possible information about a target computer system or network.
http://www.whois.com/whois website to get detailed information about a domain name information including its owner, its registrar, date of registration, expiry, name server, owner's contact information, etc.

## output

![1 whois](https://github.com/HariHaranLK/ETHICAL_HACKING_LAB/assets/132996089/8db34062-09e8-4d89-b0c5-9cf1eedf2962)

# Finding IP address:
ping command is available on Windows as well as on Linux OS. Following is the example to find out the IP address of facebook.com.
## output

![image](https://github.com/HariHaranLK/ETHICAL_HACKING_LAB/assets/132996089/aeb13aaf-aa46-480a-8254-9be33cec0dfd)

# Finding Hosting Company
get further detail by using ip2location.com website.
## output

![3 ip2location](https://github.com/HariHaranLK/ETHICAL_HACKING_LAB/assets/132996089/8c36cbf6-6267-4e37-aecd-6e229720add8)

# History of the website:
```
https://web.archive.org/
```
## output

![4 web archive](https://github.com/HariHaranLK/ETHICAL_HACKING_LAB/assets/132996089/bc8d5267-3942-4e0b-9dc7-785edeceefc0)

# Webserver Fingerprinting:

## Netcat:
sudo nc example.com 80
GET / HTTP/1.1
Host: example.com
## output

![5 nc command](https://github.com/HariHaranLK/ETHICAL_HACKING_LAB/assets/132996089/e80301ec-c5f4-4bb9-bd2f-0480d7ec2c4d)

## nmap:
## #output

![6 nmap](https://github.com/HariHaranLK/ETHICAL_HACKING_LAB/assets/132996089/d191d6e3-005d-438f-90aa-c97794b2e3d1)

# Whatweb
## output

![7 whatweb](https://github.com/HariHaranLK/ETHICAL_HACKING_LAB/assets/132996089/ae56c986-cbf2-4367-8d4a-f6cc49a23de4)

# httprint
## output

![8 httprint](https://github.com/HariHaranLK/ETHICAL_HACKING_LAB/assets/132996089/d8c34241-4036-469f-a7ff-ce8f6eabf26a)

# Tracing the Location
TCP Traceroute:
sudo traceroute -T www.google.com
## output

![9 tcp traceroute](https://github.com/HariHaranLK/ETHICAL_HACKING_LAB/assets/132996089/83b41159-bb32-4407-8e02-c56b7dc148bc)

# UDP Traceroute:
sudo traceroute -U www.google.com
## output

![9 udp traceroute](https://github.com/HariHaranLK/ETHICAL_HACKING_LAB/assets/132996089/99364561-8bbe-4d5a-b8d3-06f51a66f291)

# ICMP Traceroute:
sudo traceroute  www.google.com
## output

![9 ICMP traceroute](https://github.com/HariHaranLK/ETHICAL_HACKING_LAB/assets/132996089/69fcc942-e9ec-4bd3-aea1-116f5b938afa)

# Netcraft
## output

![10 netcraft](https://github.com/HariHaranLK/ETHICAL_HACKING_LAB/assets/132996089/6f2f02ad-cbfa-442b-806d-b0b136bd89a7)

# Wapplyzer
## output

![11 wappalyzer](https://github.com/HariHaranLK/ETHICAL_HACKING_LAB/assets/132996089/559bd9da-e837-41d8-90ba-a69442632681)

## RESULT:
The information gathering techniques tools/procedure were  identified successfully
