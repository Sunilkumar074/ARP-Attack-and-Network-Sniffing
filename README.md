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
![1](https://github.com/user-attachments/assets/d581d450-7a54-45d2-9aab-187c76761a0e)


From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:
![2](https://github.com/user-attachments/assets/e1f4986a-7a0d-444c-8e41-4a9434a0a771)


 dsniff:


![3](https://github.com/user-attachments/assets/3fd11623-ce68-4e39-813f-20405c7c0732)





In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:

![4](https://github.com/user-attachments/assets/c81139e2-9aec-441d-a74d-e6abd9618872)



In Kali issue the following commands:
sudo dsnifff
## OUTPUT:

![5](https://github.com/user-attachments/assets/41c15480-075d-4d18-916b-d163e2021aaa)


Invoke the wireshark and examine the various menus  and controls of the tool:


## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
