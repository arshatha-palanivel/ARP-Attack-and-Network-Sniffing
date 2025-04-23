
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
![428030469-86376566-6fad-4ff2-bd9d-763cc6ef6946](https://github.com/user-attachments/assets/6e467586-4f2f-4a3f-a15c-417a00e48e3e)


From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
![428030422-c7f878e5-4790-4a07-9db2-081a0645b6e7](https://github.com/user-attachments/assets/aa876cd1-dcd8-4827-8345-780f3e1792f6)

## OUTPUT:



 dsniff:


![428030167-44c9610a-c75d-40d9-a5b8-1c1130e02d8c](https://github.com/user-attachments/assets/d30a73c5-ec2e-4b02-8041-5658ffdff582)




In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:


![428030083-c59cdb52-5e51-41b4-a457-2489ad74c0a2](https://github.com/user-attachments/assets/535942a0-0a9f-418f-9a7a-d638a6334e28)



In Kali issue the following commands:
sudo dsnifff
## OUTPUT:

![428029855-f4ea961b-c176-467d-9d06-5f84386cd993](https://github.com/user-attachments/assets/daab3004-fc78-491c-99e9-01f1d254d624)



Invoke the wireshark and examine the various menus  and controls of the tool:

![428029676-d6bbf7f6-dd07-4024-b0cc-82e3d625b755](https://github.com/user-attachments/assets/dfb5a916-50f0-477a-a27d-d1636a6d0291)

## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
