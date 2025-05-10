# Log-Analysis-System-Lab

## Objective

Simulate the log analysis process using Windows Event Viewer on a Windows 10 LTSC VM performed in Oracle VirtualBox to detect suspicious activities such as failed logins, administrator account usage, folder/file access with active auditing, and changes to audit policies.

## Skills Learned

- Able to analyze and interpret system activity logs with Event ID
- Detect potential security incidents on the system
- Recognize signs of suspicious activity on the system
- Increased knowledge of system vulnerabilities
- Development of critical thinking

## Tools Used

- Windows 10 LTSC Operating System (VM)
- Oracle VirtualBox (Host-Only Network)
- Event Viewer to filter and analyze logs by Event ID
- Command Prompt

## Steps

1. Specify the internal network target: 192.168.56.0/24 (Host-Only Network)
2. Run the command: nmap -sV -O 192.168.56.0/24 <br>
Explanation: <br>
• -sV: service version detection <br>
• -O: operating system detection

### Results and Analysis

<i>Img 1: Ubuntu </i> <br>
<img src="images/nmap1.png" alt="Scan Result" width="500"/>

<i>Img 2: Metasploitable2 </i> <br>
<img src="images/nmap2.png" alt="Scan Result" width="500"/>

<i>Img 3: Kali Linux </i> <br>
<img src="images/nmap3.png" alt="Scan Result" width="500"/> <br>

Nmap completed. 3 hosts were active on the internal network and detected in 26.50 seconds.

## Conclusion


