---
published: false
---
## Introduction

Wreaking havoc and causing panic at multiple companies, banks, universities, airports, hospitals and a lot more the WannaCry ransomware worm is one of the most expensive and devastating attacks to date. The WannaCry worm solely infected Microsoft Windows.  It used two leaked tools that were proprietary of the National Security Agency (NSA). Spreading to over 150 countries it was were the world saw their privacy and information held hostage.

Originally known as WanaCrypt, the worm contained a RSA-2048 encryption making it impossible to be decrypted. The only way that the victims could regain access to their information was either through backup or paying the ransom which was a bitcoin equivalent to $300. Within 72 hours of infection the hackers demand increased where the ransom a bitcoin equivalent of $600 [3]. If the money wasn’t transferred to the hacker’s accounts within 7 days, the malware would proceed to delete all files in the victim’s system.

### Methodology

The worm infects the system the same way a trojan would. It can arrive over several methods that include Dropbox attachments, emails or advertisement links. If the worm manages to infect the system, it will quickly encrypt the files on the system using RSA-2048. When version 2.0 of the worm came out, it infected system in a much different method. Here instead of doing its original spam, spoof links or advertisements for transfer, it uses a remote malicious code. It used this remote code to attack all vulnerable computers that it can identify on the infected computers network. The worm will scan for TCP pot 139 and UDP port 445 (SMB) [3]. If any of those ports are set to listening and if the worm finds the host as vulnerable, it will download itself into that vulnerable host and execute itself and thereby infecting and encrypting that system.

For an exploit kit the ransomware uses the EternalBlue exploit kit. This exploit kit was leaked by the group called The Shadow Brokers.
