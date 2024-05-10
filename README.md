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
![image](https://github.com/danush564/ARP-Attack-and-Network-Sniffing/assets/98585166/6efd9ac0-30d9-4336-83ee-4e948da44a21)

From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>


### OUTPUT:

![image](https://github.com/danush564/ARP-Attack-and-Network-Sniffing/assets/98585166/d48deec5-d5c4-482d-b81a-c969cff395c6)

###  dsniff:

In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
### OUTPUT:

![image](https://github.com/danush564/ARP-Attack-and-Network-Sniffing/assets/98585166/a1b596d3-b7f2-40b5-8daf-12fef164600c)


In Kali issue the following commands:
sudo dsnifff
### OUTPUT:

![image](https://github.com/danush564/ARP-Attack-and-Network-Sniffing/assets/98585166/2fbdd64e-e2ee-4933-8241-1e075a132ccb)

Invoke the wireshark and examine the various menus  and controls of the tool:

![image](https://github.com/danush564/ARP-Attack-and-Network-Sniffing/assets/98585166/2f7bbd57-921e-40a5-96da-2d4b7d42cba8)

### RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
