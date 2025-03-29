# Enumeration
Enumeration Techniques

# Explore Google hacking and enumeration 
```
Register no: 212222040045

```

# AIM:

To use Google for gathering information and perform enumeration of targets

## STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode

### Step 2:

Investigate on the various Google hacking keywords and enumeration tools as follows:


### Step 3:
Open terminal and try execute some kali linux commands

## Pen Test Tools Categories:  

Following Categories of pen test tools are identified:
Information Gathering.

Google Hacking:

Google hacking, also known as Google dorking, is a technique that involves using advanced operators to perform targeted searches on Google. These operators can be used to search for specific types of information, such as sensitive data that may have been inadvertently exposed on the web. Here are some advanced operators that can be used for Google hacking:

site: This operator allows you to search for pages that are within a specific website or domain. For example, "site:example.com" would search for pages that are on the example.com domain.
Following searches for all the sites that is in the domain yahoo.com
![Screenshot 2025-03-29 134547](https://github.com/user-attachments/assets/899bde9a-d8e9-4bcd-a9de-661ec82bd8e6)


filetype: This operator allows you to search for files of a specific type. For example, "filetype:pdf" would search for all PDF files.
Following searches for pdf file in the domain yahoo.com
![Screenshot 2025-03-29 134659](https://github.com/user-attachments/assets/b05c690f-5c2b-4efe-aa3e-5eac6a524ff8)



intext: This operator allows you to search for pages that contain specific text within the body of the page. For example, "intext:password" would search for pages that contain the word "password" within the body of the page.
![Screenshot 2025-03-29 134750](https://github.com/user-attachments/assets/d5de3b91-2349-475b-bd4e-632b89a7a440)


inurl: This operator allows you to search for pages that contain specific text within the URL. For example, "inurl:admin" would search for pages that contain the word "admin" within the URL.
![Screenshot 2025-03-29 134841](https://github.com/user-attachments/assets/06fc42e6-5b57-46eb-b81c-089fa7dc663c)




cache: This operator allows you to view the cached version of a page. For example, "cache:example.com" would show the cached version of the example.com website.
![Screenshot 2025-03-29 140443](https://github.com/user-attachments/assets/cc3fdce8-4b8a-46f4-a70e-2afd64233d0e)

 
#DNS Enumeration


##DNS Recon
provides the ability to perform:
Check all NS records for zone transfers
Enumerate general DNS records for a given domain (MX, SOA, NS, A, AAAA, SPF , TXT)
Perform common SRV Record Enumeration
Top level domain expansion
## OUTPUT:

![WhatsApp Image 2025-03-29 at 13 59 26_2f866f56](https://github.com/user-attachments/assets/2ebfe44b-887f-41cf-8ac8-bd430c9bdbed)






##dnsenum
Dnsenum is a multithreaded perl script to enumerate DNS information of a domain and to discover non-contiguous ip blocks. The main purpose of Dnsenum is to gather as much information as possible about a domain. The program currently performs the following operations:

Get the host’s addresses (A record).
Get the namservers (threaded).
Get the MX record (threaded).
Perform axfr queries on nameservers and get BIND versions(threaded).
Get extra names and subdomains via google scraping (google query = “allinurl: -www site:domain”).
Brute force subdomains from file, can also perform recursion on subdomain that have NS records (all threaded).
Calculate C class domain network ranges and perform whois queries on them (threaded).
Perform reverse lookups on netranges (C class or/and whois netranges) (threaded).
Write to domain_ips.txt file ip-blocks.
This program is useful for pentesters, ethical hackers and forensics experts. It also can be used for security tests.

![WhatsApp Image 2025-03-29 at 13 59 26_d5a75bdb](https://github.com/user-attachments/assets/6f800701-1e21-4f3e-9fc5-459058c54c0e)

##smtp-user-enum
Username guessing tool primarily for use against the default Solaris SMTP service. Can use either EXPN, VRFY or RCPT TO.
![WhatsApp Image 2025-03-29 at 13 59 26_9ef28630](https://github.com/user-attachments/assets/eed5a768-716a-4332-a45f-b63d737d1c93)


In metasploit list all the usernames using head /etc/passwd or cat /etc/passwd:

select any username in the first column of the above file and check the same
![WhatsApp Image 2025-03-29 at 13 59 26_594aab0f](https://github.com/user-attachments/assets/4034b9b9-a228-4f3a-9763-d9576f5a3834)


#Telnet for smtp enumeration Telnet allows to connect to remote host based on the port no. For smtp port no is 25 to connect and issue appropriate commands
  
 ##Output
  ![WhatsApp Image 2025-03-29 at 13 59 26_5fdf6a63](https://github.com/user-attachments/assets/12591f7b-90d4-4964-9448-dd9f1bb84b1e)

  

## nmap –script smtp-enum-users.nse <hostname>

The smtp-enum-users.nse script attempts to enumerate the users on a SMTP server by issuing the VRFY, EXPN or RCPT TO commands. The goal of this script is to discover all the user accounts in the remote system.


## OUTPUT:
![WhatsApp Image 2025-03-29 at 13 59 25_98fbf637](https://github.com/user-attachments/assets/8420cb8f-0910-468f-a61d-98f6415fc71f)


## RESULT:
The Google hacking keywords and enumeration tools were identified and executed successfully

