# **Case Study: Bangladesh National Bank Cyber Attack**



An analysis of the high-profile 2016 heist orchestrated by the Lazarus Group, a sophisticated cybercriminal entity attributed to North Korea. This incident serves as a critical reminder of the vulnerabilities within global digital economies and the necessity of fortified cybersecurity.



###### **Overview**

The Lazarus Group exploited systemic weaknesses to steal a staggering amount of money within a few hours. The attack targeted the integrity of international banking mechanisms, specifically the SWIFT messaging system.



###### **Objectives of the Attack**

The group employed espionage and ransomware strategies to achieve the following:

* Monetary Heist: Executing a large-scale financial theft.
* SWIFT Disruption: Interfering with international messaging for swift execution.
* Geo-Political Messaging: Sending a message through state backed cyber action.
* Economic Impact: Destabilizing the national economy.



###### **Attack Methodology**

The attackers used a multi-stage approach to infiltrate and exfiltrate funds:

* Infiltration: Spear phishing and exploitation of known vulnerabilities.
* Execution: SWIFT system manipulation and malware deployment.
* Obfuscation: Lateral movement, destroying digital traces, and complex money laundering.



###### **Impact Analysis**

The consequences of the breach were multifaceted, as illustrated by the following distribution:

|**Category**|**Impact Percentage**|**Description**|
|-|-|-|
|Operational Disruption|35.7%|Affected bank services, customer access, and reputation.|
|Global Awareness|21.4%|Increased international focus on cyber threats and security.|
|Financial Loss|14.3%|A direct loss of $81 million impacting bank stability.|
|Attribution Challenges|14.3%|Sophisticated methods used to evade detection and complicate identification.|
|Geopolitical Implications|14.3%|Raised questions regarding state-sponsored cybercrime.|

###### 

**Key Findings**

* Financial Toll: The attack resulted in a confirmed loss of $81 million.
* Systemic Weakness: The incident exposed critical vulnerabilities in the SWIFT messaging platform.
* Criminal Convergence: Highlighted the complex relationship between government-backed groups and financially motivated criminals.



###### **Specific Malware Used**

The Lazarus Group deployed several specialized tools to carry out the heist:

* Nestegg: A key piece of malware discovered during the heist, used to establish a foothold within the bank's network.
* Evtdiag.exe: A sophisticated tool developed specifically to hide traces of malicious activity on SWIFT systems by altering logs and database records.
* Brambul: A credential-gathering worm that uses brute-force attacks against SMB servers to steal passwords and move laterally through the network.
* Keystroke Loggers: Attackers planted loggers to capture administrative passwords, which were then used to access the bank's international money transfer systems.
* Backdoor.Contopee: A known Lazarus Group malware variant used in bank intrusions to maintain persistent access to the compromised network.
* FakeTLS: A protocol used by their malware to mimic legitimate encrypted traffic, allowing communication with command-and-control servers without triggering security alerts.



###### **Malware Categories \& Functions**

* Beyond specific names, the attack relied on three primary functional categories of software:
* Persistence: Tools used to create a permanent backdoor into the bank's system.
* Exfiltration: Software that established encrypted channels to move data out of the network undetected.
* Reconnaissance: Programs used to scan and navigate the internal network to identify the computers connected to the SWIFT network.

###### 

