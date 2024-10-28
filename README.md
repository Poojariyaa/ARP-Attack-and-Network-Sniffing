# Date:
# Ex-4: ARP-Attack-and-Network-Sniffing
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
In windows 7 give the command arp -a
## OUTPUT:
![Screenshot (235)](https://github.com/user-attachments/assets/04a06e79-3a07-47ac-b05c-4ff99c131f40)


From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:

![image](https://github.com/user-attachments/assets/54b4a3a8-44e2-4765-98b5-6c1ee9aebcc5)


 dsniff:






In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:
![image](https://github.com/user-attachments/assets/99197c22-5bf6-47a2-9c27-fc6b4bf2007f)




In Kali issue the following commands:
sudo dsnifff

## OUTPUT:

![image](https://github.com/user-attachments/assets/689ef697-a235-497d-a223-eb3f78285107)

## Wireshark:
Invoke the wireshark and examine the various menus  and controls of the tool:

## OUTPUT:

![image](https://github.com/user-attachments/assets/cc9f856b-d21a-49ff-a635-b11fdec79fc6)

## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully.
