# 02. Explaining Common Threats & Protecting Humans from Attacks

## Viruses, Trojans, & Othjer Malware

### Malware: Malicious Software

* Viruses
* Trojans
* Worms
* Rootkits
* Spyware
* Adware
* PUP

### Viruses

* Computer Program that copies itself
* Spreads from one file to another
  * Can spread from computer to computer
* Executable code that attaches itself to another executable program
  * .exe
  * MS Office
* Corrupts files and the OS

### Spyware

* Could be through a keylogger
* Spies on victim
* Can find other sensitive information

### Trojan

* Designed to do a specific task
* Can give attacker backdoor access to the victim's machine
* Can control multiple machines to use as an attack - DDoS
* Ransomware: victim has to pay a ransom in order to access their files

### RootKits

* Designed to go undetected
* Can be installed in the computer's kernal
* Can control the entire computer

### Worms

* Replicate themselves
* Not attached to a program
* Attack a vulnerability of the target system

### Adware

* Generates revenue
  * Displays ads
  * Pay-per-click

## DoS Attacks & Man-in-the-middle Attacks

### Denial of Service

* Degrades a system to prevent legitimate users access
* Too much traffic for the system to process

### Distributed DoS

* Multiple machines doing a DoS to one server

### Man-in-the-middle

* Intercept client initial request to server
* Sends a copy to original server
* Server replies to Mitm
* Mitm replies to client with copy
* Can see contents of traffic intercepted by client to server communication
* Client & server believe they're talking correctly

## Social Engineering & Phishing Attacks

### Social Engineering

* Perceived trust between attacker and another party
* Could impersonate the victim in order to obtain sensitive information
* Convincing victim they are a trusted authority
* All future correspondence from them is legitimate
* Emails could contain malicious links
* Could provide the user with misinformation

### Phishing

* Social engineering attack that uses electronic communications

**Types:**
* Bulk Phishing
  * Not a specific target (Generic)
* Spear Phishing
  * Specific target (a lot of research)
* Whaling
  * Spear phishing targeting high profile targets
* Clone Phishing
  * Attacker clones logos of legitimate services

**Methods:**
* Link manipulation
* Realistic websites
  * www.titlecompany.updated-wiretransfer.com
  * Take the victim to the attackers website
* Website forgery
  * JavaScript to make the address bar look legitimate

## Endpoints Stopping Phishing

### Train the Userbase

* Verify domain
* Ask if email makes sense
* Check the data
* Call to verify
* Flag the email as spam
* Call right away if attempt was successful

### Computers Blocking Phishing Attempts

* Phishing attacks are becoming more sophisticated
* Cisco Advanced Phishing Protection
  * Analyzes emails
  * Takes configured action with malicious emails
  * Can be sent to Cisco's security experts for further analysis

## Attacks Against Cloud Services

Dos & DDoS can still happen in cloud environments

### Security Non-Profits

* CSA
* OWASP

### Data Breach

* Confidential info is stolen
* Attacker targets less secure systems:
  * Human error
  * Application vulnerabilities
  * Poor security practices

### Insecure APIs

* Allow for authorized data to be shared automatically
* Embedding API with a threat
* Stolen API keys
* API has more access than it should

### API Security Gateways

* Allow for single point of connection for API
* Security features are built into API Security Gateways
  * Not built into normal API Gateways

### Account Management

* Promptly remove accounts and change passwords
* Use MFA

## Security Intelligence Overview

### Hard to Keep up with Threats

* Not a "set it and forget it" solution
* Cant just sit back and monitor
* Too many devices to manually update
* A large amount of surface areas

### Too Much Work

Identify threats, research solutions, and implement mitigations for every threat on each attack medium

### Security Intelligence

* Organisations can participate in a community of security devices
  * All organisations benefit from new threat information
* Author, share, and consume

## Security Intelligence Authoring, Sharing, and Consuming

### Telemetry Sharing

Device upload data to network/Cloud

**Scenario:**
* Threat affects organisation
* Device now has info on threat
* Info is uploaded to cloud
* Additional info is uploaded from other orgs

### Security Intelligence

* Cloud performs analytics
* Normalises data and finds pattens
  * Time, duration, surface area, other metrics
  * Who is being attacked
  * More info allows for better mitigations
* Create signatures for different threats
* Different security devices have different mitigations
* Updates are shared with community
  * Cisco Talos can be every 3-5min
* Each device installs the updates
* All organizations participating in the cloud are protected from the new threat
* Mo manual input required
* Provides research and info to security professionals
* Allows you to stay in the loop of the new types of threats that are emerging

## Cisco Talos

* 1.1 million malicious software samples
* 300 billion email samples, 200 billion are malicious
* Block malware, phishing, and spam
* Need to have the appropriate license
  * Create policy and ruleset
* Defence in depth

**Cisco Products that use Talos:**
* NGFW & NGIPS
* Cisco AMP
* Email Security Appliance, Web Security Appliance
* Cloud Email Security, Cloud Web Security
* Cisco Umbrella
* Cisco Threat Grid
