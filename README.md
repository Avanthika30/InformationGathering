# Ex-02 InformationGathering
Information Gathering Techiques

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

## Architecture Diagram
```
                      +-------------------------+
                      |     Attacker System     |
                      |     (Kali Linux)        |
                      +-----------+-------------+
                                  |
                                  | Terminal / Browser
                                  | Executes Recon Tools
                                  v
      +------------------- Passive Recon --------------------+
      |                                                     |
      |  +----------------+     +------------------------+  |
      |  |   WHOIS Query  | --> |    Domain Registrars    |  |
      |  +----------------+     +------------------------+  |
      |                                                     |
      |  +----------------+     +------------------------+  |
      |  |   DNS Enum     | --> |     Public DNS Servers  |  |
      |  +----------------+     +------------------------+  |
      |                                                     |
      +-----------------------------------------------------+

                                  |
                                  v

      +------------------ Active Recon ----------------------+
      |                                                     |
      |  +----------------+     +------------------------+  |
      |  |   Nmap Scan    | --> |  Target Host/Network    |  |
      |  +----------------+     +------------------------+  |
      |                                                     |
      |  +----------------+     +------------------------+  |
      |  | WhatWeb, Wapp | --> |   Target Web Application |  |
      |  +----------------+     +------------------------+  |
      |                                                     |
      |  +----------------+     +------------------------+  |
      |  | theHarvester   | --> |     Search Engines      |  |
      |  +----------------+     +------------------------+  |
      +-----------------------------------------------------+

                                  |
                                  v
                    +-----------------------------+
                    |     Collected Information   |
                    | - IPs, Subdomains           |
                    | - Open Ports & Services     |
                    | - Technology Stack          |
                    | - Emails, Metadata          |
                    +-----------------------------+
```

## OUTPUT:
### Whois
<img width="1920" height="1200" alt="Screenshot (1)" src="https://github.com/user-attachments/assets/7857da10-d5e2-41bd-9974-d990a34a6725" />

### Finding Hosting Company :
<img width="1920" height="1200" alt="Screenshot (2)" src="https://github.com/user-attachments/assets/a148b608-0720-4661-af1a-d0c17920b2c2" />

### History of the website :
<img width="1920" height="1200" alt="Screenshot (3)" src="https://github.com/user-attachments/assets/63886650-79f9-4dae-89d8-804271f4a07e" />

### netcat :
<img width="1919" height="1196" alt="Screenshot 2025-08-21 083800" src="https://github.com/user-attachments/assets/a7f3c8a3-b560-4e5a-8ec9-0d8127591304" />

### nmap :
<img width="989" height="752" alt="Screenshot 2025-08-21 085644" src="https://github.com/user-attachments/assets/4b5cf20d-2582-4a36-9e23-1a77b3f24a2e" />

### whatweb :
<img width="1920" height="1200" alt="Screenshot (6)" src="https://github.com/user-attachments/assets/8d57cc7a-a2f8-4d65-880f-ad75bc36f4b3" />

<img width="1919" height="1199" alt="Screenshot 2025-08-24 184618" src="https://github.com/user-attachments/assets/8bd8ea99-d129-4e00-a425-801e81767b11" />

### httprint :
<img width="1920" height="1200" alt="Screenshot (7)" src="https://github.com/user-attachments/assets/cbf38dcc-b786-4824-885f-e23b4db4d3fa" />

### TCP traceroute :
<img width="1920" height="1200" alt="Screenshot (8)" src="https://github.com/user-attachments/assets/4ff723a6-2835-4d65-8457-b295e1586fbe" />

### UDP traceroute :
<img width="711" height="891" alt="Screenshot 2025-08-24 185951" src="https://github.com/user-attachments/assets/94b8df54-3db8-4f62-a661-6fe639f8277f" />

<img width="728" height="929" alt="Screenshot 2025-08-24 190052" src="https://github.com/user-attachments/assets/d14a8c7e-f3b1-495b-bbdd-7ea9dd954ffc" />

## RESULT:
The information gathering techniques tools/procedure were  identified successfully
