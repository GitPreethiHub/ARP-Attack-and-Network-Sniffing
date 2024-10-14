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
In windows 7 give the command arp -a
## OUTPUT:
![image](https://github.com/user-attachments/assets/6390f175-69ec-47c3-b9cc-23493d165f08)

From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:
![image](https://github.com/user-attachments/assets/46bd453a-9cdd-40b6-8389-49373cb04c55)


 dsniff:

![image](https://github.com/user-attachments/assets/049338e6-4a34-417a-aece-ec422076adee)





In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:




In Kali issue the following commands:
sudo dsnifff
## OUTPUT:



Invoke the wireshark and examine the various menus  and controls of the tool:


## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
