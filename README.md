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
![image](https://github.com/R-Guruprasad/ARP-Attack-and-Network-Sniffing/assets/119390308/54621280-8467-4238-91b0-2f5765f56741)

From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:
![image](https://github.com/R-Guruprasad/ARP-Attack-and-Network-Sniffing/assets/119390308/b5863439-8961-4b2b-823c-ea357d6efaf5)

 dsniff:
 In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:
![image](https://github.com/R-Guruprasad/ARP-Attack-and-Network-Sniffing/assets/119390308/e1f40f91-3159-4fa3-aaa6-62bd56b48b17)

Invoke the wireshark and examine the various menus  and controls of the tool:
## OUTPUT:

![image](https://github.com/R-Guruprasad/ARP-Attack-and-Network-Sniffing/assets/119390308/eb8a711a-807d-42fd-b6fb-a56a6422b711)

## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
