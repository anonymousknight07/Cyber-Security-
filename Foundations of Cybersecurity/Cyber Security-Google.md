# Introduction to CyberSecurity -

### Program Overview-

  - Detecting and Responding to attacks.
  - Monitoring and protecting networks.
  - Investigating incidents.
  - Writing code to automate tasks.

### Module 1: *Welcome to the exciting world of cybersecurity*-

Definitions -
 1. **Cybersecurity**-
    The practice of ensuring confidentiality ,integrity, and availability of information by protecting networks, devices, people and data from unauthorized access or criminal exploitation.

 2. **Threat actor**-
     Any person or group who presents a security risk.
 
 3. **Security posture** is an organization’s ability to manage its defense of critical assets and data and react to change. A strong security posture leads to lower risk for the organization.
 4. **Personally Identifiable Information (PII)-**
     Any information used to infer an individual's Identity. It can include : Phone number, Full name ,E-mail.
 5. **Sensitive Personally Identifiable Information (SPII)-**
    A specific type of PII that falls under stricter handling guidelines. It may include social security number, biometric data such as facial recognition.


### Core skills for cybersecurity professionals

1. **Security Analyst transferable skills** :
   - Communication
   - Collaboration
   - Analysis
   - Problem Solving

2. **Security Analyst technical skills** :
   - Programming Languages
   - Security information and event Management ( SIEM ) tools.
   - Computer forensic
   -  **Intrusion detection systems (IDSs):** Cybersecurity analysts use IDSs to monitor system activity and alerts for possible intrusions. It’s important to become familiar with IDSs because they’re a key tool that every organization uses to protect assets and data. For example, you might use an IDS to monitor networks for signs of malicious activity, like unauthorized access to a network.

### Module-2: *The evolution of Cybersecurity*

1. **Computer Virus** - Malicious code written to interfere with computer operations and cause damage to data and software. 
2. **Malware** - Software designed to harm devices or networks.
     There are many types of malware. The primary purpose of malware is to obtain money, or in some cases, an intelligence advantage that can be used against a person, an organization, or a territory.  
     
     Some of the most common types of malware attacks today include: 
       - **Viruses:** Malicious code written to interfere with computer operations and cause damage to data and software. A virus needs to be initiated by a user (i.e., a threat actor), who transmits the virus via a malicious attachment or file download. When someone opens the malicious attachment or download, the virus hides itself in other files in the now infected system. When the infected files are opened, it allows the virus to insert its own code to damage and/or destroy data in the system.
     
	 - **Worms:** Malware that can duplicate and spread itself across systems on its own. In contrast to a virus, a worm does not need to be downloaded by a user. Instead, it self-replicates and spreads from an already infected computer to other devices on the same network.
	 - **Ransomware:** A malicious attack where threat actors encrypt an organization's data and demand payment to restore access. 
     - **Spyware:** Malware that’s used to gather and sell information without consent. Spyware can be used to access devices. This allows threat actors to collect personal data, such as private emails, texts, voice and image recordings, and locations.

#### Past Cybersecurity attacks 
1. **Brains Virus** -
    In 1986, the Alvi brothers created the Brain virus,  although the intention of the virus was to track illegal copies of medical software and prevent pirated licenses, what the virus actually did was unexpected. Once a person used a pirated copy of the software, the virus-infected that computer. Then, any disk that was inserted into the computer was also infected. The virus spread to a new computer every time someone used one of the infected disks. Undetected, the virus spread globally within a couple of months. Although the intention was not to destroy data or hardware, the virus slowed down productivity and significantly impacted business operations.
2. **Morris Worm**-
    In 1988, Robert Morris developed a program to assess the size of the internet. The program crawled the web and installed itself onto other computers to tally the number of computers that were connected to the internet. Sounds simple, right? The program, however, failed to keep track of the computers it had already compromised and continued to re-install itself until the computers ran out of memory and crashed. About 6,000 computers were affected, representing 10% of the internet at the time. This attack cost millions of dollars in damages due to business disruptions and the efforts required to remove the worm. After the Morris worm, Computer Emergency Response Teams, known as CERTs®, were established to respond to computer security incidents.

#### Attacks in the digital age -
1. **Love-Letter Attack** - 
    In the year 2000, Onel De Guzman created the LoveLetter malware to steal internet login credentials. This attack spread rapidly and took advantage of people who had not developed a healthy suspicion for unsolicited emails. Users received an email with the subject line, "I Love You." Each email contained an attachment labeled, "Love Letter For You." When the attachment was opened, the malware scanned a user's address book. Then, it automatically sent itself to each person on the list and installed a program to collect user information and passwords. Recipients would think they were receiving an email from a friend, but it was actually malware. The LoveLetter ended up infecting 45 million computers globally and is believed to have caused over $10 billion dollars in damages. The LoveLetter attack is the first example of social engineering.

 2. **Equifax breach**-
    In 2017, attackers successfully infiltrated the credit reporting agency, Equifax. This resulted in one of the largest known data breaches of sensitive information. Over 143 million customer records were stolen, and the breach affected approximately 40% of all Americans.
    The records included personally identifiable information including social security numbers, birth dates, driver's license numbers, home addresses, and credit card numbers. From a security standpoint, the breach occurred due to multiple failures on Equifax's part.

**What is Social Engineering ?**
  Social engineering is a manipulation technique that exploits human error to gain private information, access, or valuables.

  Some of the most common types of social engineering attacks today include:
  - **Social media phishing:** A threat actor collects detailed information about their target from social media sites. Then, they initiate an attack.
  - **Watering hole attack:** A threat actor attacks a website frequently visited by a specific group of users.
  - **USB baiting:** A threat actor strategically leaves a malware USB stick for an employee to find and install, to unknowingly infect a network. 
  - **Physical social engineering:** A threat actor impersonates an employee, customer, or vendor to obtain unauthorized access to a physical location.
   
#### Phishing
 **Phishing** is the use of digital communications to trick people into revealing sensitive data or deploying malicious software. 

Some of the most common types of phishing attacks today include: 

- **Business Email Compromise (BEC):** A threat actor sends an email message that seems to be from a known source to make a seemingly legitimate request for information, in order to obtain a financial advantage.
    
- **Spear phishing:** A malicious email attack that targets a specific user or group of users. The email seems to originate from a trusted source.
    
- **Whaling:** A form of spear phishing. Threat actors target company executives to gain access to sensitive data.
    
- **Vishing:** The exploitation of electronic voice communication to obtain sensitive information or to impersonate a known source.
    
- **Smishing:** The use of text messages to trick users, in order to obtain sensitive information or to impersonate a known source.

#### Introduction to the eight CISSP security domains, Part 1

The eight CISSP security domains are :-
     ![[Pasted image 20231229221047.png]]

1. Security and Risk Management -
     Defines security goals and objectives, risk mitigation, compliance, business continuity, and the law.
2. Asset security - 
      Secures digital and physical assets. It's also related to the storage, maintenance, retention and destruction of data.
3. Security Architecture and Engineering-
      Optimizes data security by ensuring effective tools, systems and processes are in place.
4. Communication  and network security-
     Manage and secure physical networks and wireless communications.
5. Identity and access management-
    Keeps data secure, by ensuring user follow established policies to control and manage physical assets, like office spaces, and logical assets, such as networks and applications.
6. Security assessment and testing-
     Conducting security control testing, collecting and analyzing data, and conducting security audits to monitor for risks, threats, and vulnerabilities .
7. Security Operations -
      Conducting investigations and implementing preventative measures.
 8. Software development guideline-
     Uses secure coding practices , which are a set of recommended guidelines that are used to create secure applications and services.
#### Attacks-
     
 ### **Password attack** -
A **password attack** is an attempt to access password-secured devices, systems, networks, or data. Some forms of password attacks that you’ll learn about later in the certificate program are:  

    - Brute force
    
    - Rainbow table
    

Password attacks fall under the communication and network security domain. 

 ### **Social engineering attack** - 
**Social engineering** is a manipulation technique that exploits human error to gain private information, access, or valuables. Some forms of social engineering attacks that you will continue to learn about throughout the program are:

    - Phishing
    
    - Smishing
    
    - Vishing
    
    - Spear phishing
    
    - Whaling
    
    - Social media phishing
    
    - Business Email Compromise (BEC)
    
    - Watering hole attack
    
    - USB (Universal Serial Bus) baiting
    
    - Physical social engineering 
    
   Social engineering attacks are related to the security and risk management domain.

### **Physical attack**
A **physical attack** is a security incident that affects not only digital but also physical environments where the incident is deployed. Some forms of physical attacks are:

- Malicious USB cable
    
- Malicious flash drive
    
- Card cloning and skimming
    

Physical attacks fall under the asset security domain.

### **Adversarial artificial intelligence**

**Adversarial artificial intelligence** is a technique that manipulates [artificial intelligence and machine learning](https://www.nccoe.nist.gov/ai/adversarial-machine-learning) technology to conduct attacks more efficiently. Adversarial artificial intelligence falls under both the communication and network security and the identity and access management domains.

### **Supply-chain attack**

A **supply-chain attack** targets systems, applications, hardware, and/or software to locate a vulnerability where malware can be deployed. Because every item sold undergoes a process that involves third parties, this means that the security breach can occur at any point in the supply chain. These attacks are costly because they can affect multiple organizations and the individuals who work for them. Supply-chain attacks can fall under several domains, including but not limited to the security and risk management, security architecture and engineering, and security operations domains.

### **Cryptographic attack**

A **cryptographic attack** affects secure forms of communication between a sender and intended recipient. Some forms of cryptographic attacks are: 

- Birthday
    
- Collision
    
- Downgrade
    

Cryptographic attacks fall under the communication and network security domain.

#### Threat actor types

#### **Advanced persistent threats**

Advanced persistent threats (APTs) have significant expertise accessing an organization's network without authorization. APTs tend to research their targets (e.g., large corporations or government entities)  in advance and can remain undetected for an extended period of time. Their intentions and motivations can include:

- Damaging critical infrastructure, such as the power grid and natural resources
    
- Gaining access to intellectual property, such as trade secrets or patents
    

### **Insider threats**

Insider threats abuse their authorized access to obtain data that may harm an organization. Their intentions and motivations can include: 

- Sabotage
    
- Corruption
    
- Espionage
    
- Unauthorized data access or leaks 
    

### **Hacktivists**

Hacktivists are threat actors that are driven by a political agenda. They abuse digital technology to accomplish their goals, which may include: 

- Demonstrations
    
- Propaganda
    
- Social change campaigns
    
- Fame
    

## Hacker types

![Six hackers on computers.](https://d3c33hcgiwev3.cloudfront.net/imageAssetProxy.v1/OHc71ylUQoWnWRkgeKXEgw_2c16d4ed0420478c938c9af9257ccff1_image1.png?expiry=1704412800000&hmac=UG4FkMp3FMmUyZVzKIwWnjsBUpOpJlpr1KHQO48O0wE)

A **hacker** is any person who uses computers to gain access to computer systems, networks, or data. They can be beginner or advanced technology professionals who use their skills for a variety of reasons. There are three main categories of hackers:

- Authorized hackers are also called ethical hackers. They follow a code of ethics and adhere to the law to conduct organizational risk evaluations. They are motivated to safeguard people and organizations from malicious threat actors.
    
- Semi-authorized hackers are considered researchers. They search for vulnerabilities but don’t take advantage of the vulnerabilities they find.
    
- Unauthorized hackers are also called unethical hackers. They are malicious threat actors who do not follow or respect the law. Their goal is to collect and sell confidential data for financial gain. 
    

**Note:** There are multiple hacker types that fall into one or more of these three categories.

New and unskilled threat actors have various goals, including: 

- To learn and enhance their hacking skills
    
- To seek revenge
    
- To exploit security weaknesses by using existing malware, programming scripts, and other tactics 
    

Other types of hackers are not motivated by any particular agenda other than completing the job they were contracted to do. These types of hackers can be considered unethical or ethical hackers. They have been known to work on both illegal and legal tasks for pay.

There are also hackers who consider themselves vigilantes. Their main goal is to protect the world from unethical hackers.


**Watering hole attack**: A type of attack when a threat actor compromises a website frequently visited by a specific group of users


## MODULE 3 -
#### Introduction to security frameworks and controls-
1. Security Frameworks -
     Guidelines used for building plans to help mitigate risk and threats to data and privacy.
   Purpose of security frameworks- 
 - Protecting PII
 - Securing financial information
 - Identifying security weaknesses
 - Managing organizational risks
 - Aligning security with business goals
   ![[Pasted image 20240103211813.png]]
   Components of security Frameworks -
1. Identifying and documenting security goals.
2. Setting Guidelines to achieve security goals.
3. Implementing strong security processes.
4. Monitoring and communicating results.

2. Security controls -
	  Security controls are safeguards designed to reduce  specific security risks. For example, your company may have a guideline that requires employees to complete a privacy training to reduce the risk of data breaches. As a security analyst, you may use a software tool to automatically assign and track which employees have completed this training.

#### CIA Triad -
The CIA (confidentiality, integrity, and availability) triad is a foundational cybersecurity model that helps inform how organizations consider risk when setting up systems and security policies.
![[Pasted image 20240104232612.png]]

#### Security Ethics -
**Security ethics** are guidelines for making appropriate decisions as a security professional. Being ethical requires that security professionals remain unbiased and maintain the security and confidentiality of private data. Having a strong sense of ethics can help you navigate your decisions as a cybersecurity professional so you’re able to mitigate threats posed by threat actors’ constantly evolving tactics and techniques. In this reading, you’ll learn about more ethical concepts that are essential to know so you can make appropriate decisions about how to legally and ethically respond to attacks in a way that protects organizations and people alike.

## Module 4-

#### Common cybersecurity tools -

**Security information and event management (SIEM) tools**

A **SIEM tool** is an application that collects and analyzes log data to monitor critical activities in an organization. A **log** is a record of events that occur within an organization’s systems. Depending on the amount of data you’re working with, it could take hours or days to filter through log data on your own. SIEM tools reduce the amount of data an analyst must review by providing alerts for specific types of threats, risks, and vulnerabilities.

SIEM tools provide a series of dashboards that visually organize data into categories, allowing users to select the data they wish to analyze. Different SIEM tools have different dashboard types that display the information you have access to. 

SIEM tools also come with different hosting options, including on-premise and cloud.

#### Network protocol analyzers (packet sniffers)

A **network protocol analyzer**, also known as a **packet sniffer**, is a tool designed to capture and analyze data traffic in a network. This means that the tool keeps a record of all the data that a computer within an organization's network encounters. Later in the program, you’ll have an opportunity to practice using some common network protocol analyzer (packet sniffer) tools.

### Playbooks

A **playbook** is a manual that provides details about any operational action, such as how to respond to a security incident. Organizations usually have multiple playbooks documenting processes and procedures for their teams to follow. Playbooks vary from one organization to the next, but they all have a similar purpose: To guide analysts through a series of steps to complete specific security-related tasks.

```
Python and SQL can be used to perform repetitive, time-consuming tasks and/or request information from a database.
```

#### **Intrusion detection system** 

An **intrusion detection system** (IDS) is an application that monitors system activity and alerts on possible intrusions. The system scans and analyzes network packets, which carry small amounts of data through a network. The small amount of data makes the detection process easier for an IDS to identify potential threats to sensitive data. Other occurrences an IDS might detect can include theft and unauthorized access.

#### **Encryption**

Encryption makes data unreadable and difficult to decode for an unauthorized user; its main goal is to ensure confidentiality of private data. **Encryption** is the process of converting data from a readable format to a cryptographically encoded format. **Cryptographic encoding** means converting plaintext into secure ciphertext. **Plaintext** is unencrypted information and **secure ciphertext** is the result of encryption.  

**Note:** Encoding and encryption serve different purposes. Encoding uses a public conversion algorithm to enable systems that use different data representations to share information.    

#### **Penetration testing** 

**Penetration testing**, also called pen testing, is the act of participating in a simulated attack that helps identify vulnerabilities in systems, networks, websites, applications, and processes. It is a thorough risk assessment that can evaluate and identify external and internal threats as well as weaknesses.
