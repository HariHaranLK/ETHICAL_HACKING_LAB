# creating-a-backdoor-with-SET
creating a backdoor with SET - Ethical Hacking Techniques course

# AIM:
To Create a backdoor with Social Engineering Toolkit (SET)

## DESIGN STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode


### Step 2:

Investigate on the various categories of tools as follows:

### Step 3:

Open terminal and try execute some kali linux commands

## EXECUTION STEPS AND ITS OUTPUT:
Social Engineering attacks are the various cons used by the hackers to trick people into providing sensitive data to the attackers. 
The command sudo setoolkit in the prompt gives menu with set prompt:

 ![image](https://github.com/1808charitha/creating-a-backdoor-with-SET/assets/132996838/ef7b25b6-a477-4153-8066-5df532c07688)
 It displays the following menu and select 2 for Website Attack Vectors:
 ![image](https://github.com/1808charitha/creating-a-backdoor-with-SET/assets/132996838/cf29526b-3edc-4f4d-afa4-27926c2f1f24)
 The website Attack Vectors displays the following menu. In this menu3 for Credential Harvester Attack Method is selected:
 ![image](https://github.com/1808charitha/creating-a-backdoor-with-SET/assets/132996838/45904ce1-8f75-46a2-9591-26748dca14ca)
 The Credential Harvester Attack Method displays the following menu. In this menu1 for Web Templates is selected:
 ![image](https://github.com/1808charitha/creating-a-backdoor-with-SET/assets/132996838/017d7cc5-e8bf-4bbf-a989-a98446ed662a)
 It shows the following screen in which the ip address of the attacker need to be given which is the default value:
 ![image](https://github.com/1808charitha/creating-a-backdoor-with-SET/assets/132996838/12696ddd-643e-4d84-ad46-51ca12acc8b7)
 It shows the following screen in which the option Google can be selected:
 ![image](https://github.com/1808charitha/creating-a-backdoor-with-SET/assets/132996838/847305a1-96a5-40c0-82b7-9618558faeee)
 SET starts my Kali Linux Webserver on port 80, with the fake Google account login page. The setup is done:
 ![image](https://github.com/1808charitha/creating-a-backdoor-with-SET/assets/132996838/e03cbefa-1ed1-4158-86e6-4ac20056236a)
 In windows IE, on giving the url http://192.168.1.2, the fake Google page is displayed. The victim can enter the username and password 
 ![image](https://github.com/1808charitha/creating-a-backdoor-with-SET/assets/132996838/3d4153f4-67e6-408f-898f-b7f636c970cc)
 SET logs the information regarding the Google credentials:
 ![image](https://github.com/1808charitha/creating-a-backdoor-with-SET/assets/132996838/0d07b841-bc07-40cd-9bd7-f79aed210989)
 SET logs the information in the xml file under /root/.set directory:
 ![image](https://github.com/1808charitha/creating-a-backdoor-with-SET/assets/132996838/a9160ebe-7b63-45f6-a059-f59375153548)
















## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is  examined successfully
