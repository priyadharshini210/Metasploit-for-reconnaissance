# Metasploit-for-reconnaissance
# Metasploit
Metasploit for reconnaissance in pentesting

# AIM:

To get introduced to Metasploit Framework and to  perform reconnaissance  in pentesting .

## DESIGN STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode

### Step 2:

Investigate on the various categories of tools as follows:

### Step 3:

Open terminal and try execute some kali linux commands

## EXECUTION STEPS AND ITS OUTPUT:

Find out the ip address of the attackers system
## OUTPUT:
![Screenshot 2024-10-09 080051](https://github.com/user-attachments/assets/0bb9f805-2b82-41f0-ab4e-b970b417afd5)


## Invoke msfconsole
## OUTPUT:
![Screenshot 2024-10-09 080112](https://github.com/user-attachments/assets/0d38a389-19d4-4477-bef5-a8bc52d217ec)


Type help or a question mark "?" to see the list of all available commands you can use inside msfconsole.
![Screenshot 2024-10-09 080247](https://github.com/user-attachments/assets/e74be904-f7f3-48fd-956c-a3ed8bf5023f)

## Port scanning:
## msf > nmap -sT 192.168.1810/24-p1-1000
![Screenshot 2024-10-09 080300](https://github.com/user-attachments/assets/a680d2d0-a606-4817-9ca7-f047c9c37a3b)

## msf > db_nmap 192.168.181.0/24
![Screenshot 2024-10-09 080311](https://github.com/user-attachments/assets/bed6a696-fd34-4a76-8652-2b82c7513aff)

## kali > ls-l
![Screenshot 2024-10-09 080321](https://github.com/user-attachments/assets/1f2a3620-865c-42ea-9cdc-f7ce3a79688b)

## search 
![Screenshot 2024-10-09 080345](https://github.com/user-attachments/assets/f256119f-9a23-42fe-a52d-b2961d7ae9a5)

## info
![Screenshot 2024-10-09 080427](https://github.com/user-attachments/assets/156b0291-c791-47d8-9ebd-8c504684e362)

## MYSQL ENUMERATION
## db_nmap -sV -sC -p 3306 <metasploitable_ip_address>
![Screenshot 2024-10-09 080441](https://github.com/user-attachments/assets/f0466dc8-b674-46d7-beaa-9264c9e0abd8)

## search
![Screenshot 2024-10-09 080509](https://github.com/user-attachments/assets/b072c856-888d-456b-a055-3c1f8313ff76)

##  use 11 Or: use auxiliary/scanner/mysql/mysql_version
![Screenshot 2024-10-09 080520](https://github.com/user-attachments/assets/6fe5638a-385d-40a0-b304-4b5b6a8675c5)

## Use the set rhosts command to set the parameter and run the module, as follows:
![Screenshot 2024-10-09 080536](https://github.com/user-attachments/assets/8da486ea-da08-404f-b08e-491d41d8b8ba)

## After scanning, you can also brute force MySQL root account via Metasploit's auxiliary(scanner/mysql/mysql_login) module.
![Screenshot 2024-10-09 080550](https://github.com/user-attachments/assets/442c0883-a0a3-462d-9c17-f69ee42d0a00)

## /usr/share/wordlists: set PASS_FILE /usr/share/wordlistss/rockyou.txt 
![Screenshot 2024-10-09 080614](https://github.com/user-attachments/assets/3e4d32ea-f1f4-4d29-a8c3-c62831dc135b)

![Screenshot 2024-10-09 080629](https://github.com/user-attachments/assets/c55275ce-bec9-4cea-ba13-1f30bc84c757)

## RESULT:
The Metasploit framework for reconnaissance is  examined successfully
