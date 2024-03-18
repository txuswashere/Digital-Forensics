# Digital-Forensics

Digital Forensics Essentials

Table of Contents

- Module 01: Computer Forensics Fundamentals 
	- Fundamentals of Computer Forensics
	- Digital Evidence 
	- Forensic Readiness 
	- Roles and Responsibilities of a Forensic Investigator 
	- Legal Compliance in Computer Forensics 

- Module 02: Computer Forensics Investigation Process 
	- Forensic Investigation Process and its Importance 
	- Forensic Investigation Process - Pre-investigation Phase 
	- Forensic Investigation Process - Investigation Phase 
	- Forensic Investigation Process - Post-investigation Phase 

- Module 03: Understanding Hard Disks and File Systems 
	- Different Types of Disk Drives and their Characteristics
	- Logical Structure of a Disk 
	- Booting Process of Windows, Linux, and Mac Operating Systems 
	- File Systems of Windows, Linux, and Mac Operating Systems 
	- File System Examination 

- Module 04: Data Acquisition and Duplication 
	- Data Acquisition Fundamentals 
	- Types of Data Acquisition 
	- Data Acquisition Format 
	- Data Acquisition Methodology 

- Module 05: Defeating Anti-forensics Techniques 
	- Anti-forensics and its Techniques 
	- Anti-forensics Countermeasure

- Module 06: Windows Forensics 
	- Volatile and Non-Volatile Information
	- Windows Memory and Registry Analysis 
	- Cache, Cookie, and History Recorded in Web Browsers 
	- Windows Files and Metadata 

- Module 07: Linux and Mac Forensics 
	- Volatile and Non-Volatile Data in Linux 
	- Analyze Filesystem Images Using The Sleuth Kit 
	- Memory Forensics 
	- Mac Forensics 

- Module 08: Network Forensics 
	- Network Forensics Fundamentals 
	- Event Correlation Concepts and Types 
	- Identify Indicators of Compromise (IoCs) from Network Logs 
	- Investigate Network Traffic 

- Module 09: Investigating Web Attacks 
	- Web Application Forensics 
	- IIS and Apache Web Server Logs 
	- Investigating Web Attacks on Windows-based Servers 
	- Detect and Investigate Attacks on Web Applications 

- Module 10: Dark Web Forensics 
	- Dark Web 
	- Dark Web Forensics 
	- Tor Browser Forensics 

- Module 11: Investigating Email Crimes 
	- Email Basics 
	- Email Crime Investigation and its Steps 

- Module 12: Malware Forensics 
	- Malware, its Components and Distribution Methods 
	- Malware Forensics Fundamentals and Recognize Types of Malware Analysis
	- Static Malware Analysis 
	- Analyze Suspicious Word Documents 
	- Dynamic Malware Analysis 
	- System Behavior Analysis 
	- Network Behavior Analysis 




# Module 01: Computer Forensics Fundamentals 

- Fundamentals of Computer Forensics
	- Understanding Computer Forensics
	- Objectives of Computer Forensics
		- Identify, gather, and preserve the evidence of a cybercrime
		- Identify and gather evidence of cybercrimes in a forensically sound manner
		- Track and prosecute the perpetrators in a court of law
		- Interpret, document, and present the evidence such that it is admissible during prosecution
		- Estimate the potential impact of malicious activity on the victim and assess the intent of the perpetrator
		- Find vulnerabilities and security loopholes that help attackers
		- Understand the techniques and methods used by attackers to avert prosecution and overcome them
		- Recover deleted files, hidden files, and temporary data that can be used as evidence
		- Perform incident response (IR) to prevent further loss of intellectual property, finances, and reputation during an attack
		- Know the laws of various regions and areas, as digital crimes are widespread and remote
		- Know the process of handling multiple platforms, data types, and operating systems
		- Learn to identify and use the appropriate tools for forensic investigations
		- Prepare for incidents in advance to ensure the integrity and continuity of network infrastructure
		- Offer ample protection to data resources and ensure regulatory compliance
		- Protect the organization from similar incidents in the future
		- Help counteract online crimes such as abuse, bullying, and reputation damage
		- Minimize the tangible and intangible losses to an organization or an individual
		- Support the prosecution of the perpetrator of a cybercrime
	- Need for Computer Forensics 
		- Ensure the overall integrity and the continued existence of an organization’s computer system and network infrastructure
		- Help the organization capture important information if their computer systems or networks are compromised. Forensic evidence also helps prosecute the perpetrator of a cybercrime, if caught.
		- Extract, process, and interpret the actual evidence so that it proves the attacker’s actions and their guilt or innocence in court
		- Efficiently track down perpetrators/terrorists from different parts of the world. Terrorists who use the Internet as a communication medium can be tracked down, and their plans can be discovered. IP addresses are vital to finding the geographical location of the terrorists.
		- Save the organization’s money and valuable time. Many managers allocate a large portion of their IT budget for computer and network security.
		- Track complex cases such as ransomware attacks, email spamming, etc.
	- When Do You Use Computer Forensics? 
		- Prepare for incidents by securing and strengthening the defense mechanism as well as closing the loopholes in security
		- Gaining knowledge of the regulations related to cyber laws and comply with them
		- Report incidents involving a breach of cybersecurity
		- Identify the actions needed for incident response
		- Act against copyright and intellectual property theft/misuse
		- Settle disputes among employees or between the employer and employees
		- Estimate and minimize the damage to resources in a corporate setup
		- Set a security parameter and formulate security norms for ensuring forensic readiness
	- Types of Cybercrimes
		- Internal/Insider attacks
		- External attacks
	- Examples of Cybercrimes
		- Espionage
		- Intellectual property theft
		- Data manipulation
		- Trojan horse attack
		- Structured query language (SQL) attack
		- Brute-force attack
		- Phishing/spoofing
		- Privilege escalation attacks
		- Denial-of-service (DoS) attack
		- Cyber defamation
		- Cyberterrorism
		- Cyberwarfare
	- Impact of Cybercrimes at the Organizational Level
		- Loss of confidentiality, integrity and availability of information stored in organizational systems
		- Theft of sensitive data
		- Sudden disruption of business activities
		- Loss of customer and stakeholder trust
		- Substantial reputational damage
		- Huge financial losses
		- Penalties arising from the failure to comply with regulations

- Digital Evidence 
	- Types of Digital Evidence
		- Volatile data
		- Non-volatile data
	- Roles of Digital Evidence
		- Identity theft
		- Malicious attacks on the computer systems themselves
		- Information leakage
		- Unauthorized transmission of information
		- Theft of commercial secrets
		- Use/abuse of the Internet
		- Production of false documents and accounts
		- Unauthorized encryption/ password protection of documents
		- Abuse of systems
		- Email communication between suspects/conspirators
	- Sources of Potential Evidence
		- User-Created Files
			- Address books
			- Database files
			- Media (images, graphics, audio, video, etc.) files
			- Documents (text, spreadsheet, presentation, etc.) files
			- Internet bookmarks, favorites, etc.
		- User-Protected Files
			- Compressed files
			- Misnamed files
			- Encrypted files
			- Password-protected files
			- Hidden files
			- Steganography
		- Computer-Created Files
			- Backup files
			- Log files
			- Configuration files
			- Printer spool files
			- Cookies
			- Swap files
			- System files
			- History files
			- Temporary files
	- Location of Potential Evidence
		- Hard Drive: Text, picture, video, multimedia, database, and computer program files
		- Thumb Drive: Text, graphics, image, and picture files
		- Memory Card:  Event logs, chat logs, text files, image files, picture files, and internet browsing history 
		- Smart Card, Dongle, and Biometric Scanner: Evidence is found by recognizing or authenticating the information of the card and the user, through the level of access, configurations, permissions, and in the device itself
		- Answering Machine: Voice recordings such as deleted messages, last called number, memo, phone numbers, and tapes
		- Digital Camera/Surveillance cameras: Images, removable cartridges, video, sound, time and date stamp, etc.
		- Random Access Memory (RAM) and Volatile storage: Evidence is located and can be acquired from the main memory of the computer
		- Handheld Devices: Address book, appointment calendars or information, documents, email, handwriting, password, phone book, text messages, and voice messages
		- Local Area Network (LAN) Card/ Network Interface Card (NIC): MAC (Media Access Control) address
		- Routers, Modem, Hubs, and Switches: For routers, evidence is found in the configuration files. For hubs, switches, and modems evidence is found on the devices themselves
		- Network Cables and Connectors: On the devices themselves
		- Server: Computer system
		- Printer: Evidence is found through usage logs, time and date information, and network identity information, ink cartridges, and time and date stamp
		- Internet of Things and wearables: Evidence can be acquired in the form of GPS, audio and video recordings, cloud storage sensors, etc.
		- Removable Storage Device and Media: Storage device and media such as tape, CD, DVD, and Blu-ray contain the evidence in the devices themselves
		- Scanner: Evidence is found by looking at the marks on the glass of the scanner
		- Telephones: Evidence is found through names, phone numbers, caller identification information, appointment information, electronic mail, and pages, etc.
		- Copiers: Documents, user usage logs, time, and date stamps, etc.
		- Credit Card Skimmers: Evidence is found through card expiration date, user’s address, credit card numbers, user’s name, etc.
		- Digital Watches: Evidence is found through address book, notes, appointment calendars, phone numbers, email, etc.
		- Facsimile (Fax) Machines: Evidence is found through documents, phone numbers, film cartridge, send or receive logs
		- Global Positioning Systems (GPS): Evidence is found through previous destinations, way points, routes, travel logs, etc.
	- Rules of Evidence
		- Understandable
		- Admissible
		- Authentic
		- Reliable
		- Complete
	- Best Evidence Rule
	- Federal Rules of Evidence (United States) https://www.rulesofevidence.org
		- Preserving a claim of error
		- Not needing to renew an objection or offer of proof
		- Court’s statement about the ruling; directing an offer of proof
		- Preventing the jury from hearing inadmissible evidence
		- Taking Notice of Plain Error
	- Scientific Working Group on Digital Evidence (SWGDE) https://www.swgde.org
	- The Association of Chief Police Officers (ACPO) Principles of Digital Evidence https://www.college.police.uk


- Forensic Readiness 
	- An incident response team that is forensically ready offers an organization the following benefits:
		- It eases evidence gathering to act in the company’s defense in case of a lawsuit
		- It enables the use of comprehensive evidence collection to act as a deterrent to insider threats and to process all important pieces of evidence without fail
		- It helps the organization conduct a fast and efficient investigation in the event of a major incident and take the required actions with minimal disruption to day-to-day business activities 
		- It facilitates a well-designed, fixed, and structured approach toward the storage of evidence to reduce investigation expenses and time considerably and to simultaneously preserve the all-important chain of custody
		- It establishes a structured approach toward the storage of all digital information, which not only reduces the cost of any court-ordered disclosure or regulatory/legal need to disclose data but also fulfills requirements under federal law (e.g., as a response to a request for discovery under the Federal Rules of Civil Procedure)
		- It extends the protection offered by an information security policy to cover the broader threats of cybercrime, such as intellectual property thefts, fraud, or extortion
		- It demonstrates due diligence and good corporate governance of the company’s information assets, as measured by the “Reasonable Man” standard
		- It ensures that the investigation meets all regulatory requirements.
		- It can improve upon and make the interface to law enforcement easier
		- It improves the prospects of successful legal action.
		- It can provide evidence to resolve commercial or privacy disputes.
		- It can support employee sanctions up to and including termination based on digital evidence (e.g., to prove a violation of an acceptable-use policy)
		- It prevents attackers from covering their tracks
		- It limits the cost of regulatory or legal requirements for disclosure of data
		- It helps avert similar attacks in the future
	- Forensic Readiness and Business Continuity
		- Forensic readiness allows businesses to:
			- Quickly determine the incidents
			- Understand relevant information
			- Collect legally sound evidence and analyze it to identify attackers
			- Minimize the required resources
			- Eliminate the threat of repeated incidents
			- Quickly recover from damage with less downtime
			- Gather the evidence required to claim insurance
			- Legally prosecute the perpetrators and claim damages
		- Lack of forensic readiness results in the following:
			- Loss of clients due to damage to the organization’s reputation
			- System downtime
			- Data manipulation, deletion, and theft
			- Inability to collect legally sound evidence
	- Forensic Readiness Planning
		- Identify the potential evidence required for an incident
		- Determine the sources of evidence
		- Define a policy that determines the pathway to legally extract electronic evidence with minimal disruption
		- Establish a policy for securely handling and storing the collected evidence
		- Identify if the incident requires full or formal investigation
		- Create a process for documenting the procedure
		- Establish a legal advisory board to guide the investigation process
			- The legal advisory board will help the organization do the following:
				- Manage any threats arising from the incident
				- File the incident legally and ensure proper prosecution
				- Understand the legal and regulatory constraints and suggest necessary action
				- Handle processes such as reputation protection and public relations issues
				- Design legal agreements with partners, customers, investors, and employees
				- Investigate the company’s commercial and civil disputes
		- Keep an incident response team ready to review the incident and preserve the evidence

- Roles and Responsibilities of a Forensic Investigator 
	- Need for a Forensic Investigator
		- Cybercrime Investigation
		- Sound Evidence Handling
		- Incident Handling and Response
	- Roles and Responsibilities of a Forensics Investigator
		- Evaluates the damages of a security breach
		- Identifies and recovers data required for investigation
		- Extracts the evidence in a forensically sound manner
		- Ensures appropriate handling of the evidence
		- Acts as a guide to the investigation team
		- Creates reports and documents about the investigation for presenting in a court of law
		- Reconstructs the damaged storage devices and uncovers the information hidden on the computer
		- Updates the organization about various methods of attack and data recovery techniques, and maintains a regularly updated record of them (by determining and using the relevant documentation method)
		- Addresses the issue in a court of law and attempts to win the case by testifying in court
	- What Makes a Good Computer Forensics Investigator?
		- Interviewing skills to gather extensive information about the case from the client or victim, witnesses, and suspects
		- Researching skills to know the background and activities pertaining to the client or victim, witnesses, and suspects
		- Maintains perfect accuracy of the tests performed and their records
		- Patience and willingness to work long hours
		- Excellent writing skills to detail findings in the report
		- Strong analytical skills to find the evidence and link it to the suspect
		- Excellent communication skills to explain their findings to the audience
		- Remains updated about new methodologies and forensic technology
		- Well-versed in more than one computer platform (including Windows, Macintosh, and Linux)
		- Knowledge of various technologies, hardware, and software
		- Develops and maintains contact with computing, networking, and investigating professionals
		- Honest, ethical, and law abiding
		- Has knowledge of the laws relevant to the case
		- Ability to control emotions when dealing with issues that induce anger
		- Multi-discipline expertise related to both criminal and civil cases

- Legal Compliance in Computer Forensics 
	- Gramm-Leach-Bliley Act (GLBA) https://www.ftc.gov
	- Federal Information Security Modernization Act of 2014 (FISMA) https://csrc.nist.gov
	- Health Insurance Portability and Accountability Act of 1996 (HIPAA) https://www.hhs.gov
	- Payment Card Industry Data Security Standard (PCI DSS) https://www.nist.gov
	- The Electronic Communications Privacy Act https://it.ojp.gov
	- General Data Protection Regulation (GDPR) https://gdpr.eu
	- Data Protection Act of 2018 http://www.legislation.gov.uk
	- Sarbanes-Oxley Act (SOX) of 2002 https://www.sec.gov
- Other Laws Relevant to Computer Forensics
	- United States
		- Foreign Intelligence Surveillance Act https://www.fas.org
		- Protect America Act of 2007 https://www.congress.gov
		- Privacy Act of 1974 https://www.justice.gov
		- National Information Infrastructure Protection Act of 1996 https://www.congress.gov
		- Computer Security Act of 1987 https://www.congress.gov
		- Freedom of Information Act (FOIA) https://www.foia.gov
	- United Kingdom
		- Regulation of Investigatory Powers Act 2000 https://www.legislation.gov.au
	- Australia
		- Cybercrime Act 2001 https://www.legislation.gov.au
		- Information Privacy Act 2014 https://www.findandconnect.gov.au
	- India 
		- Information Technology Act http://www.dot.gov.in
	- Germany
		- Section 202a. Data Espionage, Section 303a. Alteration of Data, Section 303b. Computer Sabotage http://www.cybercrimelaw.net
	- Italy 
		- Penal Code Article 615 ter http://www.cybercrimelaw.net
	- Canada 
		- Canadian Criminal Code Section 342.1 https://laws-lois.justice.gc.ca
	- Singapore 
		- Computer Misuse Act https://sso.agc.gov.sg
	- Belgium 
		- Computer Hacking http://www.cybercrimelaw.net
	- Brazil 
		- Unauthorized modification or alteration of the information system https://www.domstol.no
	- Philippines 
		- Data Privacy Act of 2012 https://www.privacy.gov.ph
	- Hong Kong 
		- Cap. 486 Personal Data (Privacy) Ordinance https://www.pcpd.org.hk


# Module 02: Computer Forensics Investigation Process 

- Forensic Investigation Process and its Importance 
	- Forensic Investigation Process. Pre-investigation Phase 
	- Forensic Investigation Process. Investigation Phase 
	- Forensic Investigation Process. Post-investigation Phase 

- Forensic Investigation Process. Pre-investigation Phase 
	- Setting Up a Computer Forensics Lab
		- Planning and budgeting considerations
			- Types of Investigations
			- Number of Investigators/Examiners
			- Equipment Requirement
			- Software Requirement
		- Physical and structural design considerations
			- Lab Size
			- Access to Essential Services
			- Space Estimation for Work Area and Evidence Storage
			- Heating, Ventilation, and Air-Conditioning
		- Work area considerations
			- Workstation Requirement
			- Ambience
			- Internet, Network, and Communication Line
			- Lighting Systems and Emergency Power
		- Physical security considerations
			- The level of physical security required for a forensics lab depends on the nature of investigations performed in the lab
			- Maintain a log register at the entrance of the lab to record visitor data such as the address and name of the visitor with date, time, and the purpose of the visit, as well as name of the contact person. Provide visitors with passes to distinguish them from the lab staff and maintain an electronic sign-in log for them.
			- Install an intrusion alarm system in the lab to provide an additional layer of protection and deploy guards around the premises
			- Keep the lab under surveillance by placing closed-circuit cameras in the lab and around its premises
			- Place fire extinguishers within and outside the lab and provide training to the lab personnel and guards on how to use them, in case of a fire
			- Shield workstations from transmitting electromagnetic signals, which is common with electronic equipment. The solution is to shield emissions through a process the US Department of Defense has named TEMPEST. To prevent eavesdropping, TEMPEST labs use sheets of good metallic conductors such as copper for lining the walls, ceilings, and floor. Insulate the power cables to prevent radiation and add filters to the telephones within the lab.
		- Human resource considerations
			- The overall success of a computer forensics laboratory mainly relies on experience gathering, knowledge sharing, ongoing education, and investment in human resources development
			- Estimate the number of personnel required to deal with the case based on its nature and the skills they should have to complete the tasks
			- Interview the appropriate candidates and recruit them legally. Ensure they have certification pertaining to their job roles.
			- In the case of a computer forensics laboratory, key job roles include lab cybercrime investigator, lab director, forensic technician, and forensic analyst
		- Forensic lab licensing
			- Forensics labs should be licensed by the concerned authorities to indicate trustworthiness
			- The authorities provide these licenses after reviewing the lab and the facilities it has for performing investigations
			- Some such licenses include the American Society of Crime Laboratory Directors (ASCLD)/LAB accreditation and the ISO/IEC 17025 accreditation
	- Building the Investigation Team
		- Identify the team members and assign them responsibilities
		- Appoint a person as the technical lead for the investigation
		- Keep the investigation team as small as possible to achieve confidentiality and avoid information leaks
		- Provide each team member with the necessary clearance and authorization to complete the assigned tasks
		- Enlist help from a trusted external investigation team, if required

		- To find the appropriate evidence from a variety of computing systems and electronic devices, the following people may be involved:
			- Photographer
			- Incident Responder
			- Incident Analyzer
			- Evidence Examiner/Investigator
			- Evidence Documenter
			- Evidence Manager
			- Expert Witness
			- Attorney: 
	- Understanding the Hardware and Software Requirements of a Forensic Lab
		- Hardware
			- Two or more forensic workstations with good processing power and RAM
			- Specialized cables
			- Write-blockers
			- Drive duplicators
			- Archive and Restore devices
			- Media sterilization systems
			- Other equipment that allows forensic software tools to work
			- Computer Forensic hardware toolkit, such as Paraben's First Responder Bundle, DeepSpar Disk Imager, FRED forensic workstation etc.
		- Software
			- OSes
			- Data discovery tools
			- Password-cracking tools
			- Acquisition tools
			- Data analyzers
			- Data recovery tools
			- File viewers (Image and graphics)
			- File type conversion tools
			- Security and Utilities software
			- Computer forensic software tools such as Wireshark, Access Data’s FTK, etc.


- Forensic Investigation Process. Investigation Phase 
	- Computer Forensics Investigation Methodology
		- Documenting the Electronic Crime Scene 
		- Search and Seizure
		- Evidence Preservation
		- Data Acquisition
		- Data Analysis 
		- Case Analysis 
		- Reporting 
		- Testifying as an Expert Witness

	- Documenting the Electronic Crime Scene
		- Documentation of the electronic crime scene is a continuous process during the investigation that makes a permanent record of the scene
		- It is essential to properly note down the site and state of computers, digital storage media, and other electronic devices
		- Document the physical crime scene, noting the position of the system and other equipment, if any
		- Document details of any related, difficult-to-find electronic components
		- Record the state of the computer system, digital storage media, electronic devices, and predictable evidence, including the power status of the computer
		- Take a photograph of the computer monitor’s screen and note down what you see on the screen
	- Search and Seizure
	- Planning the Search and Seizure
		- Description, title, and location of the incident
		- Applicable jurisdiction, relevant legislation, and organizational policy
		- Determining the extent of authority to search
		- Creating a chain of custody document
		- Details of equipment to be seized, such as structure type and size, location (all in one place, spread across the building or floors), type of device and model number, power status, network status and type of network, backups (if any), last time and date, location of backup and if it is necessary to take the server down and the business impact of this action
		- Search and seizure type (overt/covert) and approval from the local management
		- Health and safety precautions, such as all forensic teams wearing protective latex gloves for all searching and seizing operations onsite to protect the staff and preserving any fingerprints that may come handy in the future
	- Evidence Preservation
		- The logbook of the project to record observations related to the evidence
		- A tag to uniquely identify any evidence
		- A chain of custody record
	- Data Acquisition
	- Data Analysis
		- Analyzing the file content for data usage
		- Analyzing the date and time of file creation and modification
		- Finding the users associated with file creation, access, and file modification
		- Determining the physical storage location of the file
		- Timeline generation
		- Identifying the root cause of the incident
	- Case Analysis
		- Check if there is a possibility to follow other investigative methods to, for instance, identify a remote storage location, examine network service logs for any information of evidentiary value, collect case-specific evidence from social media, identifying remote storage locations etc.)
		- Gather additional information related to the case (e.g., aliases, email accounts, ISP used, names, network configuration, system logs, and passwords) by interviewing the respective individuals.
		- Identify the relevance of various network elements to the crime scene such as credit cards, check papers, scanners, and cameras
		- Consider the relevance of peripheral components to the investigation; for instance, in forgery or fraud cases, consider non-computer equipment such as laminators, check paper, scanners, printers, and digital cameras


- Forensic Investigation Process. Post-investigation Phase 
	- Gathering and Organizing Information
		- Identification
		- Procedures
			- Gather all notes from different phases of the investigation process
			- Identify the facts to be included in the report for supporting the conclusions
			- List all the evidence to submit with the report
			- List the conclusions that need to be in the report
			- Organize and classify the information gathered to create a concise and accurate report
	- Writing the Investigation Report
		- It should accurately define the details of an incident.
		- It should convey all necessary information in a concise manner.
		- It should be technically sound and understandable to the target audience.
		- It should be structured in a logical manner so that information can be easily located.
		- It should be created in a timely manner.
		- It should be able to withstand legal inspection.
		- It should include conclusions that can be completely reproduced by a third-party.
		- It should try to answer questions raised during a judicial trial.
		- It should provide valid conclusions, opinions, and recommendations supported by figures and facts.
		- It should adhere to local laws to be admissible in court.
	- Forensics Investigation Report Template
		- Executive summary
			- Case number
			- Names and Social Security Numbers of authors, investigators, and examiners
			- Purpose of investigation
			- Significant findings
			- Signature analysis
		- Investigation objectives
		- Details of the incident
			- Date and time the incident allegedly occurred
			- Date and time the incident was reported to the agency’s personnel
			- Details of the person or persons reporting the incident
		- Investigation process
			- Date and time the investigation was assigned
			- Allotted investigators
			- Nature of the claim and information provided to the investigators
		- Evidence information
			- Location of the evidence
			- List of the collected evidence
			- Tools involved in collecting the evidence
			- Preservation of the evidence
		- Evaluation and analysis Process
			- Initial evaluation of the evidence
			- Investigative techniques
			- Analysis of the computer evidence (Tools involved) 
		- Relevant findings
		- Supporting Files
			- Attachments and appendices
			- Full path of the important files
			- Expert reviews and opinion
		- Other supporting details
			- Attacker’s methodology
			- User’s applications and Internet activity
			- Recommendations
	- Testifying as an Expert Witness
		- Familiarize the expert witness with the usual proceduresthat are followed during a trial
		- The attorney introduces the expert witness
		- The opposing counsel may try to discredit the expert witness
		- The attorney leads the expert witness through the evidence
		- Later, it is followed by the opposing counsel’s cross-examination


# Module 03: Understanding Hard Disks and File Systems 

- Different Types of Disk Drives and their Characteristics
	- Capacity
	- Interface used
	- Speed in RPM
	- Seek time
	- Access time
	- Transfer time

	- Understanding Hard Disk Drive: HDD is a non-volatile digital data storage device that records data magnetically on a metallic platter
		- Tracks: Tracks are the concentric circles on platters where all the information is stored. Platters have two surfaces, each of which is divided into concentric circles called tracks. Tracks store all the information on a hard disk
		- Track Numbering: Track numbering on a hard disk begins at 0 from the outer edge and moves towards the center. The number of tracks on a hard disk depends on the size of the disk
		- Sector: Tracks contain smaller divisions called sectors, which are the smallest physical storage units on a hard-disk platter.
			- ID information: This part contains the sector number and location, which identify sectors on the disk. It also contains status information on the sector.
			- Synchronization fields: The drive controller drives the read process using these fields
			- Data: This part is the information stored on the sector
			- Error correction coding (ECC): This code ensures the integrity of the data
			- Gaps: These are spaces used to provide time for the controller to continue the read process
		- Sector Addressing: Cylinders, heads, and sectors (CHS) determine the address of the individual sectors on the disk. When a disk is formatted, it is divided into tracks and sectors
		- 4K Sectors: New hard drives use 4096-byte (4 KB or 4K) advanced format sectors. Generation-one Advanced Format, also called as 4K sector technology, efficiently uses the storage surface media of a disk by merging eight 512-byte sectors into a single sector of 4096 bytes
		- Data Density on a Hard Disk: Data is recorded onto a hard disk using a method called zoned bit recording (also known as a multiple zone recording). In this technique, tracks are combined together into zones depending on their distance from the center of the disk. Each zone is assigned a number of sectors per track
			- Track density: This term refers to the space required by a particular number of tracks on a disk. Disks with a greater track density can store more information and offer better performance.
			- Areal density: This term refers to the number of bits per square inch on a platter, and it represents the amount of data a hard disk can hold.
			- Bit density: This term refers to the number of bits a unit length of track can accommodate.
		- CHS (Cylinder-Head-Sector) Data Addressing and Disk Capacity Calculation
			- The CHS addressing method addresses each physical block of data on a hard disk by specifying the cylinder (radius), head (platter side), and sector (angular position)
		- Measuring the Hard Disk Performance
			- Access time: Access time refers to the time taken by a drive to initiate data transfer. This time depends on the mechanical nature of rotating disks and moving heads. 
			- Seek time: This is the time required for a hard-disk controller to find a particular piece of data. When reading or writing data, the disk heads move to the correct position through the process of seeking. The time taken to move read or write disc heads from one point to another on the disk is the seek time. 
			- Rotational latency: This refers to the rotational delay in the chosen disk sector to rotate under read or write disk-drive heads. The average disk rotational latency is half the time taken by the disk to complete one revolution. The term is applicable only to rotating storage devices such as HDDs and floppy drives but not tape drives.
			- Data transfer rate: The data transfer rate of a drive is expressed by the internal rate, which is the rate of data transfer between the disk surface and drive controller, as well as the external rate, which is the rate of data transfer between the drive controller and host system.
	- Understanding Solid-State Drive (SSD): SSD is a non-volatile storage device that uses NAND flash memory chips to store digital data. SSDs are faster than HDDs as they have no moving parts, and the read/write performance depends on data connection of the drive
		- NAND-based SSDs
		- Volatile RAM-based SSDs

		- Advantages of SSD:
			- Faster data access
			- Lower power usage
			- Higher reliability
		- Components of SSD
			- NAND flash memory—It uses non-volatile storage technology to store data and consists of floating gate transistors that do not require power to retain data
			- Controller—It is an embedded processor that acts as a bridge between the flash memory components and the system by executing firmware-level software
			- DRAM—It is a volatile memory and requires power to retain data. DRAM is included in an SSD to increase its read/write performance.
			- Host interface—Based on performance requirements, various host interfaces are used in SSDs. Commonly used SSD host interfaces include Serial Advanced Technology Attachment (SATA), Peripheral Component Interconnect Express (PCIe), and SCSI.

	- Disk Interfaces:
		- ATA/PATA (IDE/EIDE): ATA (Advanced Technology Attachment) is the official ANSI (American National Standards Institute) name of Integrated Drive Electronics (IDE), a standard interface between a motherboard’s data bus and storage disks
		- Serial ATA/ SATA (AHCI): It is an advancement of ATA and uses serial signaling, unlike IDE’s parallel signaling
		- SAS (Serial Attached SCSI): is the successor and an advanced alternative to parallel SCSI in enterprise environments
		- PCIe SSD: A PCIe (Peripheral Component Interconnect Express) SSD is a high-speed serial expansion card that integrates flash directly into the motherboard
		- SCSI (Small Computer System Interface) refers to a set of ANSI standard interfaces based on the parallel bus structure and designed to connect multiple peripherals to a computer

- Logical Structure of a Disk 
	- Clusters: 
		- A cluster is the smallest logical storage unit on a hard disk
		- It is a set of sectors within a disk ranging from cluster number 2 to 32 or more, depending on the formatting scheme in use
		- The file system divides the storage on a disk volume into discreet chunks of data for efficient disk usage and performance. These chunks are called clusters
		- The process by which files are allocated to clusters is called allocation; therefore, clusters are also known as allocation units. 
		- In the File Allocation Table (FAT) file system, the clusters linked with a file keep track of file data in the hard disk's file allocation table
	- Cluster Size:
		- Cluster sizing has a significant impact on the performance of an OS and disk utilization
		- Cluster size can be altered for optimum disk storage
		- The size of a cluster depends on the size of the disk partition and type of file system installed on the partition
		- A large cluster size (greater than one sector) has the following effects:
			- Minimizes the fragmentation problem
			- Increases the probability of unused space in the cluster
			- Reduces the disk storage area in which information can be saved
			- Reduces the unused area on the disk
	- Lost Clusters:
		- When the OS marks clusters as used but does not allocate them to any file, such clusters are known as lost clusters
		- A lost cluster is a FAT file system error that results from the manner in which the FAT file system allocates space and chains files together
		- It is mainly the result of a logical structure error and not a physical disk error
		- They usually occur because of interrupted file activities caused when, for example, a file is not properly closed; thus, the clusters involved in such activity are never linked correctly to a file
		- CHKDSK is a system tool in Windows that authenticates the file system reliability of a volume and repairs logical file system errors
	- Slack Space:
		- Slack space is the storage area of a disk between the end of a file and the end of a cluster
		- If the file size is less than the cluster size, a full cluster is still assigned to that file. The remaining unused space is called slack space.

		- File Slack Types: 
			- RAM slack: RAM slack is the data storage space that starts from the end of a file to the end of the last sector of the file
			- Drive slack: Drive slack is the data storage space that starts from the end of the last sector of a file to the end of the last cluster of the file

	- Master Boot Record (MBR)
		- A master boot record (MBR) is the first sector ("sector zero") of a data storage device such as a hard disk
		- The information regarding the files on the disk, their locations and sizes, and other important data is stored in the MBR file
		- In practice, MBR almost always refers to the 512-byte boot sector (or partition sector) of a disk
		- MBR is used for the following:
			- Holding a partition table which refers to the partitions of a hard disk
			- Bootstrapping an OS
			- Distinctively recognizing individual hard disk media with a 32-bit disk signature
		- The MBR consists of the following structures:
			- Partition Table
			- Master Boot Code
				- Examines the partition table to find the active partition
				- Locates the first sector of the active partition
				- Loads a boot sector copy from the active partition into memory
				- Transfers control to the executable code in the boot sector
		- Structure of a Master Boot Record
			- Master Boot Code or Boot Strap: It is an executable code and responsible for loading OS into computer memory. It consists of a data structure of 446 bytes.
			- Partition Table: It maintains the data of all the hard disk partitions and consists of a data structure 64 bytes
			- Disk Signature: It is located at the end of the MBR and contains only 2 bytes of data. It is required by BIOS during booting.
		- Backing up MBR
			- dd if=/dev/xxx of=mbr.backupbs=512 count=1
		- Restoring MBR
			- dd if=mbr.backup of=/dev/xxx bs=512 count=1

	- Disk Partitions: 
		- Disk partitioning is the creation of logical divisions on a storage device (HDD/SSD) to allow the user to apply OS-specific logical formatting
		- The disk-partitioning process is the same for both HDDs and SSDs

		- Primary partition: 
			- It is the drive that holds information regarding the OS, the system area, and other information required for booting. 
			- In MS-DOS and earlier versions of Microsoft Windows systems, the first partition (C:) must be a primary partition.
		- Extended partition: 
			- It is the logical drive that holds information regarding the data and files stored on the disk.

	- BIOS Parameter Block (BPB)
		- The BIOS parameter block (BPB) is a data structure in the partition boot sector
		- It describes the physical layout of a data storage volume, such as the number of heads and the size of the tracks on the drive
		- BPB in file systems such as FAT12 (except in DOS 1.x), FAT16, FAT32, HPFS (High Performance File System), and NTFS (New Technology File System) defines the filesystem structure
		- The BPB length varies for FAT16, FAT32, and NTFS boot sectors due to different types of fields and the amount of data stored in them
		- BPB assists investigators to locate the file table on the hard drive

	- Globally Unique Identifier (GUID): Is a 128-bit unique number generated by the Windows OS for identifying a specific device, a document, a database entry, and/or the user. In general, GUIDs are displayed as 32 hexadecimal digits with groups separated by hyphens. 
		- Common Uses:
			- In Windows Registry, GUIDs are used to identify COM (Component Object Model) DLLs (dynamic-link libraries)
			- In database tables, GUIDs are used as primary key values
			- In some instances, a website may assign a GUID to a user’s browser to record and track the session
			- Windows assigns a GUID to a username to identify user accounts

	- GUID Partition Table (GPT)
		- Unified Extensible Firmware Interface (UEFI) replaces legacy BIOS firmware interfaces
		- UEFI is a specification that defines a software interface between an OS and platform firmware
		- It uses a partition system known as GUID Partition Table (GPT), which replaces the traditional MBR

		- Advantages of the GPT disk layout:
			- Supports a maximum partition size ranging from 2 Tebibytes (TiB) to 8 Zebibytes (ZiB)
			- It allows users to have 128 partitions in Windows using the GPT partition layout
			- GPT partition and boot data are more secure than MBR because GPT stores data in multiple locations across a disk
			- Provides primary and backup partition tables for redundancy
			- It uses cyclic redundancy checks (CRCs) to ensure data integrity
			- Uses CRC32 checksums that detect errors in the header and partition table

- Booting Process of Windows, Linux, and Mac Operating Systems 
	- What is the Booting Process?
		- Booting refers to the process of starting or restarting the OS when the user turns on a computer system
		- It loads the OS (stored in the hard disk) to the RAM (working memory)
	- Types of Booting:
		- Cold boot (Hard boot): This process occurs when the user first turns on the computer. Also called as hard booting, this is required after the user completely cuts the power supply to the system.
		- Warm boot (Soft boot): It is the process of restarting a computer that is already turned on. A warm boot might occur when the system encounters a program error or requires a restart to make certain changes after installing a program, etc.
	- Essential Windows System Files:
		- Ntoskrnl.exe Executive and kernel
		- Ntkrnlpa.exe Executive and kernel with support for Physical Address Extension (PAE)
		- Hal.dll Hardware abstraction layer
		- Win32k.sys Kernel-mode part of the Win32 subsystem
		- Ntdll.dll Internal support functions and system service dispatch stubs to executive functions
		- Kernel32.dll Win32 subsystem DLL files
		- Advapi32.dll Win32 subsystem DLL files
		- User32.dll Win32 subsystem DLL files
		- Gdi32.dll Win32 subsystem DLL files
	- Windows Boot Process: BIOS-MBR Method
		- Windows XP, Vista, and 7 OSes power on and start up using the traditional BIOS-MBR method
		- OSes starting from Windows 8 and above use either the traditional BIOS-MBR method or newer UEFI-GPT method according to the user’s choice

		- When the user switches the system ON, the CPU sends a Power Good signal to the motherboard and checks for the computer’s BIOS firmware
		- BIOS starts a power-on self-test (POST), which checks if all the hardware required for system boot are available and loads all the firmware settings from non-volatile memory onto the motherboard
		- If POST is successful, add-on adapters perform a self-test for integration with the system
		- The pre-boot process is completed with POST, detecting a valid system boot disk
		- After POST, the computer’s firmware scans the boot disk and loads the master boot record (MBR), which searches for basic boot information in Boot Configuration Data (BCD)
		- MBR triggers Bootmgr.exe, which locates the Windows loader (Winload.exe) on the Windows boot partition and triggers Winload.exe
		- The Windows loader loads the OS kernel ntoskrnl.exe
		- Once the Kernel starts running, the Windows loader loads hal.dll, boot-class device drivers marked as BOOT_START, and the SYSTEM registry hive into the memory
		- The kernel passes the control of the boot process to the Session Manager Process (SMSS.exe), which loads all other registry hives and drivers required to configure the Win32 subsystem run environment
		- The Session Manager Process triggers Winlogon.exe, which presents the user login screen for user authorization
		- The Session Manager Process initiates the Service Control Manager, which starts all the services, the rest of the non-essential device drivers, the security subsystem LSASS.EXE, and Group Policy scripts
		- Once user logs in, Windows creates a session for the user
		- The Service Control Manager starts explorer.exe and initiates the Desktop Window Manager (DMW) process, which initializes the desktop for the user

	- Identifying the MBR Partition

	- Windows Boot Process: UEFI-GPT
		- Security phase
		- Pre-EFI initialization phase
		- Driver Execution Environment phase
		- Boot Device Selection phase
		- Runtime phase

	- Identifying the GUID Partition Table (GPT)
		- Get-GPT
			- It parses the GPT data structure contained within the first few sectors of the device specified
			- It requires the use of the -Path parameter, which takes the Win32 device namespace (e.g., \\.\PHYSICALDRIVE1) for the device from which the GPT should be parsed
			- If Get-GPT is run against a disk formatted with an MBR, it will throw an error prompting to use Get-MBR instead
		- Alternate Method:
			- Open “Computer Management” application and click “Disk Management” on the left pane. Right-click on the primary disk (here, Disk 0) and then click Properties.
			- In the Device Properties window, click “Volumes” tab to view the Partition style Investigators can use cmdlets given below in Windows PowerShell to identify the presence of GPT:
		- Get-BootSector
			- It reviews the hard drive's first sector and determines if the disk is formatted using the MBR or GPT partitioning scheme; once done, it acts just as Get-MBR or Get-GPT would, respectively
		- Get-PartitionTable

	- Analyzing the GPT Header and Entries
		- Most OSes that support GPT disk access provide a basic partitioning tool, which displays details about GPTs
		- Example: DiskPart tool (Windows), OS X Disk utility (Mac), GNU Parted tool (Linux)
		- Sleuthkit (mmls command) can be used to view the detailed partition layout for a GPT disk
		- Alternatively, details about the GPT header and partition entries can be obtained via manual analysis using a hex editor

	- GPT Artifacts
		- Deleted and Overwritten GUID Partitions
			- Case 1:
				- If the MBR disk is repartitioned or converted to GPT, then sector zero will be generally overwritten with a protective MBR
				- To recover data from previously MBR-partitioned volumes, investigators can use standard forensic methods used to perform an extensive search for file systems
			- Case 2:
				- If the GPT disk is repartitioned or converted to MBR, then the GPT header and tables may remain intact based on the tool used
				- Implementation of general partition deletion tools on a GPT disk might only delete the protective MBR, which can be recreated by simply reconstructing the disk
			- As per UEFI specifications, if all the fields in a partition entry are zeroed, it implies that the entry is not in use. In this case, data recovery from deleted GUID partition entries is not possible

		- GUID Identifiers
			- The GPT scheme provides GUIDs of investigative value as they are unique and hold potentially useful information within them
			- GUIDs possess unique identifying information for both disks and individual partitions
			- Investigators can use tools such as uuid to decode various versions of GUID/UUID
		- Hidden Information on GPT Disks
			- Intruders may hide data on GPT disks as they do it on traditional MBR disks
			- Locations on GPT disks where data may be hidden are inter-partition gaps, unpartitioned space towards the end of the disk, GPT header, and reserved areas
			- Current forensic methods and tools to perform GPT analysis are unsatisfactory

	- Macintosh Boot Process
		- The Macintosh boot process starts with the activation of BootROM, which initializes system hardware and selects an OS to run
		- Once the Macintosh system is powered on, BootROM performs POST to test some hardware interfaces required for startup
		- On PowerPC-based Macintosh computers, Open Firmware initializes the rest of the hardware interfaces
		- On Intel-based Macintosh computers, EFI initializes the rest of the hardware interfaces
		- After initializing the hardware interfaces, the system selects the OS
		- If the system contains multiple OSes, then it allows the user to choose a particular OS by holding down the Option key
		- Once the BootROM operation is completed, the control passes to the BootX (PowerPC) or boot.efi (Intel) boot loader, which is located in the /System/Library/CoreServices directory
		- The boot loader loads a pre-linked version of the kernel located at /System/Library/Caches/com.apple.kernelcaches
		- If the pre-linked kernel is missing, the boot loader attempts to load the mkext cache file, which contains a set of device drivers
		- If the mkext cache file is also missing, the boot loader searches for drivers in the /System/Library/Extensions directory
		- Once the essential drivers are loaded, the boot loader starts the initialization of the kernel, Mach, and BSD data structures, as well as the I/O kit
		- The I/O kit uses the device tree to link the loaded drivers to the kernel
		- The launchd process, which has replaced the mach_init process, runs startup items and prepares the system for the user

	- Linux Boot Process
		- BIOS Stage
		- Bootloader Stage
		- Kernel Stage

- File Systems of Windows, Linux, and Mac Operating Systems 
	- Windows File Systems
		- File Allocation Table (FAT)
			- The FAT file system is used with DOS, and it was the first file system used with the Windows OS
			- It is named for its method of organization, the file allocation table, which resides at the beginning of the volume
			- FAT has three versions (FAT12, FAT16, and FAT32), which differ in terms of the size of the entries in the FAT structure
		- New Technology File System (NTFS)
			- NTFS is the standard file system of Windows NT and its descendants Windows XP, Vista, 7, 8.1,10, Server 2003, Server 2008, Server 2012, Server 2016 and Server 2019
			- From Windows NT 3.1 onwards, it is the default file system of the Windows NT family
			- It has several improvements over FAT such as improved support for metadata and the use of advanced data structures to improve performance, reliability, and disk-space utilization, as well as additional extensions such as security access-control lists and file system journaling

			- Features of NTFS:
				- NTFS uses the b-tree directory scheme to store information about file clusters
				- NTFS stores the information about a file’s clusters and other data within the cluster
				- NTFS supports files of size up to approximately 16 billion bytes
				- An access-control list (ACL) allows the server administrator to access specific files
				- NTFS features integrated file compression
				- NTFS provides data security on both removable and fixed disks

			- NTFS Architecture
				- Hard disk
				- Master Boot Record
				- Boot sector: Also known as volume boot record (VBR)
				- Ntldlr.dll: As a boot loader, it accesses the NTFS filesystem and loads contents of the boot.ini file
				- Ntfs.sys
				- Kernel mode
				- User mode

			- NTFS System Files
				- $attrdef Contains definitions of all system-and user-defined attributes of the volume
				- $badclus Contains all the bad clusters
				- $bitmap Contains bitmap for the entire volume
				- $boot Contains the volume's bootstrap
				- $logfile Used for recovery purposes
				- $mft Contains a record for every file
				- $mftmirr Mirror of the MFT used for recovering files
				- $quota Indicates disk quota for each user
				- $upcase Converts characters into uppercase Unicode
				- $volume Contains volume name and version number

		- Encrypting File Systems (EFS)
			- Encrypting File System (EFS) was first introduced in version 3.0 of NTFS and offers file system-level encryption
			- This encryption technology maintains a level of transparency to the user who encrypted the file, which means there is no need for users to decrypt the file to access it to make changes
			- After a user is done with the file, the encryption policy is automatically restored
			- When any unauthorized user tries to access an encrypted file, they are denied access
			- To enable the encryption and decryption facilities, a user must set the encryption attributes of the files and folders they wish to encrypt or decrypt

			- Components of EFS:
				- EFS Service
				- EFS Driver
				- CryptoAPI
				- EFS FSRTL
				- Win32 API

		- Sparse Files
			- Sparse files provide a method of saving disk space for files by allowing the I/O subsystem to allocate only meaningful (nonzero) data
			- If NTFS marks a file as sparse, it assigns a hard disk cluster only for the data defined by the application
			- Non-defined data of the file are represented by non-allocated space on the disk


	- Linux File Systems
		- Linux File System Architecture
			- User space
			- Kernel space
		- Filesystem Hierarchy Standard (FHS): Some Linux file-system types are Minix, Filesystem Hierarchy Standard (FHS), ext, ext2, ext3, xia, MS-DOS, UMSDOS, VFAT, /proc, NFS, ISO 9660, HPFS, SysV, SMB, and NCPFS. Minix was Linux’s first file system.
			- The Filesystem Hierarchy Standard (FHS) defines the directory structure and its contents in Linux and Unix-like OSes
			- In FHS, all files and directories are present under the root directory (represented by /)		

			- /bin Essential command binaries; e.g., cat, ls, cp
			- /boot Static files of the boot loader; e.g., Kernels, Initrd
			- /dev Essential device files; e.g., /dev/null
			- /etc Host-specific system configuration files
			- /home Users’ home directories, which hold saved files, personal settings, etc.
			- /lib Essential libraries for the binaries in /bin/ and /sbin/
			- /media Mount points for removable media
			- /mnt Temporarily mounted file systems
			- /opt Add-on application software packages
			- /root Home directory for the root user
			- /proc Virtual file system providing process and kernel information as files
			- /run Information about running processes; e.g., running daemons, currently logged-In users
			- /sbin Contains the binary files required for working
			- /srv Site-specific data for services provided by the system
			- /tmp Temporary files
			- /usr Secondary hierarchy for read-only user data
			- /var Variable data; e.g., logs, spool files, etc.

		- Extended File System (ext)
			- The extended file system (ext) is the first file system for the Linux OS to overcome certain limitations of the Minix file system
			- It has a maximum partition size of 2 GB and a maximum filename size of 255 characters
			- It removes the two major Minix file system limitations: a maximum partition size of 64 MB and short filenames
			- The major limitation of this file system is that it does not support separate access, inode modification, and data-modification timestamps
			- It was replaced by the second extended file system (ext 2)

		- Second Extended File System (ext2)
			- ext2 is a standard file system that uses improved algorithms compared to ext, which greatly enhances its speed; further, it maintains additional time stamps
			- It maintains a special field in the superblock that keeps track of the file system status and identifies it as either clean or dirty
			- Its major shortcomings are the risk of file system corruption when writing to ext2, and the lack of journaling

			- Superblock: A superblock stores information about the size and shape of the ext2 file system.
				- Magic number: It allows the mounting software to verify the Superblock for the ext2 file system. For the present ext2 version, it is 0xEF53.
				- Revision level: The major and minor revision levels allow the mounting code to determine whether a file system supports features that are only available in particular revisions of the file system. There are also feature compatibility fields that help the mounting code in determining which new features can safely be used on the file system.
				- Mount count and maximum mount count: Together, these allow the system to determine if it needs to fully check the file system. The mount count is incremented each time the system mounts the file system. When the mount count reaches the maximum mount count, the warning message “maximal mount count reached, running e2fsck is recommended” is displayed.
				- Block group number: It is the block-group number containing the superblock copy
				- Block size: It contains information on the size of a block for the file system in bytes
				- Blocks per group: It is a fixed number equal to the number of blocks in a group
				- Free blocks: It is the number of free blocks in the file system
				- Free inodes: It is the number of free inodes in the file system
				- First inode: It is the inode number of the first inode of the file system
			- Group Descriptor
				- Block bitmap: It is the block number of the block allocation bitmap for the block group. It is used in block allocation and deallocation.
				- Inode bitmap: It is the block number of the inode allocation bitmap for the block group. It is used in inode allocation and deallocation.
				- Inode table: It is the block number of the starting block for the inode table for the block group
				- Free block count, free inode count, and used directory count: All the group descriptors together constitute the group descriptor table. Every block group has the whole group descriptor table.

		- Third Extended File System (ext3)
			- ext3 is a journaling version of the ext2 file system and is greatly used in the Linux OS
			- It uses file system maintenance utilities (such as fsck) for maintenance and repair, as in the ext2 file system
			- It is an enhanced version of the ext2 file system
			- The following command converts ext2 to ext3 file system: # /sbin/tune2fs -j <partition-name>

			- Features of Ext3
				- Data integrity: It provides stronger data integrity for events that occur because of computer-system shutdowns. It allows the user to choose the type and level of protection for the received data.
				- Speed: As the ext3 file system is a journaling file system, it has a higher throughput in most cases than ext2. The user can choose the optimized speed from three different journaling modes.
				- Easy transition: The user can easily change the file system from ext2 to ext3 and increase the performance of the system by using the journaling file system without reformatting.

		- Journaling File System
			- Journaling file systems ensure data integrity on a computer
			- These file systems consist of a journal that records all the information on the updates that are ready to be applied to the file system before they are applied. This mechanism is referred to as journaling.
			- Journaling prevents data corruption by restoring the data on the hard disk to the state it existed in before the occurrence of a system crash or power failure. This helps the system to resume the completion of tasks or updates that were interrupted by an unexpected event.
			- ext3, ext4, ZFS, and XFS are some of the examples of journaling file systems in Linux. Because of its stability, ext4 is the most commonly implemented file system on Linux systems.

		- Fourth Extended File System (ext4)
			- ext4 is a journaling file system developed as the replacement of the commonly used ext3 file system
			- With the incorporation of new features, ext4 has significant advantages over ext3 and ext2 file systems, particularly in terms of performance, scalability, and reliability
			- It supports Linux Kernel v2.6.19 onwards

			- Key Features:
				- File System Size: Ext4 supports maximum individual file sizes up to 16 TB and maximum volumes sizes of about 1 EiB (exbibyte)
				- Extents: It replaces the block mapping scheme found in ext2 and ext3 to increase performance and reduce fragmentation
				- Delayed allocation: It improves performance and reduces fragmentation by effectively allocating larger amounts of data at a time by delaying allocation till the system flushes data to the disk
				- Multiblock allocation: It allocates multiple files contiguously on a disk, thereby reducing the work of calling the block allocator and optimizing memory allocation
				- Increased file system checking (fsck) speed: It marks unallocated block groups and sections and skips the marked elements while performing checks. Thus, it supports faster file system checking.
				- Journal check summing: It uses checksums in the journal to improve reliability
				- Persistent pre-allocation: The file system can pre-allocate the on-disk space for a file by writing zeroes to it during creation
				- Improved timestamps: It provides timestamps measured in nanoseconds and has support for date-created timestamps
				- Backwards compatibility: The file system is backwards compatible and allows the user to mount ext3 and ext2 as ext4

	- macOS File Systems
		- UNIX File System (UFS)
			- UFS is derived from the Berkeley Fast File System (FFS) that was originally developed at Bell Laboratories from the first version of UNIX FS
			- All BSD UNIX derivatives including FreeBSD, NetBSD, OpenBSD, NeXTStep, and Solaris use a variant of UFS
		- Hierarchical File System (HFS)
			- Developed by Apple Computer, Inc. to support macOS
		- HFS Plus
			- HFS Plus (HFS+) is the successor to HFS and is used as the primary file system in Macintosh
		- Apple File System (APFS)
			- It is a proprietary file system developed by Apple Inc. for macOS 10.13 and later versions

		- UNIX File System (UFS)
			- A few blocks at the beginning of the partition reserved for boot blocks, which must be initialized separately from the file system
			- A superblock, including a magic number identifying the file system as UFS, and some other vital numbers describing this file system’s geometry, statistics, and behavioral tuning parameters
			- A collection of cylinder groups, each of which has the following components:
				- A backup copy of the superblock
				- A cylinder group header with statistics, free lists, etc., which is similar to those in the superblock
				- Numerous inodes, each containing file attributes
				- Numerous data blocks

		- Hierarchical File System Plus (HFS+)
			- HFS+ is the successor to HFS and used as the primary file system in Macintosh
			- It supports large files and uses Unicode for naming items (files and folders)
			- It is also called macOS Extended (HFS Extended) and is one of the formats used in the Apple iPod
			- The HFS Plus allows user to:
				- Efficiently use hard disk space
				- Use only international-friendly filenames
				- Easily boot on non-Mac OSes
			- The following are a few of the features added to HFS+:
				- HFS+ uses B-tree to store data
				- It supports files 64 bits in length
				- It permits filenames 255 characters in length
				- It uses a 32-bit allocation table for the mapping table, unlike the 16-bits allocation table in HFS
			- HFS+ enables the following:
				- Efficient use of hard disk space
				- Use of only international-friendly filenames
				- Easy booting on non-Mac OSes

		- Apple File System (APFS)
			- APFS (Apple File System), is a file system developed and introduced by Apple for MacOS High Sierra and later versions as well as iOS 10.3 and later versions in the year 2017
			- It replaced all the file systems used by Apple and is suitable for all Apple OSes including iOS, watchOS, tvOS, and macOS

			- The Apple File System (APFS) comprises of two layers:
				- The container layer: It organizes information on the file-system layer and stores higherlevel information such as volume metadata, encryption state, and snapshots of the volume
				- The file-system layer: It consists of data structures that store information such as file metadata, file content, and directory structures


- File System Examination 
	- File System Analysis Using Autopsy
		- Autopsy is a digital forensics platform and graphical interface to The Sleuth Kit (TSK) and other digital forensics tools
		- It can be used to investigate activities on a computer

		- Timeline analysis: Advanced graphical event viewing interface (video tutorial included)
		- Hash filtering: Flags known bad files and ignores known good files
		- Keyword search: Indexed keyword search to find files that mention relevant terms
		- Web artifacts: Extracts history, bookmarks, and cookies from Firefox, Chrome, and Internet Explorer
		- Data carving: Recovers deleted files from unallocated space using PhotoRec
		- Multimedia: Extracts Exif files from pictures and videos
		- Indicators of compromise: Scans a computer using Structured Threat Information Expression (STIX)

	- File System Analysis Using The Sleuth Kit (TSK)
		- The Sleuth Kit (TSK) is a library and a collection of command-line tools that allow the investigation of volume and file system data
		- The file system tools allow you to examine file systems of a suspect computer in a non-intrusive fashion
		- It supports DOS partitions, BSD partitions (disk labels), Mac partitions, Sun slices (Volume Table of Contents), and GPT disks
		- It analyzes raw (i.e. dd), Expert Witness (i.e. EnCase), and AFF file systems and disk images
		- It supports the NTFS, FAT, ExFAT, UFS 1, UFS 2, ext2, ext3, ext4, HFS, ISO 9660, and YAFFS2 file systems

	- Recovering Deleted Files from Hard Disks using WinHex https://x-ways.net
		- WinHex is a hexadecimal editor, used for computer forensics, data recovery, low-level data processing, and IT security
		- It is mainly used to inspect and edit all types of files and to recover deleted files or lost data from hard drives with corrupt file systems or from memory cards of digital cameras

		- Features:
			- Disk editor for hard disks, floppy disks, CD-ROMs, DVDs, ZIP files, SmartMedia cards, etc.
			- Native support for FAT12/16/32, exFAT, NTFS, Ext2/3/4, Next3®, CDFS, and UDF
			- Built-in interpretation of RAID systems and dynamic disks
			- Various data recovery techniques
			- RAM editor, providing access to physical RAM and virtual memory of other processes
			- Data interpreter
			- Editing data structures using templates
			- Concatenating and splitting files; unifying and dividing odd and even bytes/words
			- Analyzing and comparing files
			- Flexible search and replace
			- Disk cloning
			- Drive images and backups
			- Application programming interface (API) and scripting
			- 256-bit AES encryption, checksums, CRC32, hashes (MD5, SHA-1, etc.)
			- Securely erasing (wiping) confidential files and cleansing hard drives
			- Importing from all clipboard formats, including ASCII hex values


# Module 04: Data Acquisition and Duplication 

- Data Acquisition Fundamentals 
	- Data acquisition is the use of established methods to extract Electronically Stored Information (ESI) from suspect computer or storage media to gain insight into a crime or an incident
	- Investigators must be able to verify the accuracy of acquired data, and the complete process should be auditable and acceptable in the court

	- Data Acquisition Categories
		- Live Acquisition: It involves collecting data from a system that is powered ON 
		- Dead Acquisition (Static Acquisition): It involves collecting data from a system that is powered OFF

	- Live Acquisition
		- Live data acquisition involves collecting volatile data from a live system
		- Volatile information assists in determining the logical timeline of the security incident, and the possible users responsible
		- Live acquisition can then be followed by static/dead acquisition, where an investigator shuts down the suspect machine, removes the hard disk and then acquires its forensic image

		- Types of data captured during live acquisition
			- System Data
				- Current configuration
				- Running state
				- Date and time
				- Current system uptime
				- Running processes
				- Logged on users
				- DLLs or shared libraries
				- Swap files and temp files
			- Network Data
				- Routing tables
				- ARP cache
				- Network configuration
				- Network connections

		- Order of Volatility: When collecting evidence, an investigator needs to evaluate the order of volatility of data depending on the suspect machine and the situation
			- According to the RFC 3227, below is an example of the order of volatility for a typical system:
				- Registers, processor cache: The information in the registers or the processor cache on the computer exists for nanoseconds. It is constantly changing and can be classified as the most volatile data.
				- Routing table, process table, kernel statistics, and memory: The routing table, ARP cache, and kernel statistics reside in the ordinary memory of the computer. These are slightly less volatile than the information in the registers, with a life span of about ten nanoseconds.
				- Temporary system files: Temporary system files tend to persist for a longer time on the computer compared to routing tables and ARP caches. These systems are eventually overwritten or changed, sometimes in seconds or minutes later.
				- Disk or other storage media: Anything stored on a disk stays for a while. However, sometimes due to unforeseen events, these data can be erased or overwritten. Therefore, disk data may also be considered somewhat volatile, with a lifespan of some minutes.
				- Remote logging and monitoring data related to the target system: Data that pass through a firewall cause a router or switch to generate logs. The system might store these logs elsewhere. These logs may overwrite themselves within an hour, a day, or a week. However, these are generally less volatile data.
				- Physical configuration and network topology: Physical configuration and network topology are less volatile and have a longer life span than some other logs
				- Archival media: A DVD-ROM, a CD-ROM, or a tape contains the least volatile data because the digital information does not change in such data sources automatically unless damaged under a physical force

	- Dead Acquisition
		- Dead acquisition is defined as the acquisition of data from a suspect machine that is powered off
		- Dead acquisition usually involves acquiring data from storage devices such hard drives, DVDROMs, USB drives, flash cards, and smart phones
		- Examples of static data: emails, word documents, web activity, spreadsheets, slack space, unallocated drive space, and various deleted files
		- Static data recovered from a hard drive include the following:
			- Temporary (temp) files
			- System registries
			- Event/system logs
			- Boot sectors
			- Web browser cache
			- Cookies and hidden files
	
		- Rules of Thumb for Data Acquisition
			- Do not work on original digital evidence. Create a bitstream/logical image of a suspicious drive/file to work on.
			- Use clean media to store the copies
			- Produce two or more copies of the original media
				- The first is the working copy to be used for analysis
				- The other copies act as the library/control copies that are stored for disclosure purposes or in the event that the working copy gets corrupt
			- Upon creating copies of original media, verify the integrity of copies with the original


- Types of Data Acquisition 
	- Logical Acquisition
		- Logical acquisition allows an investigator to capture only selected files or files types of interest to the case
		- Examples of logical acquisition include:
			- Email investigation that requires collection of Outlook .pst or .ost files
			- Collecting specific records from a large RAID server
	- Sparse Acquisition
		- Sparse acquisition is similar to logical acquisition, which in addition collects fragments of unallocated data, allowing investigators to acquire deleted files
		- Use this method when inspection of the entire drive is not required
	- Bit-Stream Imaging: Bit-stream imaging creates a bit-by-bit copy of a suspect drive, which is a cloned copy of the entire drive including all its sectors and clusters, which allows forensic investigators to retrieve deleted files or folders
		- Bit-stream disk-to-image file
			- It is the most common method used by forensic investigators
			- The created image file is a bit-by-bit replica of the suspect drive
			- Tools used: ProDiscover, EnCase, FTK, The Sleuth Kit, X-Ways Forensics, etc.
		- Bit-stream disk-to-disk
			- Disk-to-image copying is not possible in situations where
				- The suspect drive is very old and incompatible with the imaging software
				- Investigator needs to recover credentials used for websites and user accounts
			- To overcome this situation, investigators can create a diskto-disk bit-stream copy of the target media
			- While creating a disk-to-disk copy, investigators can adjust the target disk’s geometry (its head, cylinder, and track configuration) to align with the suspect drive. This results in smooth data acquisition process.
			- Tools used: Encase, Tableau Forensic Imager, etc.


- Data Acquisition Format 
	- Raw Format: Raw format creates a bit-by-bit copy of the suspect drive. Images in this format were are usually obtained by using the dd command.
		- Advantages 
			- Fast data transfers
			- Minor data read errors on source drive are ignored
			- Read by most of the forensic tools
		- Disadvantages
			- Requires same amount of storage as that of the original media
			- Tools (mostly open source) might fail to recognize/collect marginal (bad) sectors from the suspect drive

	- Proprietary Format: Commercial forensics tools acquire data from the suspect drive and save the image files in their own formats
		- They offer certain features which include the following:
			- Option to compress the image files of the evidence disk/drive in order to save space on the target media
			- Ability to split an image into multiple segments, in order to save them to smaller target media such as CD/DVD, while maintaining their integrity
			- Ability to incorporate metadata into the image file, which includes date and time of acquisition, hash values of the files, case details, etc.
		- Disadvantages
			- Image file format created by one tool may not be supported by other tool(s)

	- Advanced Forensics Format (AFF)
		- Advanced Forensics Format is an open source acquisition format with the following design goals
			- No size limitation for disk-to-image files
			- Option to compress the image files
			- Allocates space to record metadata of the image files or segmented files
			- Simple design and customizable
			- Accessible through multiple computing platforms and OSes
			- Internal consistency checks for selfauthentication
		- File extensions include .afm for AFF metadata and .afd for segmented image files
		- AFF supports the following two compression algorithms:
			- Zlib, which is faster but less efficient
			- LZMA, which is slower but more efficient

	- Advanced Forensic Framework 4 (AFF4)
		- Redesign and revision of AFF to manage and use large amounts of disk images, reducing both acquisition time and storage requirements
		- Basic types of AFF4 objects: volumes, streams, and graphs. They are universally referenced through a unique URL.
			- Volumes: They store segments, which are indivisible blocks of data
			- Streams: These are data objects that can help in reading or writing, for example, segments, images, and maps
			- Graphs: Collections of RDF statements
		- Abstract information model that allows storage of disk-image data in one or more places while the information about the data is stored elsewhere
		- Stores more kinds of organized information in the evidence file
		- Offers unified data model and naming scheme


- Data Acquisition Methodology 
	- Determining the data acquisition method
		- An investigator needs to identify the best data acquisition method suitable for the investigation, depending on the situation the investigator is presented with
		- These situations include:
			- Size of the suspect drive
			- Time required to acquire the image
			- Whether the investigator can retain the suspect drive
		- Example:
			- In case the original evidence drive needs to be returned to the owner, as in the case of a discovery demand for a civil litigation case, check with the requester (lawyer or supervisor) whether logical acquisition of the disk is acceptable. If not, you may have to go back to the requester.
		- Investigators need to acquire only the data that is intended to be acquired

	- Determining the data acquisition tool
		- Mandatory Requirements
			- The tool should not change the original content
			- The tool should log I/O errors in an accessible and readable form, including the type of the error and location of the error
			- The tool must have the ability to pass scientific and peer review. Results must be repeatable and verifiable by a third party if necessary.
			- The tool should alert the user if the source is larger than the destination
			- The tool should create a bit-stream copy of the original content when there are no errors in accessing the source media
			- The tool should create a qualified bit-stream copy (a qualified bitstream copy is defined as a duplicate except in identified areas of the bit-stream) when I/O errors occur while accessing the source media
		- Optional requirements
			- The tool should compute a hash value for the complete bit-stream copy generated from a source image file, compare it with the source hash value computed at the time of image creation, and display the result on a disk file
			- The tool should divide the bit-stream copy into blocks, compute hash values for each block, compare them with the hash value of original block data computed at the time of image creation, and display the result on a disk file
			- The tool should log one or more items on a disk file (items include tool version, subject disk identification, any errors encountered, tool actions, start and finish run times, tool settings, and user comments)
			- The tool should create a qualified bit-stream duplicate and adjust the alignment of cylinders to cylinder boundaries of disk partitions when the destination is of a different physical geometry
			- The tool should create a bit-stream copy of individual partitions as per user direction
			- The tool should make the source disk partition table visible to users, and record its contents
			- The tool should create an image file on a fixed or removable magnetic or electronic media that is used to create a bit-stream copy of the original
			- The tool should create a bit-stream copy on a platform that is connected through a communications link to a different platform containing the source disk

	- Sanitizing the target media
		- Investigators must properly sanitize the target media in order to any prior data residing on it, before it is used for collecting forensic data
		- Post investigation, they must dispose this media by following the same standards, so as to mitigate the risk of unauthorized disclosure of information, and ensure its confidentiality
		- The following are some standards for sanitizing media:
			- Russian Standard, GOST P50739-95
				- (6 passes): It is a wiping method that writes zeros in the first pass and then random bytes in the next pass
			- German: VSITR
				- (7 passes): This method overwrites in 6 passes with alternate sequences of 0x00 and 0xFF, and with 00xAA in the last (7th) pass
			- American: NAVSO P-5239-26 (MFM)
				- (3 passes): This is a three-pass overwriting algorithm that verifies in the last pass
			- American: DoD 5220.22-M
				- (7 passes): This standard destroys the data on the drive’s required area by overwriting with 010101 in the first pass, 101010 in the second pass and repeating this process thrice. This method then overwrites that area with random characters which is the 7th pass.
			- American: NAVSO P-5239-26 (RLL)
				- (3 passes): This is a three-pass overwriting algorithm that verifies in the last pass
			- NIST SP 800-88
				- Clear: Logical techniques applied to sanitize data in all storage areas using the standard read and write commands
				- Purge: Involves physical or logical techniques to make the target data recovery infeasible by using state-of-the-art laboratory techniques
				- Destroy: Enables target data recovery to be infeasible with the use of state-of-the-art laboratory techniques, which result in an inability to use the media for data storage

		- The application of complex access controls and encryption can reduce the chances for an attacker to gain direct access to sensitive information
		- An organization can dispose of the not so useful media data by internal or external transfer or by recycling to fulfill data sanitization
		- Effective sanitization techniques and tracking of storage media are crucial to ensure protection of sensitive data by organizations against attackers
		- All organizations and intermediaries are responsible for effective information management and data sanitization

	- Acquiring volatile data
		- Volatile data acquisition involves collecting data that is lost when the computer is shut down or restarted
		- This data usually corresponds to running processes, logged on users, registries, DLLs, clipboard data, open files, etc.
			- Acquire Volatile Data from a Windows Machine
				- Belkasoft Live RAM Capturer https://belkasoft.com
				- Belkasoft Live RAM Capturer is a forensic tool that allows extracting the entire contents of a computer’s volatile memory
				- It saves the image files in .mem format

	- Enabling write protection on the evidence media
		- It is necessary to write protect the suspect drive using write blockers to preserve and protect the evidence contained in it
		- A write blocker is a hardware device or software application that allows data acquisition from the storage media without altering its contents
		- It blocks write commands, thus allowing read-only access to the storage media
			- If hardware write blocker is used:
				- Install a write blocker device
				- Boot the system with the examiner-controlled operating system
				- Examples of hardware devices: CRU® WiebeTech® USB WriteBlocker, Tableau Forensic Bridges, etc.
			- If software write blocker is used:
				- Boot the system with the examiner-controlled operating system
				- Activate write protection
				- Examples of software applications: SAFE Block, MacForensicsLab Write Controller, etc.

		- The following are some measures that provide defense mechanisms against alterations:
			- Set a hardware jumper to make the disk read-only
			- Use operating system and software that cannot write to the disk unless instructed
			- Employ a hard disk write block tool to protect against disk writes

	- Acquiring non-volatile data
		- Non-volatile data can be acquired in both live acquisition and dead acquisition. It mainly involves acquiring data from a hard disk.
		- There is no significant difference in the amount of data acquired from a hard disk between the live and dead acquisition methods
		- Live Acquisition of a hard disk is performed by using remote acquisition tools (e.g. netcat), and bootable CDs or USBs (e.g. CAINE); while dead acquisition involves removing the hard disk from the suspect drive, connecting it to a forensic workstation, write-blocking the hard disk, and running a forensic acquisition tool on the disk

		- The dead acquisition process can be performed via the following steps:
			- Remove the hard drive from the suspect drive
			- Connect it to a forensic workstation to perform the acquisition
			- Write-block the hard disk to ensure that it provides only read-only access to the hard drive and prevents any modification or tampering of its contents
			- Run any forensic acquisition tool suitable for the purpose of acquiring/collecting data

		- Acquire Non-volatile Data (Using a Windows Forensic Workstation)
			- To acquire forensic image of a hard disk during dead acquisition, remove the hard disk, connect it to a forensic workstation, enable write-blocker, and run a forensic imaging tool (e.g. AccessData FTK Imager) on the workstation
			- AccessData FTK Imager is a disk imaging program which can preview recoverable data from a disk of any kind and also create copies, called forensics images, of that data

			- AccessData FTK Imager https://accessdata.com
				- Features
					- Create forensic images of local hard drives, CDs and DVDs, thumb drives, or other USB devices, entire folders, or individual files from various places within the media
					- Enables previewing files and folders on local hard drives, network drives, CDs and DVDs, thumb drives, or other USB devices
					- Enables previewing the contents of forensic images stored on a local machine or a network drive
					- Enables mounting an image for a read-only view that leverages Windows Internet Explorer to display the content of the image exactly as the user saw it on the original drive
					- Exports files and folders from forensic images
					- Recovers files that have been deleted from the Recycle Bin, but have not yet been overwritten on the drive
					- Creates hashes of files to check the integrity of the data by using either of the two hash functions available in FTK Imager: Message Digest 5 (MD5) and Secure Hash Algorithm (SHA-1)

	- Planning for contingency
		- Investigators must prepare for contingencies such as when the hardware or software does not work, or a failure occurs during acquisition
		- Hard Disk Data Acquisition
			- Investigators must create at least two images of the digital evidence collected, in order to preserve it. If one copy of the digital evidence recovered becomes corrupt, investigators can then use the other copy.
		- Imaging Tools
			- If you possess more than one imaging tool, such as Pro-iscoverForensics or AccessData FTK Imager, it is recommended to create the first image with one tool and the second image with the other tool. If you posses only one tool, make two or more images of the drive using the same tool.		
		- Hardware Acquisition Tool
			- Consider using a hardware acquisition tool (such as UFED Ultimate or IM SOLO-4 G3 IT RUGGEDIZED) that can access the drive at the BIOS level to copy data in the Host Protected Area (HPA)
		- Drive Decryption
			- Be prepared to deal with encrypted drives that need the user to provide the decryption key for decrypting. Microsoft includes a full disk encryption feature (BitLocker) with select editions of Windows Vista and later.

	- Validating data acquisition
		- Validating data acquisition involves calculating the hash value of the target media and comparing it with its forensic counterpart to ensure that the data is completely acquired
		- The unique number (hash value) is referred to as a “digital fingerprint”
		- As hash values are unique, if two files have the same hash value, they are 100% identical even if the files are named differently
		- Utility algorithms that produce hash values include CRC-32, MD5, SHA-1, and SHA-256

		- The following are some hashing algorithms that can be used to validate the data acquired:
			- CRC-32: Cyclic redundancy code algorithm-32 is a hash function based on the idea of polynomial division. The number 32 indicates that the size of the resulting hash value or checksum is 32 bits. The checksum identifies errors after data transmission or storage.
			- MD5: This is an algorithm used to check data integrity by creating a 128-bit message digest from data input of any length. Every MD5 hash value is unique to that particular data input.
			- SHA-1: Secure Hash Algorithm-1 is a cryptographic hash function developed by the United States National Security Agency, and it is a US Federal Information Processing Standard issued by NIST. It creates a 160-bit (20-byte) hash value called a message digest. This hash value is a 40 digits long hexadecimal number.
			- SHA-256: This is a cryptographic hash algorithm that creates a unique and fixed-size 256-bit (32-byte) hash. Therefore, it is ideal for anti-tamper technologies, password validation, digital signatures, and challenge hash authentication.

		- Validate Data Acquisition. Windows Validation Methods
			- Windows computers come with PowerShell utility, which has the ability to run cmdlet
			- The Get-FileHash cmdlet computes the hash value for an evidence file by using the specified hash algorithm
			- This hash value is used throughout the investigation for validating the integrity of the evidence
			- Investigators can also use commercial computer forensics programs, which have built-in validation features that can be used to validate the evidence files
			- For instance:
				- ProDiscover’s .eve files contain metadata in segmented files or acquisition files, including the hash value for the original media
				- When you load the image to ProDiscover, it compares the hash value of this image to the hash value of the original media
				- If the hashes do not match, the tool notifies that the image is corrupt, implying that the evidence cannot be considered reliable
			- Note: In most computer forensics tools, raw format image files do not contain metadata. For raw acquisitions, therefore, a separate manual validation is recommended during analysis.


# Module 05: Defeating Anti-forensics Techniques 

- Anti-forensics and its Techniques 
	- Anti-forensics (also known as counter forensics) is a common term for a set of techniques aimed at complicating or preventing a proper forensics investigation process
	- Goals of Anti-forensics
		- Interrupt and prevent information collection
		- Make difficult the investigator’s task of finding evidence
		- Hide traces of crime or illegal activity
		- Compromise the accuracy of a forensics report or testimony
		- Delete evidence that an anti-forensics tool has been run
	- Anti-forensics Techniques
		- Data/File Deletion
		- Password Protection
		- Steganography
		- Data Hiding in File System Structures
		- Trail Obfuscation
		- Artifact Wiping
		- Overwriting Data/Metadata
		- Encryption
		- Program Packers
		- Minimizing Footprint
		- Exploiting Forensics Tool Bugs
		- Detecting Forensics Tool Activities

	- Anti-forensics Technique: Data/File Deletion
		- When a file is deleted from the hard drive, the pointer to the file gets deleted but the contents of file remain on the disk
		- In other words, the deleted files can be recovered from the hard disk until the sectors containing the contents of the file are overwritten with the new data
		- Data recovery Tools such as Autopsy, Recover My Files, EaseUS Data Recovery Wizard Pro, and R-Studio can be used for recovering deleted files/folders
	- What Happens When a File is Deleted in Windows?
		- FAT File System 
			- The OS replaces the first letter of a deleted file name with a hex byte code: E5h
			- E5h is a special tag that indicates that the file has been deleted
			- The corresponding cluster of that file in FAT is marked as unused, although it will continue to contain the information until it is overwritten
		- NTFS File System
			- When a user deletes a file, the OS just marks the file entry as unallocated but does not delete the actual file contents
			- The clusters allocated to the deleted file are marked as free in the $BitMap ($BitMap file is a record of all used and unused clusters)
			- The computer now notices those empty clusters and avails that space for storing a new file
			- The deleted file can be recovered if the space is not allocated to any other file
	- Recycle Bin in Windows
		- The Recycle Bin is a temporary storage place for deleted files
		- The file remains in the Recycle Bin until you empty the Recycle Bin or restore the file
		- Items can be restored to their original positions with the help of the Restore all items option of the Recycle Bin

		- The storage location of Recycle Bin depends on type of OS and file system
			- Recycle Bin storage location on FAT file systems:
				- On older FAT file systems (Windows 98 and prior), it is located in Drive:\RECYCLED
			- Recycle Bin storage location on NTFS file systems:
				- On Windows 2000, NT, and XP it is located in Drive:\RECYCLER\<SID>
				- On Windows Vista and later versions, it is located in Drive:\$Recycle.Bin\<SID>
		
		- When a file is deleted, the complete path of the file and its name is stored in a hidden file called INFO2 ( in Windows 98) in the Recycled folder. This information is used to restore the deleted files to their original locations.
			- Prior to Windows Vista, a file in the Recycle Bin was stored in its physical location and renamed using the syntax: D<original drive letter of file><#>.<original extension>
				- “D” denotes that a file has been deleted

		- In Windows Vista and later versions, the deleted file is renamed using the syntax: $R<#>.<original extension>, where <#> represents a set of random letters and numbers
		- At the same time, a corresponding metadata file is created which is named as: $I<#>.<original extension>, where <#> represents a set of random letters and numbers the same as used for $R
		- The $R and $I files are located at C:\$Recycle.Bin\<USER SID>\
		- $I file contains following metadata:
			- Original file name
			- Original file size
			- The date and time the file was deleted

		- Recycle Bin Forensics
			- The original files pertaining to the $I files are not visible in the Recycle Bin folder when,
				- $I file is corrupted or damaged
				- The attacker/insider deletes $I files from the Recycle Bin
			- During forensic investigation, the investigator should check for the $R files in the Recycle Bin directory to counter the anti-forensic technique used by the attacker

			- If the metadata files related to the original files are not present in the folder, then the investigator can use ‘copy’ command to recover the deleted files ($R files) 
				- Command: copy <$R*(or File name)> <Destination Directory>
			- In case, the metadata of Recycle Bin is lost, or the data is hidden intentionally by the perpetrator, the investigator can follow above steps to recover the deleted files from Recycle Bin for further analysis

	- File Carving
		- It is a technique to recover files and fragments of files from the hard disk in the absence of file system metadata
		- In this technique, file identification and extraction is based on certain characteristics such as file header or footer rather than the file extension or metadata
		- A file header is a signature (also known as a magic number), which is a constant numeric or text value that determines a file format
			- Example:
				- A suspect may try to hide an image from being detected by investigators by changing the file extension from .jpg to .dll
				- However, changing the file extension does not change the file header, and analysis tells the actual file format
			- Example:
				- A file format is confirmed as .jpg if it shows “JFIF” in the file header and hex signature as “4A 46 49 46“
		- Investigators can take a look at file headers to verify the file format using tools such as 010 Editor, CI Hex Viewer, Hexinator, Hex Editor Neo, Qiew, WinHex, etc.

		- File Carving on Windows
			- Windows tracks its files/folders on a hard drive using the pointers that tells the system where the file begins and ends
			- When a file is deleted from the hard drive, the pointer to the file gets deleted but the contents of file remains on the disk
			- In other words, the deleted files can be recovered from the hard disk until the sectors containing the contents of the file are overwritten with new data
			- Data recovery Tools such as Autopsy, Recover My Files, EaseUS Data Recovery Wizard Pro, R-Studio for Windows, etc., can be used for recovering deleted files/folders from Windows

	- File Recovery Tools: Windows
		- EaseUS Data Recovery Wizard Pro https://www.easeus.com
			- EaseUS Data Recovery Wizard Pro Hard drive data recovery software to recover lost data from PC, laptop or other storage media due to deleting, formatting, partition loss, OS crash, virus attacks, etc.
			- Specifies file types before file recovery to find lost files quickly
			- Saves previous searching results for continuous recovery
			- Scans lost files faster by skipping bad sectors automatically
		- Recover My Files https://getdata.com
		- DiskDigger https://diskdigger.org
		- Handy Recovery https://www.handyrecovery.com
		- Quick Recovery https://www.recoveryourdata.com
		- Stellar Phoenix Windows Data Recovery https://www.stellarinfo.com

	- File Carving on Linux
		- When a file is deleted from Linux using the command /bin/rm/, the inode pointing to the file gets removed but the file remains on the disk until it is overwritten with new data
		- If a running process keeps a file open and then removes the file, the file contents are still on the disk, and other programs will not reclaim the space
		- It is required to note that if an executable erases itself, its contents can be retrieved from a /proc memory image. The command cp /proc/$PID/exe/tmp/file creates a copy of a file in /tmp
		- Third-party tools such as Stellar Phoenix Linux Data Recovery, R-Studio for Linux, TestDisk, PhotoRec, and Kernel for Linux Data Recovery can be used to recover deleted files from Linux

	- SSD File Carving on Linux File System
		- Forensic workstation used: Windows 10
		- The forensically acquired image from TRIM disabled SSD should be examined using file carving tools such as Autopsy, R-Studio, etc.
		- In Autopsy, the carved data from the forensic evidence file is displayed under the appropriate data source with heading “$CarvedFiles”

	- Recovering Deleted Partitions
		- The MBR partition table contains the records of the primary and extended partitions of a disk
		- When a partition is deleted from a disk, the entries with respective to deleted partition are removed by the computer from the MBR partition table
		- Investigators use tools such as R-Studio and EaseUS Data Recovery Wizard to scan the disk for lost partitions and recover them
		- These automated tools perform full disk scan, looks for deleted partition information and reconstruct the partition table entry for deleted partition

	- Recovering Deleted Partitions: Using EaseUS Data Recovery Wizard
		- When an Unallocated partition is found during forensic investigation, the investigator use automated tools such as EaseUS Data Recovery Wizard to discover lost partition and recover the data from it
		- EaseUS Data Recovery Wizard tool recovers data from the FAT and NTFS based file system partitions

- Anti-forensics Countermeasure

	- Anti-forensics Technique: Password Protection
		- While conducting forensic investigation on suspect’s computer, accessing password protected resources is one of the challenges faced by the investigator
		- In such cases, investigators can use password cracking tools such as ophcrack and RainbowCrack to circumvent the password protection
	- Password Types
		- Cleartext passwords
			- Passwords are sent and stored in plaintext without any alteration
			- Example: Windows Registry stores automatic logon password in cleartext in the registry, HKLM\SOFTWARE\Microsoft\Windows NT\CurrentVersion\Winlogon
			- Investigators can use tools such as Cain and Ettercap to sniff cleartext passwords
		- Obfuscated passwords
			- Passwords are stored or communicated after a transformation. Obfuscated passwords are encrypted using an algorithm and can be decrypted by applying a reverse algorithm
			- When transformation is reversible, password becomes unreadable when user applies an algorithm and on application of reverse algorithm, it returns to cleartext form
		- Password hashes
			- Password hashes are a signature of the original password generated using a one-way algorithm. Passwords are hashed using hash algorithms (MD5, SHA, etc.), which are not reversible
	- Password Cracking Techniques
		- Dictionary Attack
			- A dictionary file is loaded into the cracking application that runs against user accounts
			- This attack is applicable in two situations:
				- In cryptanalysis, it helps find out the decryption key for obtaining the plaintext from the ciphertext
				- In computer security, it helps avoid authentication and access to a computer by guessing passwords
			- Methods to improve the success of a dictionary attack:
				- Using more number of dictionaries, such as technical dictionaries and foreign dictionaries, can help retrieve the correct password
				- Using string manipulation; for example, if the dictionary contains the word, “system,” then try string manipulation and use “metsys” and others
		- Brute Forcing Attacks
			- The program tries every combination of characters until the password is broken
			- Some considerations for brute-force attack are as follows:
				- It is a time-consuming process
				- It can eventually trace all passwords
				- An attack against Networking Technology (NT) hash is much harder against LAN Manager (LM) hash
		- Rule-based Attack
			- This attack is used when some information about the password is known
	- Password Cracking Tools
		- Passware Kit Forensic https://www.passware.com 
			- A complete encrypted electronic evidence discovery solution that reports and decrypts all password-protected items on a computer
		- L0phtCrack https://www.l0phtcrack.com
		- ophcrack https://ophcrack.sourceforge.io
		- Cain & Abel https://www.oxid.it
		- RainbowCrack https://project-rainbowcrack.com
		- Offline NT Password & Registry Editor https://pogostick.net

	- Anti-forensics Technique: Steganography
		- Steganography is a technique of hiding a secret message within an ordinary message and extracting it at the destination to maintain confidentiality of data
		- Attacker can use steganography to hide messages such as a list of the compromised servers, source code for the hacking tool, and plans for future attacks
		- The forensic investigator examines the Stego-Object to extract the hidden information
	- Steganography Detection Tools
		- OpenStego https://www.openstego.com
			- OpenStego provides two main functionalities:
				- Data Hiding: It can hide any data within a cover file (e.g. images).
				- Watermarking (beta): Watermarking files (e.g. images) with an invisible signature. It can be used to detect unauthorized file copying.
			- It allows investigators to extract hidden data for analysis.
		- StegSpy http://www.spy-hunter.com
			- StegSpy identifies a “steganized” file and detects steganography and the program used to hide the message. It also identifies the location of the hidden content as well. StegSpy currently identifies the following programs:
				- Hiderman
				- JPHideandSeek
				- Masker
				- JPegX
				- Invisible Secrets

	- Anti-forensics Technique: Alternate Data Streams
		- Attackers use Alternate Data Streams (ADS) to hide data in Windows NTFS and cannot be revealed through command line or Windows Explorer
		- ADS allows attacker to hide any number of streams into one single file without modifying the file size, functionality, etc., except the file date
		- However, the file date can be modified using anti-forensics tools like TimeStomp
		- In some cases, these hidden ADS can be used to remotely exploit a web server

	- Anti-forensics Technique: Trail Obfuscation
		- The purpose of trail obfuscation is to confuse and mislead the forensics investigation process
		- Attackers mislead investigators via log tampering, false e-mail header generation, timestamp modification, and various file headers’ modification
		- Some of the techniques attackers use for data/trail obfuscation:
			- Log cleaners 
			- Spoofing
			- Misinformation 
			- Zombie accounts
			- Trojan commands
		- Traffic content obfuscation can be attained by means of VPNs and SSH tunneling

		- Timestomp is one of the most widely used trail obfuscation tools that allow deletion or modification of timestamp-related information on files. Procedure to defeat this technique is covered in “Detecting Overwritten Data/Metadata” section.

	- Anti-forensics Technique: Artifact Wiping
		- Artifact wiping involves various methods aimed at permanent deletion of particular files or entire file systems
		- Artifact wiping methods:
			- Disk Wiping Utilities 
				- Disk wiping involves erasing data from the disk by deleting its links to memory blocks and overwriting the memory contents
				- Some of the commonly used disk wiping utilities include BCWipe Total WipeOut, CyberScrub cyberCide, DriveScrubber, ShredIt, etc.
			- File Wiping Utilities
				- Deletes individual files and file table entries from an OS
				- Some of the commonly used file wiping utilities include BCWipe, R-Wipe & Clean, CyberScrub Privacy Suite, etc.
			- Disk Degaussing/Destruction Techniques 
				- Disk degaussing is a process by which a strong magnetic field is applied to storage device, resulting in an entirely clean device of any previously stored data
				- NIST recommends a variety of methods to accomplish physical destruction of the digital media, which includes disintegration, incineration, pulverizing, shredding, and melting
				- Intruders use disk degaussing/destruction techniques to make the evidentiary data unavailable to forensics investigators
			- Disk Formatting
				- Formatting of a hard drive does not erase the data present on the disk but wipes its address tables and unlinks all the files in the file system
				- Later, a new file tree is set up to use with OS
				- After formatting a hard disk, the forensic investigator can recover data from a formatted drive

	- Anti-forensics Technique: Overwriting Data/Metadata
		- Perpetrators use different techniques to overwrite data or metadata (or both) on a storage media thereby posing a challenge to the investigators while performing data recovery
		- Overwriting programs (disk sanitizers) work in three modes:
			- Overwrite entire media
			- Overwrite individual files
			- Overwrite deleted files on the media
		- Overwriting Metadata
			- Investigators use metadata to create a timeline of the perpetrator’s actions by arranging all the computer’s timestamps in a sequence
			- Although attackers can use tools to wipe the contents of media, that action itself might draw the attention of investigators. Therefore, attackers cover their tracks by overwriting the metadata (i.e. access times), rendering the construction of timeline difficult.
			- Ex: Timestomp (part of the Metasploit Framework) is used to change MACE (Modified-Accessed-Created-Entry) attributes of the file

	- Anti-forensics Technique: Encryption
		- Data encryption is one of the commonly used techniques to defeat forensics investigation process
		- Intruders use strong encryption algorithms to encrypt data of investigative value, which renders it virtually unreadable without the designated key
		- Additionally, most encryption programs are capable of performing additional functions, including use of a key file, full-volume encryption, and plausible deniability; that makes the investigator’s job more difficult
		- Cryptanalysis can be used to decrypt encrypted data
			- Example: CrypTool

- Anti-forensics Countermeasures
	- Some of the important countermeasures against anti-forensic techniques are listed below:
		- Train and educate the forensic investigators about anti-forensics
		- Validate the results of examination using multiple tools
		- Impose strict laws against illegal use of anti-forensics tools
		- Understand the anti-forensic techniques and their weaknesses
		- Use latest and updated CFTs and test them for vulnerabilities
		- Save data in secure locations
		- Use intelligent decompression libraries to defend against compression bombs
		- Replace weak file identification techniques with stronger ones
	- Anti-forensics Tools
		- Steganography Studio (http://stegstudio.sourceforge.net)
		- CryptaPix (https://www.briggsoft.com)
		- GiliSoft File Lock Pro (http://gilisoft.com)
		- wbStego (https://wbstego.wbailer.com)
		- Data Stash (https://www.skyjuicesoftware.com)
		- OmniHide PRO (https://omnihide.com)
		- Masker (http://softpuls.weebly.com)
		- DeepSound (http://jpinsoft.net)
		- DBAN (https://dban.org)
		- east-tec InvisibleSecrets (https://www.east-tec.com)


# Module 06: Windows Forensics 

	- Introduction to OS Forensics
		- Windows, Mac, and Linux are the three most widely used operating systems (OSes). Thus, the probability for an investigator to come across these OSes at the crime scene is very high.
		- Performing OS forensics to uncover the underlying evidence is a challenging task as it requires the investigator to have thorough knowledge of these OSes
		- To conduct a successful digital forensic examination in Windows, Mac, and Linux, one should be familiar with their working, commands or methodologies, in order to be able to extract volatile and non-volatile data with OS-specific tools

- Volatile and Non-Volatile Information
	- Collecting Volatile Information
		- Volatile information can be easily modified or lost when the system is shut down or rebooted
		- Collecting volatile information helps determine a logical timeline of the security incident and the responsible users
		- Volatile data resides in registers, cache, and RAM
	- Volatile information includes:
		- System time
		- Logged-on user(s)
		- Network information
		- Open files
		- Network connections
		- Network status
		- Process information
		- Process-to-port mapping
		- Process memory
		- Mapped drives
		- Shares
		- Clipboard contents
		- Service/driver information
		- Command history

	- Collecting System Time
		- It provides details of the information collected during the investigation
		- It helps in re-creating the accurate timeline of events that occurred on the system
		- System uptime provides an idea of when an exploit attempt might have been successful
		- Command: date /t & time /t

	- Collecting Logged-On Users
		- PsLoggedOn
			- PsLoggedOn is an applet that displays both the users logged on locally and via resources for either on the local, or a remote computer
			- Syntax: psloggedon [- ] [-l] [-x] [\\computername | username]
			- PsLoggedOn https://docs.microsoft.com
		- net sessions Command:
			- net session command displays computer and usernames on a server, open files, and duration of sessions 
			- Syntax: net sessions [\\<ComputerName>] [/delete] [/list]
			- net sessions https://docs.microsoft.com
		- LogonSessions Tool
			- It lists the currently active logon sessions and, if the -p option is specified, the processes running in each session are listed
			- Syntax: logonsessions [-c[t]] [-p]
				- -c, Print output as CSV
				- -ct, Print output as tab-delimited values
				- -p, List processes running in logon session
			- LogonSessions https://docs.microsoft.com
		- Collecting Open Files: net file Command
			- Collect information about the files opened by the intruder using remote login
			- Displays details of open shared files on a server, such as a name, ID, and the number of each file locks, if any. It also closes individually shared files and removes file locks.
			- The syntax of the net file command:
				- net file [ID [/close]]
		- Collecting Open Files: Using NetworkOpenedFiles
			- NetworkOpenedFiles is a utility for Windows OS that lists all the files currently opened on the host system through remote login
			- It displays the Filename, Computer and Username, Permission information (Read/Write/Create), Locks count, File Size, File Attributes, etc.
			- NetworkOpenedFiles https://www.nirsoft.net

	- Collecting Network Information
		- Intruders after gaining access to a remote system, try to discover other systems that are available on the network
		- NetBIOS name table cache maintains a list of connections made to other systems using NetBIOS
		- The Windows inbuilt command line utility nbtstat can be used to view NetBIOS name table cache
		- The nbtstat -c option shows the contents of the NetBIOS name cache, which contains NetBIOS name-to-IP address mappings

		- Syntax: nbtstat [-a RemoteName] [-A IP address] [-c] [-n][-r] [-R] [-RR] [-s] [-S] [interval]

		- Network information useful for investigation includes the following:
			- Data content such as header information, text, etc.
			- Session information that is relevant to the investigation
			- IDS/IPS, firewall, server, and application log data
			- Other network information such as secure file transfers
			- Network packets
			- Port scan results

	- Collecting Information about Network Connections
		- Collecting information about the network connections running to and from the victim system allows to locate logged attacker, IRCbot communication, worms logging into Command and Control server
		- Netstat with –ano switch displays details of the TCP and UDP network connections including listening ports, and the identifiers

		- Syntax: netstat [-a] [-e] [-n] [-o] [-p <Protocol>] [-r] [-s] [<Interval>]

	- Process Information
		- Investigate the processes running on a potentially compromised system and collect the information
		- Tools and commands used to collect detailed process information include:
			- Task Manager displays the programs, processes, and services that are currently running on computer
			- Tasklist
				- Tasklist displays a list of applications and services with their Process ID (PID) for all tasks running on either a local or a remote computer
				- Syntax: tasklist[.exe] [/s computer] [/u domain\user [/p password]] [/fo {TABLE|LIST|CSV}] [/nh] [/fi FilterName [/fi FilterName2 [ ... ]]] [/m [ModuleName] | /svc | /v]
			- PsList
				- PsList displays elementary information about all the processes running on a system
				- -x switch shows processes, memory information, and threads
		- An Investigator can retrieve all process information by looking for the details listed below:
			- The full path to the executable image (.exe file)
			- The command line used to launch the process, if any
			- The amount of time that the process has been running
			- The security/user context that the process is running in
			- The modules the process has loaded
			- The memory contents of the process

	- Process-to-Port Mapping
		- Process-to-port mapping traces the port used by a process, and protocol connected to the IP
		- Tools and commands to retrieve the process-to-port mapping:
			- Syntax: netstat –a –n –o

	- Examining Process Memory
		- Running processes could be suspicious or malicious in nature
		- Process Explorer can be used to check if the process is malicious/suspicious
		- Process Explorer shows information about opened or loaded handles and DLLs processes
		- If the process is suspicious, it gathers more information by dumping the memory used by the process using tools such as ProcDump and Process Dumper
		- The tool comes with built-in VirusTotal support to check whether the running process is malicious

		- Process Explorer https://docs.microsoft.com Process Explorer shows information about the handles and DLLs of the processes that have been opened or loaded.
		- ProcDump https://docs.microsoft.com
		- Process Dumper https://github.com
	
	- Collecting Network Status
		- Collect information of the network interface cards (NICs) of a system to know whether the system is connected to a wireless access point and what IP address is being used
		- Tools for the network status detection are:
			- ipconfig command https://docs.microsoft.com
			- PromiscDetect tool https://vidstromlabs.com
				- PromiscDetect checks if network adapter(s) is running in promiscuous mode, which may be a sign that a sniffer is running on computer
			- Promqry tool
		- Ipconfig.exe is a utility native to Windows systems that displays information about NICs and their status
		- Ipconfig /all command displays the network configuration of the NICs on the system
		
	- Collecting Non-volatile Information
		- Non-volatile data remain unchanged even after the system is shut down or powered off
		- Example: Emails, word processing documents, spreadsheets and various “deleted” files
		- Such data usually resides in hard drive (swap file, slack space, unallocated drive space, etc.)
		- Other non-volatile data sources include DVDs, USB thumb drives, smartphone memory, etc.
	
	- Examining File Systems
		- Run the command dir /o:d in command prompt
		- This enables the investigator to examine:
			- The time and date of the OS installation
			- The service packs, patches, and subdirectories that automatically update themselves often. For e.g.: drivers, etc.
		- Give priority to recently dated files

		- File systems comprise of five sections, namely, file system data, content data, metadata, file name, and file system application data.
			- File system data: File system data gives details about the file system structure such as file system and file system block size, number of allocated blocks, etc.
			- Content data: This data has most of the information of the file system. It consists of the contents of the file system.
			- Metadata: Metadata generally provides information about content locations, file size, and MAC timestamps.
			- Application data: Application data gives information about the file system journal quota statistics.

	- ESE Database File
		- Extensible Storage Engine (ESE) is a data storing technology used by various Microsoft-managed software such as Active Directory, Windows Mail, Windows Search, and Windows Update Client
		- This database file is also known as JET Blue
		- The file extension of ESE database file is .edb. Following are the examples of ESE database files:
			- contacts.edb Stores contacts information in Microsoft live products
			- WLCalendarStore.edb Stores calendar information in Microsoft Windows Live Mail
			- Mail.MSMessageStore Stores messages information in Microsoft Windows Live Mail
			- WebCacheV24.dat and WebCacheV01.dat Stores cache, history, and cookies information in Internet Explorer 10
			- Mailbox Database.edb and Public Folder Database.edb - Stores mail data in Microsoft Exchange Server
			- Windows.edb Stores index information (for Windows search) by Windows OS
			- DataStore.edb Stores Windows updates information (Located under C:\windows\SoftwareDistribution\DataStore)
			- spartan.edb Stores the Favorites of Internet Explorer 10/11. (Stored under %LOCALAPPDATA%\Packages\Microsoft.MicrosoftEdge_8wekyb3d8bbwe\AC\MicrosoftEdge\User\Default\DataStore\Data\nouser1\120712-0049)
	- Examining .edb File Using ESEDatabaseView
		- The data stored inside ESE database files can be parsed by tools such as ESEDatabaseView and ViewESE
		- During forensic investigation, the data extracted from these .edb files can serve as a potential evidence
		- ESEDatabaseView lists all the tables and records found in the selected tables of .edb database file
		- The data extracted from ESEDatabaseView can be exported to a HTML file
		- ESEDatabaseView https://www.nirsoft.net

	- Windows Search Index Analysis
		- Windows Search Index uses ESE data storage technology to store its data
		- It is stored in a file called Windows.edb, located in the directory: C:\ProgramData\Microsoft\Search\Data\Applications\Windows
		- Forensic investigators parse those files to extract data pertaining to deleted data, damaged disks, encrypted files, Event bounding, etc., which can be a good source of evidence for investigation
		- ESEDatabaseView is used to parse Windows.edb file and extract the details of deleted data on the system

	- Detecting Externally Connected Devices to the System
		- Attackers connect external storage media to the system and steal sensitive data or perform illicit activities
		- As a part of the forensic investigation, identifying the devices connected to the system helps investigator to determine if any external media is used by the suspect
		- Later, the investigator can get the specific external media from the suspect in a legal manner for further analysis
		- The utility, DriveLetterView, lists all the drives on the system even if they are not currently plugged
		- DriveLetterView https://www.nirsoft.net

	- Slack Space
		- Slack space refers to the portions of a hard drive that may contain data either from a previously deleted file or unused space by the currently allocated file
		- Non-contiguous file allocation leaves more trailing clusters leaving more slack space
		- The data residue in the slack space is retrieved by reading the complete cluster
		- DriveSpy tool collects all the slack space in an entire partition into a file

		- Steps in slack space information collection
			- Connect to the target computer and select the media
			- Create bit-level copy of the original media
			- Verify the copy by generating its hash value
			- Investigate using keyword searches, hash analysis, file signature analysis, and Enscripts present in Encase tool


- Windows Memory and Registry Analysis 
	- Windows memory analysis involves acquisition of physical memory or RAM dumps of the Windows machine
	- Examining these memory dumps help investigators detect hidden rootkits, find hidden objects, determine any suspicious process, etc.

	- Windows Crash Dump
		- Windows crash dump file contains the contents of computer’s memory at the time of a crash
		- It helps in diagnosing and identifying bugs in a program that led to the system crash
		- You can check the memory dump information using DumpChk utility
		- In Windows 10, the OS creates the following memory dumps:
			- Automatic memory dump
			- Complete memory dump
			- Kernel memory dump
			- Small memory dump
		- Examining the crash dumps can sometimes help a forensic investigator in finding out if the crash is caused due to an internal error or by a remote attacker, who was successful in exploiting a bug in the OS, or a third-party application installed on the OS

		- DumpChk https://docs.microsoft.com
			- DumpChk (Microsoft’s crash dump file checker tool) is a program that performs a quick analysis of a crash dump file. It shows summary information about what the dump file contains. If the dump file is corrupt in such a way that it cannot be opened by a debugger, DumpChk reveals the same to the investigator.
			- Syntax: DumpChk [-y SymbolPath] DumpFile

	- Collecting Process Memory
		- Collect the contents of process memory available in a RAM dump file
		- Process Dumper (pd.exe) dumps the entire process space along with the additional metadata and the process environment to the console; it redirects the output to a file or a socket
		- Userdump.exe dumps any process without attaching a debugger and without terminating the process once the dump has been completed
		- Another method of dumping a process is to use adplus.vbs script
		- Once done with the dumping process, use debugging tools to analyze the dump files

	- Random Access Memory (RAM) Acquisition
		- Examining volatile memory is as important as non-volatile memory
		- From forensics point of view, examining RAM dumps provides system artifacts such as running services, accessed files and media, system processes, network information, and malware activity
		- During live acquisition, investigators use tools such as Belkasoft RAM Capturer and AccessData FTK Imager to perform RAM dumps

	- Memory Forensics: Malware Analysis Using Redline
		- Redline is a security tool to identify malicious activities through memory and helps forensic investigators to establish the timeline and scope of an incident
		- Analyze the RAM dump using Redline by loading it from ‘Analyze Data’ section
		- Under ‘Analysis Data’ tab, you can find all the processes running on the system when the RAM dump was acquired
		- Click on ‘Ports’ under ‘Processes’ tab, where you can find all the connections available when the RAM dump was acquired

		- Memory Forensics: Malware Analysis Using Redline https://www.fireeye.com

	- Windows Registry Analysis
		- The Windows registry is a hierarchical database that contains low-level settings for the Microsoft Windows OS and for applications that use the registry
		- Investigating the data present in the registry help forensic investigators obtain information on software installed and hardware driver’s configuration settings, track suspicious user activity, etc.
		- This information help investigators build timeline analysis of the incident during forensic investigation
	- Windows Registry
		- Every action performed by the user on the machine is recorded in the Windows Registry; Hence, it is a good source of evidence during forensic investigation
		- With respect to data persistence, Windows Registry hives are divided into:
			- Non-volatile:
				- HKEY_LOCAL_MACHINE: This hive contains a vast array of configuration information for the system, including hardware settings and software settings
				- HKEY_USERS: It contains all the actively loaded user profiles for that system
			- Volatile:
				- HKEY_CLASSES_ROOT: This hive contains configuration information related to the applications used for opening various files on the system
				- HKEY_CURRENT_USER: It is the active, loaded user profile for the currently logged-on user
				- HKEY_CURRENT_CONFIG: This hive contains the hardware profile the system uses at startup
		- The volatile hives are captured during live analysis of the system while the non-volatile hives are stored on the hard drive
	- Registry Structure within a Hive File
		- Various components of the registry called “cells” have a specific structure and contain specific type of information
			- Key cell: It contains Registry key information and includes offsets to other cells as well as the LastWrite time for the key.
			- Value cell: It holds a value and its data
			- Subkey list cell: It is made up of a series of indexes pointing to key cells, these all are sub keys to the parent key cell
			- Value list cell: It is made up of a series of indexes pointing to value cells, these all are values of a common key cell
			- Security descriptor cell: It contains security descriptor information for a key cell
	- Windows Registry: Forensic Analysis
		- Forensic analysis of Windows registry helps the investigator to extract forensic artifacts such as user accounts, recently accessed files, USB activity, last run programs, and installed applications
		- The forensic investigator should analyze the Windows registry in two methods:
			- Static Analysis 
				- The investigator examines the registry files stored on the captured evidence file. These files are located in the C:\Windows\System32\config folder.
				- These files are located in the C:\Windows\System32\config folder.
			- Live Analysis
				- The investigator can use built-in registry editor to examine registry and also use tools like FTK Imager to capture registry files from live system for analysis

		- To capture Windows registry files on Live system using FTK Imager:
			- Open FTK Imager and browse File > Obtain Protected Files
			- Select, Password recovery and all registry files and provide destination directory to extract the files
				- Sub Keys of HKEY_LOCAL_MACHINE Exported
		- The extracted subkeys of HKEY_LOCAL_MACHINE contains following information:
			- SAM (Security Account Manager): It is a local security database and subkeys in the SAM contains settings of user data and work groups
			- Security: It includes local security database in SAM
			- Software: It contains information about the software applications and their configuration settings on the system
			- System: It contains configuration settings of the hardware drivers and services
			- Default: It includes default user settings but NTUSER.dat file pertaining to the currently logged-on user overrides the default user settings
		- Hex Workshop http://www.hexworkshop.com


- Cache, Cookie, and History Recorded in Web Browsers 
	- Examining web browsers such as Microsoft Edge, Google Chrome, Mozilla Firefox, etc., provide crucial evidentiary data such as web history, cookie and cache information pertaining to the user’s browsing activity

	- Cache, Cookie, and History Analysis: Google Chrome
		- Google Chrome records information about browsing history on the system at the following locations:
			- History, downloads, and cookies location
				- C:\Users\{username}\AppData\Local\Google\Chrome\User Data\Default
			- Cache location
				- C:\Users\{username}\AppData\Local\Google\Chrome\User Data\Default\Cache

	- Analysis Tool: ChromeCacheView
		- ChromeCacheView is a small utility that reads the cache folder of Google Chrome and displays the list of all files currently stored in the cache
		- It displays the information such as URL, Content Type, File Size, Last Accessed Time, Expiration Time, Server Name, and Server Response

		- Analysis Tool: ChromeCacheView
		 	- ChromeCacheView https://www.nirsoft.net

	- Analysis Tool: ChromeCookiesView
		- ChromeCookiesView https://www.nirsoft.net
			- ChromeCookiesView displays the list of all cookies stored by Google Chrome, and allows investigators to export the cookies into a text/CSV/html/XML file
			- It displays information such as Host Name, Path, Name, Value, Secure (Yes/No), HTTP Only Cookie (Yes/No), Last Accessed Time, Creation Time, and Expiration Time for each cookie

	- Analysis Tool: ChromeHistoryView
		- Analysis Tool: ChromeHistoryView
			- ChromeHistoryView https://www.nirsoft.net
		- ChromeHistoryView reads the history data file of Google Chrome and displays the list of all visited Web pages in the last days
		- It displays information such as URL, Title, Visit Date/Time, Number of visits, number of times that the user typed this address (Typed Count), Referrer, and Visit ID for each visited web page

	- Cache, Cookie, and History Analysis: Mozilla Firefox
		- Mozilla Firefox - Cache, cookies, and history are stored in the following system locations:
			- Cache Location: C:\Users\<Username>\AppData\Local\Mozilla\Firefox\Profiles\XXXXXXXX.default\cache2
			- Cookies Location: C:\Users\<Username>\AppData\Roaming\Mozilla\Firefox\Profiles\XXXXXXXX.default\cookies.sqlite
			- History Location: C:\Users\<Username>\AppData\Roaming\Mozilla\Firefox\Profiles\XXXXXXXX.default\places.sqlite
		- Analysis Tools:
				- MZCacheView (http://www.nirsoft.net)
				- MZCookiesView (http://www.nirsoft.net)
				- MZHistoryView (http://www.nirsoft.net)

	- Cache, Cookie, and History Analysis: Microsoft Edge
		- Microsoft Edge - Cache, cookies, and history are stored in the following system locations:
			- Cache Location: C:\Users\Admin\AppData\Local\Microsoft\Windows\WebCache
			- Cookies Location: C:\Users\Admin\AppData\Local\Packages\Microsoft.MicrosoftEdge_xxxxxxxxxx\AC\MicrosoftEdge\Cookies
			- History Location: C:\Users\Admin\AppData\Local\Microsoft\Windows\History
		- Analysis Tools:
			- IECacheView (http://www.nirsoft.net)
			- EdgeCookiesView (http://www.nirsoft.net)
			- BrowsingHistoryView (http://www.nirsoft.net)


- Windows Files and Metadata 
	- Windows File Analysis
		- Forensic examination of restore point log files and prefetch files provide information such as MAC timestamps, file name, file size, number of times the application has been run, process name, etc., related to the installed/uninstalled applications

	- System Restore Points (Rp.log Files)
		- Rp.log is the restore point log file located within the restore point (RPxx) directory
		- It includes value indicating the type of the restore point; a descriptive name for the restore point creation event, and the 64-bit FILETIME object indicating when the restore point was created
		- System restore points are created when applications and unsigned drivers are installed, when an auto update installation and a restore operation are performed
		- Description of the event that caused the restore point creation is written to the rp.log file, and this log file helps the investigator to notice the date when the application was installed or removed

	- System Restore Points (Change.log.x Files)
		- File changes are recorded in the change.log files, which are located in the restore point directories
		- Changes to the monitored files are detected by the restore point file system driver, the original filename is entered into the change.log file along with sequence number, type of change occurred, etc.
		- Monitored file is preserved and copied to the restore point directory and renamed in the format Axxxxxxx.ext, where x represents a sequence number and .ext is the file’s original extension
		- First change.log file is appended with a sequence number and a new change.log file is created when the system is restarted

	- Prefetch Files C:\Windows\Prefetch
		- When a user installs an application, runs it, and deletes it, traces of that application can be found in the Prefetch directory
		- DWORD value at the offset 144 within the file corresponds to the number of times the application is launched
		- DWORD value at the offset 120 within the file corresponds to the last time of the application run, this value is stored in UTC format
		- Information from .pf file can be correlated with the registry or Event Log information to determine who was logged on to the system, who was running which applications, etc.

		- Prefetching is used by the Windows OS to speed up system boot process and application launches
		- The data is recorded for up to first 10 seconds after the application process is started
		- Once the data is processed, it is written to a .pf file in the Windows\Prefetch directory
		- The forensic investigator should identify whether the victim’s system has enabled the prefetching process, before conducting examination
		- Prefetching is controlled by the registry key: HKEY_LOCAL_MACHINE\SYSTEM\ControlSet00x\Control\SessionManager\MemoryManagement\PrefetchParameters
		- The data associated with value of EnablePrefetcher tells which form of prefetching the system uses:
			- 0: Prefetching is disabled
			- 1: Application prefetching is enabled
			- 2: Boot prefetching is enabled
			- 3: Both application and boot prefetching are enabled

	- Image Files
		- The metadata present in a JPEG image file depends largely on the application that created or modified it
		- For e.g., digital cameras embed Exchangeable Image File Format (EXIF) information in images, which can include the model and manufacturer of the camera, and even store thumbnails or audio information
		- You can use tools such as Exiv2, IrfanView, and the Image::MetaData::JPEG Perl module to view, retrieve, and in some cases modify the metadata embedded in JPEG image files
		- Tools such as ExifReader, EXIF Library, and ExifTool display EXIF data found in a JPEG image

	- Metadata Investigation
		- In computer forensics, metadata obtained from the databases, image files, word files, web browsers, etc., contains evidentiary data of forensic value
		- Metadata includes file name, file size, MAC timestamps, GPS data, etc.
	- Understanding Metadata
		- Metadata is data about data. It describes various characteristics of data, including when and by whom it was created, accessed, or modified
		- Because it is not normally seen, users can inadvertently share confidential information when sending or providing files in electronic form
			- Examples of metadata include the following:
				- Organization name
				- Author name
				- Computer name
				- Network name
				- Hidden text or cells
				- Document versions
				- Template information
				- Personalized views
				- Non-visible portions of embedded Object Linking and Embedding (OLE) objects
			- It is important to collect this data as it provides information about the following:
				- Hidden data about the document
				- Who tried to hide, delete, or obscure the data
				- Correlated documents from different sources
			- The investigator can use tools such as Metadata Assistant, Paraben P2 Commander, and Metashield Analyzer to analyze metadata.
	- Metadata in Different File Systems
		- The most commonly known metadata about files on Windows systems are the files’ MAC times; MAC stands for modified, accessed, and created
		- The MAC times are time stamps that refer to the time at which the file was last modified, last accessed, and originally created
		- MAC times are managed by the OS depending on the file system used
			- On the FAT file system, times are stored based on the local time of the computer system
			- NTFS file system stores MAC times in Coordinated Universal Time (UTC) format
		- Investigate the way the timestamps are displayed, based on various move and copy actions
		- How time stamps are displayed and changed in the FAT 16 and NTFS file systems is shown below
			- FAT 16 file system
				- Copy myfile.txt from C:\ to C:\subdir on the same file system (FAT 16)
					- Myfile.txt retains the same modification date, but the creation date is updated to the current date and time
				- Move myfile.txt from C:\ to C:\subdir on the same file system (FAT 16)
					- Myfile.txt retains the same modification and creation dates
				- Copy myfile.txt from a FAT16 partition to an NTFS partition
					- Myfile.txt retains the same modification date, but the creation date is updated to the current date and time
				- Move myfile.txt from a FAT16 partition to an NTFS partition
					- Myfile.txt retains the same modification and creation dates
			- NTFS file system
				- Copy myfile.txt from C:\ to C:\subdir on the same file system (NTFS)
					- Myfile.txt retains the same modification date, but the creation date is updated to the current date and time
				- Move myfile.txt from C:\ to C:\subdir on the same file system (NTFS)
					- Myfile.txt retains the same modification and creation dates
	- Metadata in PDF Files
		- Portable document format (PDF) files can also contain metadata such as name of the author, the date when file was created, and the application used to create the PDF file
		- Often, the metadata can show that the PDF file was created on a Mac or that the PDF file was created by converting a Word document to PDF format
		- You can use the Perl scripts pdfmeta.pl and pdfdmp.pl to extract metadata from PDF files
		- To view PDF metadata, open it with Adobe Acrobat Reader. In the File menu, click Properties
	- Metadata in Word Documents
		- Word documents are compound documents, based on Object Linking and Embedding (OLE) technology that defines the file structure
		- Word documents can maintain not only past revisions but also a list of up to the last 10 authors to edit the file
		- You can use the Perl scripts wmd.pl and oledmp.pl to list the OLE streams embedded in a Word document
		- To view metadata in Word 2010, click on the File tab / Info option
		- Click Check for Issues / Inspect Document
		- Select the content to view and click the Inspect button
	- Metadata Analysis Tool: 
		- Metashield Analyzer https://www.elevenpaths.com
		- Metashield Analyzer is an online service that allows investigators to analyze the metadata contained in files


# Module 07: Linux and Mac Forensics 

- Volatile and Non-Volatile Data in Linux 
	- Linux is an open-source OS that is used extensively for enterprise servers and employee desktop platforms in several corporate organizations
	- Cybercrimes have been increasing in such business environments, and extracting artifacts from Linux systems is a challenging task
	- So, it is important for forensic investigators to understand how to examine Linux systems, and use Linux workstation for forensic examination

	- Collecting Volatile Data
		- Volatile data is lost when a machine is turned off/powered-down
		- However, during forensic investigation, investigators need to collect this data to construct a timeline analysis of the incident that occurred

	- Volatile Information includes:
		- Hostname, date & time, and time zone
		- Uptime
		- Network information
		- Open ports
		- Open files
		- Mounted filesystem information
		- Loaded kernel modules
		- User events
		- Running processes
		- Swap areas and Disk partition information
		- Kernel messages

	- Collecting Hostname, Date, and Time
		- Identify the computer name using the hostname command
			- Command: hostname
		- This command can be useful while examining logs and network traffic
		- Check the date and time of the machine to build a proper timeline of events
			- Command: 
				- date +%s
				- cat /etc/timezone
		- Alternately, you can calculate the epoch time (count of the number of seconds from the Unix OS starting point) of the system and convert it w.r.t your time zone
			- Command: date +%s
				- Note: The Unix epoch timestamp begins on 1st January 1970 00:00:00 UTC (in seconds), whereas the epoch timestamps for HFS+ and Cocoa in Apple begin on 1st January 1904 00:00:00 UTC (in seconds) and 1st January 2001 00:00:00 UTC (in seconds), respectively
		- Upon obtaining the epoch timestamp, you can use online or offline converters to convert the epoch time to original time. Here, we are doing the conversion in www.epochconverter.com

	- Collecting Uptime Data
		- The uptime command in Linux system displays how long the system has been running since the last restart
		- This command also returns the current time, number of presently logged-in users, system load averages, etc.
			- Command: uptime

	- Collecting Network Information
		- The following syntax displays all Network Interface Controllers (NICs) and associated IP addresses associated with them
			- Syntax: ip addr show
		- An attacker can sniff a network for devices that are in promiscuous mode and view all the network packets
		- To identify promiscuous mode, use the following command:
			- Syntax: ifconfig <interface>
		- To disable promiscuous mode on the network devices
			- Syntax: ifconfig <interface> -promisc
		- The netstat command can be used to extract network information
			- It displays network connections, routing tables, and a number of network interface (network interface controller or software-defined network interface) and network protocol statistics
			- To view list of network interfaces on the system
				- Command: netstat -i

	- Viewing Network Routing Tables
		- The netstat command can also be used to print routing tables
			- Command: netstat -rn
		- In Linux, the routing table provides information on the process of forwarding TCP/IP data packets
			- Command: ip r

	- Collecting Open Port Information
		- Open ports can be vulnerable, and attackers use them to exploit a machine or a server
		- To gather information on open ports from the system, use the following commands:
			- For TCP port connections:
				- Syntax: nmap –sT localhost
			- For UDP port connections:
				- Syntax: nmap –sU localhost
	- Finding Programs/Processes Associated with a Port
		- To detect intrusions, it is necessary to collect open port information
		- It is also important to check if there are any programs/processes associated with open ports
			- Command: netstat –tulpn
	- Another command to list the processes running on open ports
		- Command: lsof -i -P -n | grep LISTEN
		
	- Collecting Data on Open Files
		- You can run lsof command to list all open files as well as the active processes that opened them on the system
			- Command: lsof
		- To list the open files for the user currently logged into the system
			- Command: lsof -u <user_name>

	- Viewing Running Processes in the System
		- Run the ps command to view the processes running on the system
		- It provides a snapshot of the current processes along with detailed information, such as the user id, CPU usage, memory usage, and command name
		- Check the process tree to determine any suspicious child processes and dependencies

	- Collecting Non-volatile Data
		- The state of non-volatile data does not change when the machine is turned off
		- During forensic investigation, the investigators should collect non-volatile information such as system information, user login history, system logs, and hidden files to construct timeline analysis of the incident that occurred

		- Non-volatile data includes the following:
			- System information
			- Kernel information
			- User accounts
			- Currently logged-in users and login history
			- System logs
			- Linux log files
			- User history file
			- Hidden files and directories
			- Suspicious information
			- File signatures
			- File information obtained using file and strings command
			- Writable files obtained using the find command

	- Collecting System Information
		- Execute the cat /proc/cpuinfo command to view details about the CPU on a machine
		- Run the cat /proc/self/mounts command to view mount points and mounted external devices

	- Collecting Kernel Information
		- Use the following commands to check the Linux kernel version on a system:
			- uname -r
			- cat /proc/version
			- hostnamectl | grep Kernel

	- Collecting User Account Information
		- The /etc/passwd file running on a Linux system stores local user account information
		- Analyzing the /etc/passwd file allows the investigator to view the user accounts on the system
			- Command: cat /etc/passwd
		- Command given to list only usernames in the output
			- cut –d: -f1 /etc/passwd
		- Each line in the output represents the login information of a single user and includes seven fields separated by colon (:)

	- Collecting Currently Logged-in Users and Login History Information
		- To find the currently logged in user in the system
			- Command: w
		- The log file /var/log/wtmp maintains information about the user login history, system reboot time and system status
		- The last command pulls the login history from the wtmp log file
			- Command: last -f /var/log/wtmp
		- The /var/log/auth.log file logs information related to the user’s authentication and authorization events, user remote logins, sudo logins, SSH logins, etc.
			- Command: cat /var/log/auth.log
		- The following command filters out sudo commands
			- grep sudo /var/log/auth.log

	- Collecting System Logs Data
		- On a Linux machine, the system logs are located in the directory /var/log/syslog
		- The syslog configuration file stores system messages from logging facility and collects data logs of various programs and services, including the kernel
			- Command: cat /var/log/syslog
		- Analyzing Linux kernel logs located at /var/log/kern.log can be helpful for troubleshooting custom kernels
			- Command: cat /var/log/kern.log

	- Linux Log Files
		- /var/log/auth.log System authorization information, including user logins and authentication mechanism
		- /var/log/kern.log Initialization of kernels, kernel errors or informational messages sent from the kernel
		- /var/log/faillog Failed user login attempts
		- /var/log/lpr.log Printer logs
		- /var/log/mail.* All mail server message logs
		- /var/log/mysql.* All MySQL server logs
		- /var/log/apache2/* All Apache web server logs
		- /var/log/apport.log Application crash report/log
		- /var/log/lighttpd/* Lighttpd web server log files directory
		- /var/log/daemon.log Running services, such as squid and ntpd
		- /var/log/debug Debugging log messages
		- /var/log/dpkg.log Package installation or removal logs


- Analyze Filesystem Images Using The Sleuth Kit 
	- File System Analysis Using The Sleuth Kit: fsstat
		- In Linux systems, the fsstat command provides information associated with the given file system
		- The output of this command is filesystem-specific and consists of several information such as the file system type, volume ID, last mounted timestamps and last mounted directory
			- Command: fsstat -i <input _filetype> <filename.extension>
	- File System Analysis Using The Sleuth Kit: fls and istat
		- Run the fls command to list the files and directories available in an image file
		- This command is also useful to view recently deleted files
			- Command: fls -i <image_type> <imagefile_name>
		- Use istat command that displays the metadata of a file, such as MAC times, file size, and file access permissions, by specifying a particular inode number
		- Command: istat -f <fstype> -i <imgtype> <imagefile_name> <inode_number>

- Memory Forensics 
	- Memory forensics involves forensic analysis of RAM dumps captured from a running machine
	- Forensic analysis of RAM dump provides insights into processes running in the memory, network information, unauthorized access to the system, loaded modules, recently executed commands, injected code fragments, etc.
	- Such information can help the investigator uncover malware attacks or any other malicious behavior that has occurred on the target machine

	- Malware Analysis Using Volatility Framework
		- After acquiring RAM dumps from the target machine, the investigator should analyze those dumps using tools such as Volatility to identify the occurrence of malicious activity
		- To examine memory dumps using Volatility Framework, the investigator should create a Linux profile that matches the kernel version of the target RAM dump (which is used for analysis)
		- The pslist plugin lists all the processes that were running on the machine when the memory dump was captured
			- Command: python vol.py --file=<file_name> --profile=<Linux_profile_name> linux_pslist
		- Use the netstat plugin to search for malicious network communication on the machine
			- Command: python vol.py --file=<file_name> --profile=<Linux_profile_name> linux_netstat
		- The pstree plugin displays the parent and associated child processes generated using a malicious backdoor
			- Command: python vol.py --file=<file_name> --profile=<Linux_profile_name> linux_pstree
		- The malfind plugin helps the investigator identify any remote/hidden code injections in the memory
			- Command: python vol.py --file=<file_name> --profile=<Linux_profile_name> linux_malfind
			- When malfind plugin is run with PID, the parameter ‘Protection’ shows that the process is marked with Read, Write and Execute permissions. This indicates that some malicious code has been injected into the process.

	- Carving Memory Dumps Using PhotoRec Tool https://www.cgsecurity.org
		- PhotoRec is an open-source tool that uses data carving techniques to recover deleted files/lost data from a drive or an image file
		- Memory dumps contain volatile data pertaining to logged on users, shared files, recently accessed media files and chats via social networks, accessed webpages, etc.
		- Identifying and extracting these files allows the forensic investigators to perform a more detailed investigation
		- Run the PhotoRec tool and execute the below command
			- Command: photorec <Imagefile_name>
		- Use anti-malware tools to scan the data extracted from the memory dumps for viruses
		- This enables the detection of any malicious data in the memory dumps that could be helpful during an investigation

- Mac Forensics 
	- The ever-increasing adoption of Mac systems has made them a primary target for malicious attacks
	- The advancement of malware tools and lower availability of security tools for MacOS-based systems has further expedited these threats
	- In order to identify an attack or prove guilt, investigators require evidence such as the presence of malware, unauthorized logging attempts, and connectivity to malicious servers and websites
	- Mac systems store all such evidence data in log files, directories, configurations, applications history, etc. and investigators need to extract these data and use them to create a timeline to figure out what happened
	- Therefore, to carry out an effective investigation, investigators should possess in-depth knowledge of the MacOS, its filesystem, libraries, and directories

	- Mac Forensics Data
		- Detection of the System Version:
			- View the SystemVersion.plist file located at /System/Library/CoreServices/SystemVersion.plist
		- Timestamp:
			- Use the command line input stat to find the timestamp of any file
			- Usage: stat [-FlLnqrsx] [-f format] [-t timefmt] [file ...]
		- Application bundles:
			- These are special directories that store application data, and are hidden from the user
			- Analyze these bundles to identify malware or other suspicious data
			- Evaluate the executable codes to check if something is wrong with the application
		- Finder:
			- It is the default Mac application that helps find specific files and folders
			- It also helps in sorting in the required order

		- User account 
			- The user account data is stored in the user library folder /Users/username/Library
			- Collect information such as modification, access, and creation times for each account
		- File system 
			- The file system layer stores information such as file metadata, file content, and directory structures
		- Basic Security Module (BSM)
			- The token represents specific data, such as program arguments, return value, text data, socket, execution, and action in a file
			- Data stored in BSM helps determine the file type, creator, and usage data

		- Spotlight 
			- Use a spotlight to search for specific keywords that represent malicious activity
		- Home directory
			- Stores the authentication data, such as logon attempts (both success and failure) of all users
			- Helps investigator in determining all the attempts made to bypass the security measures along with the relevant timestamps
		- Time machine
			- A backup tool that stores the contents of the hard disk
			- Includes a BackupAlias file containing the binary information related to the hard disk used to store the backups
		- Kexts
			- MacOS can incorporate additional capabilities by loading kernel extensions
			- Analyze the system for kernel extensions

		- Apple Mail
			- Stores user email in the /Users//Library/Mail directory
			- Saves email in emlx format, where each email is stored as a file in ASCII format
			- Use email extractors such as Email Extractor 7 and Data Extractor to analyze email data
		- Safari
			- Data such as browsing history, download history, and bookmarks can be used as evidence and are stored as History.plist, Downloads.plist, and Bookmarks.plist respectively in the /Users//Library/Safari location 
		- iChat
			- Check for any saved chats in the default location: /Users/<username>/Documents/iChats
			- Individual applications are stored as <username> on <date> at <time>.ichat
		- Command line inputs
			- MacOS records commands in the bash shell and stores them in the file .bash_history
			- Use the $tail .bash_history command to view the most recent commands that have been run on the suspect machine
	- Mac Log Files
		- /var/log/crashreporter.log Application crash history
		- /var/log/cups/access_log Printer connection information
		- /var/log/cups/error_log Printer connection information
		- /var/log/daily.out Network interface history
		- /var/log/samba/log.nmbd Samba (Windows-based machine) connection information
		- ~/Library/Logs Application logs specific to Home directory
		- ~/Library/Logs/iChatConnectionErrors iChat connection information
		- ~/Library/Logs/Sync Information of devices on .Mac syncing
		- /var/log/* Main folder for system log files
		- /var/audit/* Audit logs
		- /var/log/install.log System and software update installation dates

	- Mac Directories
		- Launch agent files /Library/LaunchAgents/*, /System/Library/LaunchAgents/*
		- Launch daemon files /Library/LaunchDaemons/*, /System/Library/LaunchDaemons/*
		- Startup item file /Library/StartupItems/*, /System/Library/StartupItems/*
		- Mac OS X jobs /usr/lib/cron/jobs/*
		- Cron tabs or scheduled jobs /etc/crontab, /usr/lib/cron/tabs/*
		- Wireless networks /Library/Preferences/SystemConfiguration/com.apple.airport.preferences.plist
		- User preference settings for applications and utilities %%users.homedir%%/Library/Preferences/*
		- Attached iDevices %%users.homedir%%/Library/Preferences/com.apple.iPod.plist
		- Social accounts %%users.homedir%%/Library/Accounts/Accounts3.sqlite
		- Trash directory %%users.homedir%%/.Trash/
		- Safari main folder %%users.homedir%%/Library/Safari/*
		- Mozilla Firefox web browser %%users.homedir%%/Library/Application Support/Firefox/*
		- Google Chrome web browser %%users.homedir%%/Library/Application Support/Google/Chrome/*

	- APFS Analysis: Biskus APFS Capture
		- The SQLite report file provides all APFS metadata in an organized manner as it is on the APFS directory
		- It also provides individual access to every named key, inode, xattr and extent record, including CNIDs and block numbers
		- This enables investigators to search for hardlinks, cloned file content, etc., and use this information to access every file on the disk

	- Parsing Metadata on Spotlight
		- Spotlight is a built-in indexing system on MacOS that creates indexes of all files/folders on the system and stores the metadata of every file/folder on the disk
		- On MacOS, Spotlight can be accessed by pressing Command + Space bar keys
		- The store.db database file is the Spotlight’s central database repository. Each individual MacOS partition contains store.db file.
		- In digital forensic examination, the database information parsed from Spotlight retrieves details such as dates, last opened, and number of times an application or file is opened

		- Parsing with Spotlight
			- Run spotlight_parser and point it to the database file, .store.db which is located in the /.Spotlight-V100/Store-V2/<UUID> folder
			- Syntax: python spotlight_parser.py <path_to_database> <path_to_output_folder>
			- When Spotlight has finished parsing the database file, it creates two output files
			- One is a text file containing a database dump of all entries while the other is CSV file consisting of directories of every file/folder in the specified partition

	- Mac Forensics Tools
		- OS X Auditor (https://github.com)
		- Recon Imager (https://sumuri.com)
		- Memoryze for the Mac (https://www.fireeye.com)
		- Stellar Data Recovery Professional for Mac (https://www.stellarinfo.com)
		- F-Response (https://www.f-response.com)
		- volafox (https://github.com)
		- Volatility (https://www.volatilityfoundation.org)
		- mac_apt - macOS (and iOS) Artifact Parsing Tool (https://github.com)


# Module 08: Network Forensics 
- Network Forensics Fundamentals 
	- Network forensics is the capturing, recording, and analysis of network events in order to discover the source of security incidents
	- Network forensics can reveal the following information:
		- Source of security incidents
		- The path of intrusion
		- The Intrusion techniques an attacker used
		- Traces and evidence
	- Postmortem and Real-Time Analysis
		- Postmortem analysis of logs is conducted to investigate an incident that has already happened
		- Real-time analysis is conducted to detect and examine an ongoing-attack

	- Most common attacks on networks
		- Eavesdropping
		- Data Modification
		- IP Address Spoofing
		- Denial-of-Service Attack
		- Man-in-the-Middle Attack
		- Packet Sniffing
		- Enumeration
		- Session Hijacking
		- Buffer Overflow
		- Email Infection
		- Malware attack
		- Password-based attack
		- Router Attacks
	- Attacks specific to wireless networks
		- Rogue Access Point Attack
		- Client Misassociation
		- Misconfigured Access Point Attack
		- Unauthorized Association
		- Ad Hoc Connection Attack
		- Honeypot Access Point Attack
		- AP MAC Spoofing
		- Jamming Attack

	- Indicators of Compromise (IOCs)
		- Indicators of Compromise (IoCs) are digital forensic artifacts that help detect a security incident that has occurred (or is ongoing) on a host system or a network
		- These artifacts include logs related to systems, applications, networks, firewalls, etc.
			- Unusual outbound network traffic: Unusual increase in the outbound traffic could be a sign of ongoing attack
			- Uniform Resource Locators or URLs: Malicious URLs that are often spread via phishing and spamming are considered potential IoCs
			- User-agent strings: User-agent informs the server regarding visiting device’s OS, browser information, etc.
			- Log-in anomalies: Increase in the number of failed login attempts on a user account could be sign of malicious activity
			- Increased number of requests for same file: Attackers perform many requests to infiltrate a network, which leaves the traces of malicious activities
			- Network traffic traversing on unusual ports: Programs using unusual ports and pretending to be legitimate
	- Where to Look for Evidence
		- Logs collected in network devices and applications can be used as evidence for investigating network security incidents
	- Types of Network-based Evidence
		- Full Content Data
			- Full content data refers to actual packets that are collected by storing the network traffic (known as packet capture or PCAP files)
			- Investigators can use tools like tcpdump or Wireshark to analyze any subset of full content data
		- Session Data
			- Session data refers to a summary of conversation between two network entities
			- It includes details such as destination IP and destination port, source IP and source port, start time of the session, and amount of information exchanged during the session
		- Alert Data
			- Alert data is triggered by tools such as Snort IDS and Suricata that are preprogrammed to examine network traffic for IoCs and report the findings as alerts
			- Investigators need to be careful while examining alert data as there might be false positive alerts
		- Statistical Data
			- Statistical data provides overall profile or summaries of the network traffic
			- Statistical data analysis can provide investigator with useful information such as timestamps related to network conversations, protocols and services being used, average packet size, and average packet rate

- Event Correlation Concepts and Types 
	- Event correlation is the process of relating a set of events that have occurred in a predefined interval of time
	- It includes analysis of events to determine how it could add up to become a bigger event
	- It is usually performed on a log management platform, after identifying logs having similar properties
	- Steps in event correlation:
		- Event aggregation
		- Event masking
		- Event filtering
		- Root cause analysis
	- Types of Event Correlation
		- Same-Platform Correlation
			- This correlation method is used when one common OS is used throughout the network in an organization
			- Example: An organization running only Microsoft Windows OS (any version) on their servers may collect event log entries and perform trend analysis diagonally
		- Cross-Platform Correlation
			- This correlation method is used when different OS and network hardware platforms are used in the network of an organization
			- Example: Clients may use Microsoft Windows, but they use a Linux-based firewall and email gateway
	- Prerequisites of Event Correlation
		- Transmission of Data
			- Transmitting log data from one security device to another until it reaches a consolidation point in the automated system. 
			- To have a secure transmission and reduce the risk of exposure during transmission, the data must be encrypted and authenticated.
		- Normalization
			- After the data is gathered, it must be formatted again from different log formats to a single or polymorphic log that can be easily inserted into the database
		- Data Reduction
			- After collecting the data, repeated data must be removed so that the data can be correlated more efficiently. 
			- Removing unnecessary data can be done by compressing the data, deleting repeated data, filtering, or combining similar events into a single event, and sending that to the correlation engine.

		- Event Correlation Approaches
			- Graph-Based Approach
			- Neural Network-Based Approach
			- Codebook-Based Approach
			- Rule-Based Approach
			- Field-Based Approach
			- Automated Field Correlation
			- Packet Parameter/Payload Correlation for Network Management
			- Profile/Fingerprint-Based Approach
			- Vulnerability-Based Approach
			- Open-Port-Based Correlation
			- Bayesian Correlation
			- Time (Clock Time) or Role-Based Approach
			- Route Correlation

- Identify Indicators of Compromise (IoCs) from Network Logs 
	- Analyzing Firewall Logs
		- Firewalls are the first points of entry into a network and store details of all the data packets moving in and out of the network
		- The network firewall logs collect network traffic data such as request source and destination, ports used, time and date, and priority
		- These details help investigators correlate the data with other suspicious files to identify the source and other targets of an attack
		- Investigators need to analyze the logs carefully based on the timings and suspicious IP addresses
		- Check for application generated requests, DNS queries, suspicious IP addresses, and URLs

		- Cisco Firewall uses mnemonics as identifiers to represent severity of an event
		- Cisco firewall logs include the following details:
			- Date and Time
			- Mnemonic message
			- Firewall Action
			- Source IP address and port
			- Destination IP address and port
			- Type of request
		
		- Analyzing Firewall Logs: Check Point
			- Check Point firewall logs can be viewed through a Check Point Log viewer
			- It uses icons and colors in the log table to represent different security events and their severity
			- Red (Error message) represents the connection attempts blocked by the firewall
			- Orange (Warning message) signifies traffic detected as suspicious, but accepted by the firewall
			- Green is for the traffic accepted by the firewall

			- Check Point firewall log when viewed through Check Point Log viewer

		- Analyzing IDS Logs
			- Intrusion Detection System (IDS) logs provide information helpful in finding suspicious packet types, determining probes, generating new attack signatures, and measuring attack statistics
			- Some of the common IDS devices and tools include Juniper, Check Point and Snort
			
			- General indicators of intrusion:
				- Requests targeted towards known vulnerabilities 
				- Failure to comply with protocols and syntaxes 
				- Unexpected elements such as date, time, and system resources 
				- Repeated unusual network activity
				- Address anomalies in traffic
				- Occurrence of mistyped command

		- Analyzing IDS Logs: Check Point
			- Check Point IPS provides an in-built software for managing the device
			- Users can view and analyze the logs using this software
			- Steps to view and access logs in check Point IPS:
				- Go to SmartDashboard, click SmartConsole / select SmartView Tracker
				- Select the Network & Endpoint tab, expand Predefined / Network Security Blades / IPS Blade
				- Double-click All to view complete log information
			- Check Point also provides details of each log
				- To view the details of any log, go to the SmartView Tracker records list and double-click on the event

		- Analyzing Honeypot Logs
			- Honeypots are devices that are deployed to bait attackers. These appear to contain very useful information to lure the attackers, and find their whereabouts and techniques
			- Kippo is one of the most commonly used honeypots
			- Logs stored in Kippo contain the following information:
				- Timestamp
				- Type of session
				- Session ID and Source IP address
				- Message with other details

		- Analyzing Router Logs
			- Routers store network connectivity logs with details such as date, time, source and destination IPs, and ports used
			- This also enables investigators to correlate various events to identify the source and destination IP
			- This information can help investigators in verifying the timestamps of an attack
			- Routers contain various standards for storing the log details of a network
			- The incoming log details are as follows:
				- Date and time
				- Source IP address
				- Source port
				- Destination IP address
				- Destination port
			- The outgoing log details are the following:
				- Date
				- Time
				- Source IP address
				- Source-port
				- URL accessed
				- URL IP address
				- Port Used
		
		- Analyzing Router Logs: Cisco
			- Cisco routers run on a specific operating system- the Cisco IOS
			- The OS has a built-in security manager that defines policies regarding basic logging parameters
			- The router complies with syslog standards to define severity levels using numeric code
			- Cisco IOS helps users to classify logs using certain predefined identifiers
			- The following are the details found in the Cisco router log:
				- Event ID
				- Date
				- Time
				- Identifier
				- Protocols supplied
				- Source IP address
				- Destination IP address

		- Analyzing DHCP Logs
			- DHCP logs are saved in the C:\Windows\System32\dhcp folder on DHCP servers
			- DHCP server log file format is as follows:
				- ID: A DHCP Event ID code
				- Date: The date on which this entry was logged on the DHCP server
				- Time: The time at which this entry was logged on the DHCP server
				- Description: A description of this DHCP server event
				- IP Address: The IP address of the DHCP client
				- Host Name: The host name of the DHCP client
				- MAC Address: The media access control (MAC) address used by the network adapter hardware of the client

- Investigate Network Traffic 
	- To detect and examine an ongoing attack by monitoring network traffic communication patterns
	- To know which hosts or networks are involved in a network security incident
	- To trace information/packets related to a security intrusion and collect them as evidence

	- Gathering Evidence via Sniffers
		- Sniffer is a computer software or hardware that can intercept and log traffic passing over a network
		- Sniffers put NICs in promiscuous mode to allow them to listen to and capture all data transmitted over the network
		- Sniffers collect traffic from the network and transport layers other than the physical and datalink layer
		- Investigators should configure sniffers for the size of frames to be captured

	- Sniffing Tool: Tcpdump https://www.tcpdump.org
		- Tcpdump is a command line interface packet sniffer which runs on Unix-based OSes

	- Sniffing Tool: Wireshark https://www.wireshark.org
		- It enables you to capture and interactively browse the traffic running on a computer network
		- Wireshark uses Winpcap to capture packets, and therefore, can only capture packets on networks supported by Winpcap
		- It captures live network traffic from Ethernet, IEEE 802.11, PPP/HDLC, ATM, Bluetooth, USB, Token Ring, Frame Relay, FDDI networks
		- Captured files can be programmatically edited via command-line
		- A set of filters for customized data display can be refined using a display filter

		- Display Filters in Wireshark
			- Display filters are used to change the view of packets in the captured files in Wireshark some of which are as follows:
				- Display Filtering by Protocol
					- Type the protocol such as arp, http, tcp, udp, dns, and ip, in the filter box
				- Monitoring Specific Ports
					- tcp.port==23
					- ip.addr==192.168.1.100 machine
					- ip.addr==192.168.1.100 && tcp.port=23
				- Filtering by Multiple IP Addresses
					- ip.addr == 10.0.0.4 or ip.addr == 10.0.0.5
				- Filtering by IP Address
					- ip.addr == 10.0.0.4
				- Other Filters
					- ip.dst == 10.0.1.50 && frame.pkt_len > 400
					- ip.addr == 10.0.1.12 && icmp && frame.number > 15 && frame.number < 30
					- ip.src==205.153.63.30 or ip.dst==205.153.63.30

		- Analyze Traffic for TCP SYN Flood DoS Attack
			- SYN flooding is a type of Denial-of-Service (DoS) attack in which the attacker sends large number of SYN packets repeatedly to the target server using multiple spoofed IP addresses that never return an ACK packet, thus keeping the server busy and rendering it unresponsive
			- Run Wireshark to monitor network activity and detect any abnormalities in the TCP traffic
			- The Wireshark packet capture screenshot above shows a large number of TCP SYN packets of similar length of 120 being sent from different IP addresses to the destination IP address 192.168.0.145 over HTTP port 80
			- Navigate to Statistics > Protocol Hierarchy to examine the statistical value of each protocol

		- Analyze Traffic for SYN-FIN Flood DoS Attack
			- Attackers send packets with both the SYN and FIN flags in an attempt to saturate the network bandwidth and cause a DoS attack
			- Use the filter tcp.flags==0x003 to detect a SYN/FIN flooding attack on Wireshark
			- The screenshot below shows a large number of TCP SYN-FIN packets being passed from a single source IP address 10.0.0.2 to the destination IP address 10.128.0.2 on HTTP port 80
			- Navigate to Statistics > Capture File Properties to analyze the summary of packets captured
		
		- Analyze Traffic for FTP Password Cracking Attempts
			- In a password cracking attack, the attacker attempts to gain access to the credentials of an authenticated user via various techniques, such as brute-force or dictionary attacks
			- Apply the filter ftp.response.code == 530 to monitor all unsuccessful login attempts over FTP
			- Apply the filter ftp.response.code == 230 to see successful logins on the FTP server
		
		- Analyze Traffic for SMB Password Cracking Attempts
			- The traffic captured via Wireshark reveals several usernames along with the message 'Error: STATUS_LOGON_FAILURE' which strongly indicates a brute-force attack attempt on the SMB protocol
			- If any name found on the captured packets matches that of an authorized user on the target host, you can consider that the brute-force attack is likely to have been successful
			- Gather other useful information under the Transmission Control Protocol section such as source port, destination port and count of packet bytes
		
		- Analyze Traffic for Sniffing Attempts
			- Attackers sniff the network traffic for sensitive information
			- Different techniques may be used for sniffing the traffic depending on the type of network
			- Passive sniffing is used to sniff a hub-based network while active sniffing is used to sniff a switch-based network
			- An attacker uses MAC flooding and ARP poisoning to sniff network traffic, which can then serve as a basis for launching man-in-the middle (MiTM) attacks
			- Identify sniffing attempts by detecting the signs of MAC flooding and ARP poisoning using Wireshark

		- Analyze Traffic for MAC Flooding Attempt
			- In a MAC flooding attack, the attacker connects to a port on the switch and floods its interface by sending a large volume of ethernet frames from various fake MAC addresses
			- Wireshark considers MAC flooded packets as malformed packets
			- Go to the Analyze menu on Wireshark and select Expert Information to view these malformed packets
			- Analyze source IP, destination IP, and the Time to Live (TTL) values of the malformed packets while looking for signs of a MAC flooding attack on the network
		
		- Analyze Traffic for ARP Poisoning Attempt
			- target network
			- Wireshark detects duplicate IP addresses on the ARP protocol with the warning message ‘duplicate use of <IP address> detected’
			- To locate duplicate IP address traffic use the filter: arp.duplicate-address-detected

		- Analyze Traffic to Detect Malware Activity
			- After a malware infects the target host, its activities on the network are often reflected in the ongoing traffic patterns which you can inspect and analyze via Wireshark
			- Search online databases to gather more information on any unusual/suspicious ports, IP addresses, or websites
			- The port database of speedguide.net below shows the port 1177 to be malicious and used by the njRAT trojan


# Module 09: Investigating Web Attacks 
- Web Application Forensics 
	- Web application forensics involves tracing back a security attack that occurred on any web application to identify its origin, and how it was penetrated
	- It includes the collection and analysis of log and configuration files associated with the web server, application server, database server, system events, etc. to determine the cause, nature and perpetrator of a web exploit

	- Challenges in Web Application Forensics
		- Due to the distributed nature of web applications, traces of activities are recorded across numerous hardware and software components
		- Very limited or no downtime is allowed for investigation
		- Web application forensics requires the analysis and correlation of huge volumes of logs
		- It also requires complete knowledge of different web servers, application servers, databases and underlying applications
		- Tracing back is difficult in case of reverse proxies and anonymizers	

	- Indicators of a Web Attack
		- Customers being unable to access services
		- Suspicious activities in user accounts
		- Leakage of sensitive data
		- URLs redirecting to incorrect sites
		- Web page defacements
		- Unusually slow network performance
		- Frequent rebooting of the server

	- Web Application Threats
		- Cookie Poisoning
		- SQL Injection
		- Injection Flaws
		- Cross Site Request Forgery
		- Path/Directory Traversal
		- Unvalidated Input
		- Cross Site Scripting (XSS)
		- Sensitive Data Exposure
		- Parameter/Form Tampering
		- Denial-of-Service (DoS)
		- Broken Access Control
		- Security Misconfiguration
		- Information Leakage
		- Improper Error Handling
		- Buffer Overflow
		- Insufficient Logging & Monitoring
		- Broken Authentication
		- Log Tampering
		- Insecure Direct Object References
		- Insufficient Transport Layer Protection
		- Failure to Restrict URL Access
		- Insecure or Improper Cryptographic Storage
		- Insecure Deserialization
		- Cookie Snooping
		- XML External Entities
		- Security Management Exploits
		- Authentication Hijacking
		- Unvalidated Redirects and Forwards
		- Session Fixation Attack
		- CAPTCHA Attacks

	- Web Attack Investigation Methodology
		- Conduct individual interviews to obtain information
		- Locate the servers or other devices that are involved in the security attack, take them offline, and perform seizure in a forensically sound manner
		- Follow the process of forensic image acquisition and duplication
		- Collect logs from the web server, application server, database server, web application firewall, local system events, SIEM tool, and IDS, along with application and server configuration files
		- Use encryption and checksum to verify and protect the integrity of log files
		- Analyze the working copies of collected logs to look for suspicious entries and correlate the data to build a chain of events unfolding the whole attack scenario
		- Trace the attacking IP to identify the perpetrator of the attack
		- Document every step of the investigation

- IIS and Apache Web Server Logs 
	- IIS Web Server Architecture
		- Internet Information Services (IIS) for Windows Server is a flexible, secure and easy-to-manage web server for hosting anything on the web

		- IIS includes the following components:
			- Protocol listeners (known as HTTP.sys)
			- World Wide Web Publishing Service (known as WWW service)
			- Windows Process Activation Service (WAS)
		- The responsibilities of the IIS components include the following:
			- Listening to requests coming from the server
			- Managing processes
			- Reading configuration files
		- How IIS 10.0 Server Components Function
			- When a HTTP request for a resource is sent from the client browser to the web server, it is intercepted by HTTP.sys
			- HTTP.sys communicates with WAS to collect data from ApplicationHost.config, the root file in the configuration system in IIS web server
			- WAS raises a request for configuration information, such as that of the site and application pool, to ApplicationHost.config, which is then passed to WWW Service.
			- WWW Service utilizes the configuration information obtained to configure HTTP.sys
			- A worker process is then initiated by WAS for the application pool which the request is aimed at
			- The request is then processed by the worker process, and the response is returned to HTTP.sys
			- The client browser receives a response
		- IIS Logs 
			- IIS logs all server visits in log files
			- IIS logs provide useful information regarding the activity of various web applications, such as the client IP address, username, date and time, request type, and target of operation
			- The IIS server generates ASCII text-based log files
			- On Windows Server OSes, the log files are stored by default in %SystemDrive%\inetpub\logs\LogFiles

		- Analyzing IIS Logs
		- Apache Web Server Architecture
			- The elements of the Apache core are http_protocol, http_main, http_request, http_core, alloc, and http_config.
				- http_protocol: This element is responsible for managing the routines. It interacts with the client and handles all the data exchange and socket connections between the client and server.
				- http_main: This element handles server startups and timeouts. It also consists of the main server loop that waits for the connections and accepts them.
				- http_request: This element controls the stepwise procedure followed among the modules to complete a client request and is responsible for error handling
				- http_core: This element includes a header file that is not required by the application module
				- Alloc.c: This element handles the allocation of resource pools
				- http_config: This element is responsible for reading and handling configuration files. One of the main tasks of http_config is to arrange all the modules, which the server will call during various phases of request handling.

		- Apache Web Server Logs
			- Apache HTTP Server 
				- Apache HTTP Server is a web server that supports many OSs, such as Unix, GNU, FreeBSD, Linux, Solaris, Novell NetWare, AmigaOS, macOS, Microsoft Windows, OS/2 and TPF
			- Apache Log Types 
				- Apache server generates two types of logs
					- Access log
					- Error log
			- Apache Log Information
				- Apache logs provide information about web application activities, such as the following:
					- IP address of the client
					- Ident of the client machine
					- User ID of the client
					- Time
					- Request line from the client
					- Status code
					- Size of the object returned to the client
			- Apache Access Logs
				- It contains requests processed by the Apache server
					- The default locations of access logs are as follows: 
						- RHEL/Red Hat/CentOS/Fedora Linux: /var/log/httpd/access_log
						- Debian/Ubuntu Linux: /var/log/apache2/access.log
						- FreeBSD Linux: /var/log/httpd-access.log

			- Analyzing Apache Access Logs
				- Access log: Common Log format "%h %l %u %t \"%r\" %>s %b"
				- Access log: Combined Log format "%h %l %u %t \"%r\" %>s %b \"%{Referer}i\" \"%{User-agent}i\""

			- Apache Error Logs		
				- The Apache server saves diagnostic information and error messages that it encounters while processing requests in the error logs
					- RHEL/Red Hat/CentOS/Fedora Linux: /var/log/httpd/error_log
					- Debian/Ubuntu Linux: /var/log/apache2/error.log
					- FreeBSD: /var/log/httpd-error.log

			- Analyzing Apache Error Logs
				- Date and time of the log
				- Severity of the error 
				- Process ID and thread ID
				- IP address of the client
				- Message stating “File not found”
				- The object requested by the client

- Investigating Web Attacks on Windows-based Servers 
	- Run Event Viewer to view the logs: C:\> eventvwr.msc
	- Check if the following suspicious events have occurred:
		- Event log service has ended
		- Windows File Protection is inactive on the system
		- MS Telnet Service is running
	- Find out whether the system has failed login attempts or locked-out accounts

	- Review file shares to ensure their purpose: C:\> net view <IP Address>
	- Verify the users using open sessions: C:\> net session
	- Check if the sessions have been opened with other systems: C:\> net use
	- Analyze at NetBIOS over TCP/IP activity: C:\> nbtstat -S
	- Find if TCP and UDP ports have unusual listening: C:\> netstat –na
	- Find scheduled and unscheduled tasks on the local host: C:\> schtasks.exe
	- Check for the creation of new accounts in the administrator group: Start -> Run -> lusrmgr.msc -> OK
	- Check whether any unexpected processes are running in Task Manager: Start -> Run -> taskmgr -> OK
	- Check for unusual network services: C:\> net start
	- Check file space usage to find any sudden decrease in free space: C:\> dir

- Detect and Investigate Attacks on Web Applications 
	- Common XSS attacks use HTML tags, such as <script></script>, <IMG>, <INPUT>, and <BODY>
	- Attackers use various obfuscation techniques to avoid detection by application firewalls and IDS/IPS systems
		- Hex encoding
		- In-line comment
		- Char encoding
		- Toggle case
		- Replaced keywords
		- White-space manipulation
	- For example, all the scripts below have the same meaning:
		- <script>alert(“XSS”)</script>
		- <sCRipT>alert(“XSS”)</ScRiPt>…......................................................(Toggle case)
		- %3cscript%3ealert(”XSS”)%3c/script%3e>…....................................(Hex encoding)
		- %253cscript%253ealert(1)%253c/script%253e….............................(Double encoding)
	- Investigators can use regex search to find HTML tags, other XSS signature words, and their hex equivalents in web-server logs, IDS logs, SIEM tool alerts, etc. to check for XSS attacks

	- Investigating XSS: Using Regex to Search XSS Strings
		- The regular expression below checks for attacks that may contain HTML opening and closing tags (<>) with any text inside, along with their hex and double encoding equivalents

		- /((\%3C)|(\%253C)|<)((\%2F)|(\%252F)|\/)*[azA-Z0-9\%]+((\%3E)|(\%253E)|>)/ix
			- ((\%3C)|(\%253C)|<) 
				- Checks for the opening angle bracket, or its hex or double-encoded hex equivalent
			- ((\%2F)|(\%252F)|\/)* 
				- Checks for the forward slash in a closing tag, or its hex or double-encoded hex equivalent
			- [a-zA-Z0-9\%]+ 
				- Checks for upper and lower-case alphanumeric strings inside the tag, or their hex representation
			- ((\%3E)|(\%253E)|>) 
				- Checks for the closing angle bracket, or its hex or double-encoded hex equivalent

		- Detection of simple XSS attempt
			- /((\%3C)|<)((\%2F)|\/)*[a-z0-9\%]+((\%3E)|>)/ix
		- Detection of <img src= based XSS attempt
			- /((\%3C)|<)((\%69)|i|(\%49))((\%6D)|m|(\%4D))((\%67)|g|(\%47))[^\n]+((\%3E)|>)/I
		- Detection of HTML tag-based XSS attempt
			- /(javascript|vbscript|script|embed|object|iframe|frameset)/i
		- Detection of all XSS attempts
			- /((\%3C)|<)[^\n]+((\%3E)|>)/I

	- Examining Apache Logs for XSS Attack
		- The highlighted log entry in the Apache access.log file shows a GET request followed by some hex encoded values in the query string
		- Decode the query string to determine whether it contains any malicious HTML tags
			- %3C <
			- %3E >
			- %28 (
			- %29 )
			- %2F /
		- Decoding the values reveals that the log is associated with an XSS attack
		- The detailed analysis of the log has provided the following findings:
			- The attack originated from the IP 10.0.0.1 16th June 2020 
			- The malicious XSS script %3Cscript%3Ealert%28XSS%29%3C%2Fscript%3E , which converts to <script>alert(XSS)</script> after decoding, was injected into the page /wordpress/wp-admin/admin.php?page=newsletters-subscribers (3) by the attacker
			- A HTTP 200 status code can be observed, implying that the web application server processed the request
		- From the log examination, it can be inferred that an XSS attack occurred on the web application. If this is a stored XSS attack, this script would get stored on the backend database and would trigger an alert pop-up with the message “XSS” whenever a user visits that webpage.

	- Examining Snort Alert Logs for XSS Attack
		- Snort IDS has generated an alert for an XSS attack attempt with the following details:
			- Source/Attacker IP Address: 192.168.0.233 
			- Destination/Target IP Address: 192.168.0.115
			- Source Port: 64580 
			- Destination Port: 80

	- Examining SIEM Logs for XSS Attack
		- a Splunk-triggered alert as collected from Snort IDS shows an XSS attack with the following information:
			- The date of the attack is 12th December 2018, and the time is 4.12 A.M.
			- Attacker’s IP address is 10.10.10.2 using port 1593
			- The target server IP is 10.10.10.20 using HTTP port 80

	- Investigating SQL Injection Attack
		- Look for SQL injection attack incidents in the following locations:
			- IDS log files
			- Web server log files
			- SIEM-triggered alerts
		- The SQL injection attack signature in Web server log files may look like the following:
			- 10:23:45 10.0.0.7 HEAD GET /login.asp?username=blah’ or 1=1 –
			- 10:23:45 10.0.0.7 HEAD GET /login.asp?username=blah’ or )1=1 (--
			- 10:23:45 10.0.0.7 HEAD GET /login.asp?username=blah’ or exec master..xp_cmdshell 'net user test testpass --
		- Obfuscation Methods used in SQL Injection Attack
			- Attackers use various obfuscation methods to bypass security mechanisms in websites. Some of the techniques are discussed below:
				- In-line comment: Attackers use in-line comments in the middle of attack strings to bypass security mechanisms.
					- Code with inline comment: http://www.bank.com/accounts.php?id=/*!union*/+/*!select*/+1,2,concat(/*!table_name*/)+FrOm/*!information_schema*/.tables/*!WhErE*/+/*!TaBlE_sChEMa*/+like+database()--
				- Char encoding/ double encoding: Some WAFs decode hex-encoded inputs and filter them, preventing an attack. To bypass them, attackers might double encode the input.
					- Code with char encoding: http://www.bank.com/accounts.php?id=1%252f%252a*/union%252f%252a/select%252f%252a*/1,2,3%252f%252a*/from%252f%252a*/users--
				- Toggle Case: Some applications block lowercase SQL keywords. In such case, attackers use code written in alternating case to bypass this security mechanism.
					- Some firewalls contain the regular expression (regex) filter /union\select/g. Therefore, they may filter suspicious code written in lowercase letters.
					- Code with toggled case: http://www.bank.com/accounts.php?id=1+UnIoN/**/SeLecT/**/1,2,3--
				- Replaced Keywords: Some applications and WAFs use preg_replace to remove all SQL keywords. Hence, attackers use the following coding technique to bypass WAFs.
					- Code with replaced keywords: http://www.bank.com/accounts.php?id=1+UNunionION+SEselectLECT+1,2,3--
				- White space manipulation: As explained above, when attackers replace keywords, some WAFs may replace the keywords with white space. In such cases, the attackers use "%0b" to eliminate the space and bypass firewalls.
					- Code with white-space manipulation: http://www.bank.com/accounts.php?id=1+uni%0bon+se%0blect+1,2,3--
		- Investigating SQL Injection Attack: Using Regex
			- Investigators should perform regex search in the log files to look for the presence of SQL-specific meta-characters, such as the single-quote (‘), the double-dash (--), the equals sign (=), and the semi-colon (;) as well as their hex equivalents in an attempt to identify SQL injection attacks
			- Regular expression for detecting SQL meta-characters: /(\%27)|(\')|(\-\-)|(\%23)|(#)/ix
			- Modified Regular expression for detecting SQL meta-characters: /((\%3D)|(=))[^\n]*((\%27)|(\')|(\-\-)|(\%3B)|(;))/i
			- Regular expression for detecting a typical SQL injection attack: /\w*((\%27)|(\'))((\%6F)|o|(\%4F))((\%72)|r|(\%52))/ix
			- Regular expression for detecting SQL injection with the UNION keyword: /((\%27)|(\'))union/ix
			- Regular expression for detecting SQL injection attack on an MSSQL server: /exec(\s|\+)+(s|x)p\w+/ix

		- Examining IIS Logs for SQL Injection Attack
			- The GET request in the highlighted IIS log entry contains some SQL meta-characters some of which are encoded
			- With the characters decoded, the query Id=ORD- 001%27%20or%201=1;-- translates to Id=ORD-001 ' or 1=1;-- which indicates an SQL injection attack
			
		- Examining Snort Alert Logs for SQL Injection Attack
		- Examining SIEM Logs for SQL Injection Attack


# Module 10: Dark Web Forensics 

- Dark Web 
	- Different Layers of the Internet
		- Surface Web
			- It is the visible part of the web and contains content that can be accessed by search engines such as Google and Yahoo
		- Deep Web 
			- The deep web can only be accessed by an authorized user having a valid username, password, etc. It includes contents such as legal documents, financial records, government reports, and subscription information.
		- Dark Web 
			- It is an invisible or a hidden part of the web that requires specific web browsers such as the Tor browser to access; such browsers protect the anonymity of the users

	- Tor Relays
		- Tor relays are also referred to as Routers or Nodes through which traffic passes
		- For greater security, the Tor circuit is designed to have the following three types of relays:
			- Entry Relay
				- When establishing a Tor network, the user connects to the entry node, from which the IP address of the user can be seen
			- Middle Relay
				- Here, the data is transferred in an encrypted mode
			- Exit Relay
				- The data is sent to the destination servers through this node. Thus, the exit node is seen as the origin of the traffic, hiding the original identity of the user.
	- Working of the Tor Browser
		- The Tor browser is based on Mozilla’s Firefox web browser and works on the concept of onion routing
		- In onion routing, the traffic is encrypted and passed through different relays present in the Tor circuit. This multi-layered encrypted connection makes the user identity anonymous.
		- The Tor browser provides access to .onion websites available on the dark web
		- Tor’s hidden service protocol allows users to host websites anonymously with .BIT domains and these websites can only be accessed by users on the Tor network

	- Tor Bridge Node
		- The Tor relay nodes are publicly available in the directory list, but the bridge node is different from relay nodes
		- Bridge nodes act as a proxy to the Tor network which implies that they follow different configuration settings to forward the traffic to the entry node
		- This makes it difficult for organizations or governments to censor the usage of Tor and list the bridge nodes on the public directory of Tor nodes

- Dark Web Forensics 
	- Dark web forensics involves identification and investigation of illicit activities on the dark web performed by attackers/malicious users
	- To investigate the malicious activities performed using the Tor browser, the investigator should obtain memory dumps from the suspect machine and examine them to extract valuable information such as websites browsed, emails accessed, etc. 
	
	- Identifying Tor Browser Artifacts: Command Prompt
		- When Tor browser is installed on a Windows machine, it uses port 9150/9151 for establishing connection via Tor nodes
		- When investigators test for the active network connections on the machine by using the command netstat -ano, they will be able to identify whether Tor was used on the machine	

	- Identifying Tor Browser Artifacts: Windows Registry
		- When the Tor browser is installed on a Windows machine, the user activity is recorded in Windows Registry
		- Forensic investigators can obtain the path from where the TOR browser is executed in the following
			- Registry key: HKEY_USERS\<SID>\SOFTWARE\Mozilla\Firefox\Launcher

		- Extract last execution date and time of the Tor browser:
			- On a suspect machine, the investigator analyzes the ‘State’ file located in the path where the Tor browser was executed
			- The directory of the State file in the Tor browser folder is \Tor Browser\Browser\TorBrowser\Data\Tor\

	- Identifying Tor Browser Artifacts: Prefetch Files
		- When the Tor browser is uninstalled from a machine, or if it is installed in a location other than the desktop (in Windows), it will be difficult for investigators to know whether it was used or the location where it is installed
		- Examining the prefetch files will help investigators in obtaining this information
		- The prefetch files are located in the directory, C:\WINDOWS\Prefetch on a Windows machine
		- Using tools such as WinPrefetchView, investigators can obtain metadata related to the browser, which includes:
			- Browser created timestamps
			- Browser last run timestamps
			- Number of times the browser was executed
			- Tor browser execution directory
			- Filename

	- Dark Web Forensics Challenges
		- High level of anonymity: The dark web allows perpetrators to carry out illegal activities by hiding their identity
		- Encrypted networks: Tracing the physical location of the perpetrators is difficult.
		- Limited number of traces: When the Tor browser is uninstalled on a suspect machine, the investigator is left with a limited number of artifacts, which makes the investigation process difficult.
		- Legal jurisdiction issues: The criminal activities on the dark web occur irrespective of the jurisdiction, posing legal jurisdiction issues to investigators and law enforcement agencies.

- Tor Browser Forensics 
	- Tor Browser Forensics: Memory Acquisition
		- RAM contains volatile information pertaining to various processes and applications running on a system
		- Examining RAM dumps can provide deep insights regarding the actions that occurred on the system
		- Forensic investigators can examine these dumps in an attempt to extract various Tor browser artifacts that help in reconstructing the incident
		- The results obtained by examining these artifacts differ based on the following conditions:
			- Tor Browser Opened 
			- Tor Browser Closed 
			- Tor Browser Uninstalled
		- A memory dump taken while the browser is opened collects the most number of artifacts, while a dump taken post browser uninstallation collects the least
		- Memory dumps taken while the browser is closed contain most of the information that is found in memory dumps collected, while the browser is left opened

	- Collecting Memory Dumps
		- Investigators need to acquire a memory dump of the suspect machine to begin the forensic examination
		- Tools such as Belkasoft LIVE RAM Capturer and FTK Imager can help capture RAM
		- The memory dump collected from the suspect machine not only contains artifacts related to the browser, but also all the activities that occurred on it

	- Memory Dump Analysis: Bulk Extractor
		- The memory dump acquired from the machine must be examined on the forensic workstation to discover artifacts that may potentially be helpful during investigation
		- Tools such as Bulk Extractor help in processing these dumps and providing useful information such as the URLs browsed, email IDs used, and personally identifiable information entered in the websites
		- Bulk Extractor https://digitalcorpora.org
	

# Module 11: Investigating Email Crimes 

- Email Basics 
	- An email system encompasses servers that send and receive emails on the network, along with the email clients that allow users to view and compose messages 
	- Email systems are based on a client-server architecture
	- The mail is sent from the client to a central server, which then reroutes the mail to its intended destination

	- Components Involved in Email Communication
		- Mail User Agent (MUA) 
			- Also known as email client, MUA is an application that enables users read, compose and send emails from their configured email addresses
			- There are two commonly used email clients:
				- Standalone: Microsoft Outlook and Mozilla Thunderbird
				- Web-based: Gmail, Yahoo! mail, AOL mail, etc.
		- Mail Transfer Agent (MTA) 
			- MTA is also known as a mail server that accepts the email messages from the sender and routes them to their destination
			- Examples include Sendmail, Exim and Postfix
		- Mail Delivery Agent (MDA)
			- MDA is an application responsible for receiving an email message from the MTA and storing it in the mailbox of the recipient
			- Example includes Dovecot
		- SMTP Server 
			- SMTP (Simple Mail Transfer Protocol) is an outgoing mail server that allows a user to send emails to a valid email address
			- When a user sends an email, the sender’s host SMTP server interacts with the receiver’s host SMTP server
			- The SMTP servers listen on the port 25
		- POP3 Server 
			- POP3 (Post Office Protocol version 3) is an Internet protocol that is used to retrieve e-mails from a mail server
			- It handles incoming mails and listens on port 110
			- POP3 automatically downloads the emails to the user's hard disk and removes them from the mail server
		- IMAP Server
			- Internet Message Access Protocol (IMAP) is an internet protocol designed for accessing e-mail on a mail server
			- By default, the IMAP server listens on port 143, and the IMAPS (IMAP over SSL) listens on port 993
			- This protocol keeps e-mails on the server even after the user has already downloaded them, thus enabling the user to use multiple devices to check the email

	- How Email Communication Works
	- Understanding the Parts of an Email Message
		- Header
			- Email headers contain information about the email origin such as the address from which it came, the routing, time of the message, and the subject line
			- Examples include To, Cc, Bcc, From, Message- Id, Reply-To, Sender, Subject, MIME-Version, and Priority
		- Body
			- This part contains the actual message sent via the email either in HTML or plain-text
			- It may include images and hyperlinks
		- Signature
			- This provides information to the recipients about the identity or designation of the sender

- Email Crime Investigation and its Steps 
	- Email crime investigation involves the examination of the origin and content of email messages as evidence
	- This enables investigators to identify the type of email fraud performed, the criminal and their malicious intent

	- Email crime can be categorized in two ways
		- Crimes committed by sending e-mails 
			- Spamming
			- Phishing
				- Spear Phishing
				- Whaling
				- Pharming
				- Spimming
			- Mail bombing
			- Mail Storms 
		- Crimes supported by e-mails
			- Identity Fraud
			- Cyberstalking
			- Child abduction

	- Steps to Investigate Email Crimes
		- Seizing the computer and email accounts
		- Acquiring the email data
		- Examining email messages
		- Retrieving email headers
		- Analyzing email headers
		- Recovering deleted email messages

	- Step 1: Seizing the Computer and Email Accounts
		- Obtain a search warrant that should include permission to perform onsite examination of the suspect's computer and the email server used to send the emails under investigation
		- Seize all computers and email accounts suspected to be involved in the crime
		- You can seize the email accounts by changing the existing password of the e-mail account, either by asking the suspect his or her password or obtaining it from the mail server
	- Step 2: Acquiring the Email Data
		- The next step in an email crime investigation is to acquire the email data for forensic analysis
		- Before acquiring email data, the investigator should consider the following scenarios:
			- The suspect accesses his/her emails via any desktop-based email client
			- The suspect has an web-based email account on which the crime has occurred
		- The email data acquisition methods would be different for each scenario

	- Acquiring Email Data from Desktop-based Email Clients
		- When an email crime is suspected to have occurred on a user’s machine using email clients, the key sources of evidence are the local folders and archived files stored by these programs that hold information regarding all email activities
		- Forensic investigators need to locate the local folders and recover the email messages using the right forensic tools for further examination
		- While acquiring email data from the local archives, investigators must be careful to gather all the files as local archives can be spilt into multiple files that store data separately

	- Local Email Files in Microsoft Outlook
		- When users configure their email accounts on Outlook, it creates a local copy of all the email information in two kinds of file formats:
			- Personal Storage Table (.pst)
				- Certain kinds of POP accounts use the .pst file to save mailbox information on the local computer
				- By default, .pst files are stored at C:\Users\%USERNAME%\Documents\Outlook Files
			- Offline Storage Table (.ost)
				- Account types such as Microsoft Exchange, Office 365 and IMAP accounts store a copy of the mailbox components in an .ost file
				- By default, .ost files are located at C:\Users\%USERNAME%\AppData\Local\Microsoft\Outlook

		- Email artifacts can also be found in the Archive folder, which is a default folder created by Outlook along with folders such as Inbox, Drafts, and Sent Items
		- Outlook 2010, 2013 and 2016 have an Outlook Auto Archive feature that enables users to move email messages and other important items to an archive folder
		- To know the Outlook 2016 Auto Archive data location on the suspect's machine, navigate to File > Options > Advanced > AutoArchive Settings
		- Outlook saves the Archived data in .pst file format

	- Acquiring Thunderbird Local Email Files via SysTools MailPro+
		- Use tools such as SysTools Mailpro+ to examine local mail files and folders and collect them as evidence https://www.systoolsgroup.com
		- You can select one or more mbox files or specific local email folders for forensic acquisition and analysis
		- Mailpro+ offers six different views to look at the messages extracted from the Thunderbird local folders
		- Select all email messages of evidentiary value and click the 'Export' button to acquire them
		- You can select the exported file type and name format and collect the selected email messages in the chosen destination folder
		- SysTools Mailpro+ https://www.systoolsgroup.com
			- Features
				- Supports more than 12 email file formats
				- Read the mailbox of any email file type
				- Search emails within source email files in just a few clicks
				- Create and save collections for easy mailbox management
				- Search and extract emails from hard drive or external storage
				- Add files in three modes to the software’s dashboard
				- Export emails into .pst, .pdf, .msg, .html, .eml, .tiff, and .csv file types
				- Preview attachment types such as JPG, GIF, PNG, DOC, and PDF

	- Step 3: Examining Email Messages
		- While looking at the acquired email messages, you need to closely examine the following areas:
			- Subject
				- This field is important as it sums up the message contained in that email; most spam email subjects create a sense of urgency, prompting users to open the mail
			- Sender Email Address
				- Attackers often spoof this address to make it look legitimate to the user. You can see here that customer support team at abc bank is using a Gmail account instead of the respective bank domain which is suspicious.
			- Email Body
				- A spoofed email body might contain direct links/hyperlinks designed to lure users into providing sensitive details
			- Email attachment
				- Attackers can embed malicious javascript, VBScript or .exe files within the documents and PDF files sent as attachments. You need to examine these attachments within a controlled forensic environment.

	- Step 4: Retrieving Email Headers
		- If an offending email has been identified or is suspected to be spoofed, investigators must examine its header information
		- The email header plays a vital role in forensic investigation as it holds detailed information on the email’s origin, which can help investigators gather supporting evidence and identify the culprit behind the crime
		- Email header information can be retrieved after acquiring the email messages
		- If the investigator is physically accessing the suspect’s computer, they can view the email header using the same email program as the one used by the suspect. This process is different for different email programs.

	- Retrieving Email Headers in Microsoft Outlook
		- Launch Microsoft Outlook and double-click on the email message
		- Click the File button located on the top-left and then the Properties icon
		- When the Properties window opens, select the message header text from the Internet headers box, then copy and paste the text in any text editor and save the file
	- Retrieving Email Headers in Microsoft Outlook.com
		- Log on to Microsoft Outlook.com and select the received mail for which you would like to see headers
		- Click on the More actions drop-down button and navigate to the View message details option
		- Select the message headers text from the Message details box, copy and paste the text in any text editor, and save the file
	- Retrieving Email Headers in Gmail
		- Log on to Gmail and select the received mail for which you would like to see headers
		- Click on the more drop-down button and navigate to the Show original option
		- Select the message headers text, copy and paste the text in any text editor, and save the file

	- Step 5: Analyzing Email Headers
		- Timestamp: Shows the date and time when the mail was sent
		- From: Shows the email ID of the sender as it is visible to the recipient; this can be forged in case of spam emails
		- To: Shows the email ID of the recipient
		- Message ID: As per RFC 2822, a specific email message should have a globally unique message identifier The first part of the message ID before ‘@’ contains the timestamp of the email (1587617857 in Unix epoch format converts to Thursday April 23, 2020 04:57:37 am in UTC) The part of message ID after '@’ contains the Fully Qualified Domain Name (here, the domain name is mail.yahoo.com)
		- Subject: Shows the subject as given by the sender
		- MIME-Version: Multi-purpose Internet Mail Extensions are used to support non-text attachments such as video, images, and audio and the default version is 1.0
		- Received Header: 
			- The entries in the received headers are of significant forensic value as these cannot be forged unlike other email header elements
			- The number of received headers found in an email message depends on the mail servers that processed the message as it travelled from source to destination
			- Investigators should start with the bottommost received header (B), as it is closest to the source and then move towards the top headers (A)
			- Here, the B header is showing the domain name from which the email message originated (sonic302-19.consmr.mail.sg3.yahoo.com), the associated IP address (106.10.242.139), and the date and time in PDT
		- Return-Path
			- It is the bounce address for emails that are sent but not delivered to the recipient
			- If the sender's email address and the return-path address are different, it generally indicates email spoofing
		- Received-SPF
			- Sender Policy Framework or SPF refers to the process that enables organizations to mention servers that can send emails on behalf of their domains
			- An email header showing a failed SPF check can help detect spam messages
		- DomainKeys Identified Mail (DKIM) Signature
			- It offers a cryptographic way of verifying whether a received email has actually originated from the sending domain
		
		- Different elements of the DKIM signature
			- "v=" field stands for the DKIM signature version which should always be set to 1
			- "a=" field shows the algorithm (sha256) used to generate the signature
			- "c=" field denotes the canonicalization algorithm used. It shows if there is any modification in the email in terms of whitespace or line-wrapping; the first value before
			- "/" is for the header and the rest is for the body
			- "d=" field refers to the domain of the sender
			- "s=" field refers to the selector to identify the DNS public key
			- "t=" field denotes the timestamp of the signature in Unix epoch time and should always match or be close to the time reflected in the Received header and Message ID fields
			- "bh=" field is the hash for the body as per the hashing algorithm in use and then encoded in Base64
			- "b=" field includes the DKIM signature that should be calculated as per the header field mentioned in the "h=" field

	- Analyzing Email Headers: Checking Email Authenticity
		- Once the sender’s email address has been identified, investigators should check whether it is valid
		- Use Email Dossier, a scanning tool included in the CentralOps.net suite of online network utilities
		- This tool provides information about e-mail address, including the mail exchange records
		- It initiates SMTP sessions to check address acceptance, but it never actually sends e-mail

		- Email Dossier https://centralops.net
		- Email Address Verifier https://tools.verifyemailaddress.io
		- Email Checker https://email-checker.net
		- G-Lock Software Email Verifier https://www.glocksoft.com

	- Investigating a Suspicious Email
		- Examining the Email Message
			- This message invokes a sense of urgency asking the recipient to login to their Twitter account
			- Inspect the message body thoroughly to look for any suspicious link/attachment
		- Checking the Link
			- Run the link given on the email message on a forensic workstation within a controlled environment
		- Analyze the Received Header Entries 
			- Start from the bottommost received header entry and then proceed to the top to locate the email ID and IP address of the attacker
		- Examine the Originating IP Address
			- Look for IP address details collected from the received header in the whatismyipaddress website
		- Examine the Received-SPF Field
			- Analyze the Received-SPF header to see if there is any SPF validation failure
			- You can see that the received-SPF field below is showing a softfail which indicates that the domain of jose.regan@gmail.com or the sender does not permit the server IP 93.99.104.210 to send mails on its behalf
			- This validation failure is a sign that the message might have been spoofed
		- Check the Sender's Email Validity
			- Use the Email Dossier website to see whether the sender's email address as shown in the email message is legitimate
			- You can see that Email Dossier shows the email address to be valid
			- This indicates that the attacker might have compromised the email account of the user named Jose Regan, or obtained the email address via social engineering techniques
		- Examine the Message ID
			- You can see here that the highlighted part of the message ID shows the Fully Qualified Domain Name (FQDN) to be the local host instead of mail.gmail.com which clearly indicates that this is a spoofed email message

	- Step 6: Recovering Deleted Email Messages
		- Paraben's Electronic Evidence Examiner https://paraben.com
		- Recovery of deleted e-mail messages depends upon the e-mail client used to send the email
			- Thunderbird 
				- Messages deleted from the mailbox reside in the trash folder, until the trash folder is cleared
				- Some forensic tools might recover these deleted messages, depending on how soon the recovery is attempted
				- Email messages deleted from the Trash section of Local Folders can be completely recovered
			- Outlook PST
				- When email messages are deleted on Outlook, they are moved to the ‘Deleted Items’ folder
				- If the emails are deleted from the Deleted Items folder, they will go to the unallocated space of the drive
				- The deleted email messages can be recovered if that unallocated space is not replaced with new data
		- Recovering Deleted Email Messages from Outlook .pst Files Using Paraben’s Electronic Evidence Examiner
			- Here the screenshot shows the retrieval of two email messages by Paraben’s Electronic Email Examiner that have been deleted from Outlook local .pst files
			- You can see the recovered email's body, attachments, and its RFC headers and use the information for further analysis

# Module 12: Malware Forensics 

- Malware, its Components and Distribution Methods 
	- Malware is a malicious software that damages or disables computer systems and gives limited or full control of the systems to the malware creator for the purpose of theft or fraud
	- Different types of malware include viruses, worms, Trojans, etc.

	- Different ways malware can get into a system:
		- Instant Messenger and Internet Relay Chat
		- Removable Devices
		- Email and Attachments
		- Browser and Software Bugs
		- Bluetooth and Wireless Networks
		- File Downloads
		- Network File Sharing (Using NetBIOS)

	- Malware programmers develop and use it to:
		- Attack browsers and track websites visited
		- Alter system performance, making it very slow
		- Cause hardware failure, rendering computers inoperable
		- Steal personal information, including contacts
		- Erase important information, resulting in potentially huge data losses
		- Attack additional computer systems directly from a compromised system
		- Spam inboxes with advertising emails

	- Components of Malware: Components of a malicious software rely on the requirements of the malware author, who designs it for a specific target to perform the intended tasks
		- Crypter: A software type that disguises malware as a legitimate product through encryption or obfuscation, thus protecting it from detection by security programs
		- Downloader: A type of Trojan that downloads other malware from the Internet on to the PC. Usually, attackers install downloader software when they first gain access to a system
		- Dropper: A type of Trojan that installs other malware files on to the system either from the malware package or internet
		- Exploit: A malicious code that breaches the system security via software vulnerabilities to access information or install malware
		- Injector: A program that injects its code into other vulnerable running processes and changes the way of execution to hide or prevent its removal
		- Obfuscator: A program that conceals its code and intended purpose via various techniques, thus making it hard for security mechanisms to detect or remove it
		- Packer: A program that allows to bundle all files together into a single executable file via compression in order to bypass security software detection
		- Payload: A piece of software that allows to control a computer system after it has been exploited
		- Malicious Code: A command that defines malware’s basic functionalities, such as stealing data and creating a backdoor
		- Fileless Malware: A group of malware that do not write any file to the disk and use only approved Windows tools for installation and execution, thus circumventing security programs and application whitelisting processes
		
	- Common Techniques Attackers Use to Distribute Malware across Web
		- Blackhat Search Engine Optimization (SEO)
			- Ranking malware-attacked pages in search engine page result
		- Malvertising
			- Embedding malware in ad-networks that display across hundreds of legitimate, high-traffic sites
		- Compromised Legitimate Websites
			- Hosting embedded malware sites that spreads to unsuspecting visitors
		- Domain Shadowing
			- Stealing domain account credentials via phishing to create multiple subdomains that direct traffic to landing pages hosting an exploit kit
		- Social Engineered Clickjacking
			- Tricking users into clicking on innocent-looking webpages
		- Spear Phishing Sites
			- Mimicking legitimate institutions in an attempt to steal login credentials
		- Drive-by Downloads
			- Viruses exploiting flaws in a browser software to install malware just by visiting a web page
		- Mouse Hovering
			- Malware getting auto executed when the user hovers his mouse pointer over any hyperlinked text or picture in a malicious PowerPoint Slideshow

- Malware Forensics Fundamentals and Recognize Types of Malware Analysis
	- Often, attackers use malware such as virus, worm, trojan, spyware, and ransomware to commit a crime on the intended target system
	- Malware forensics deals with identifying and containing malicious code, and examine its behavior in a controlled environment
	- Performing malware analysis enables investigators to know the type of malware, how it works, its behavior, and its impact on the target system
	- You can use a set of tools and techniques to conduct static analysis and dynamic (run-time) analysis of the malicious code

	- Why Analyze Malware?
		- To determine what exactly happened 
		- To determine the malicious intent of malware 
		- To find out the IoCs
		- To determine the complexity level of an intrusion
		- To identify the exploited vulnerability
		- To identify the extent of damage from an intrusion
		- To catch the perpetrator accountable for installing the malware
		- To find signatures for host and network-based intrusion detection systems

	- Malware Analysis Challenges https://www.hhs.gov
		- Accuracy of the analysis process
		- Detection of malware pieces and traits
		- Amount of data to be analyzed
		- Changing technologies and dynamics of malware creation and propagation
		- Anti-analysis procedures such as encryption, code obfuscation, and deletion of records
	
	- Identifying and Extracting Malware
		- If a user has reported a suspicious activity on his/her system, you must examine the following areas of the compromised system to find traces of malware installation:
			- Installed programs
			- Suspicious executables
			- Auto-starting locations
			- Scheduled jobs
			- Services
			- Modules
			- Logs
			- User accounts and login activities
			- File systems
			- Registry entries
			- Application traces
			- Restore points
		- You can use tools, such as Balbuzard and Cryptam Malware Document Detection Suite, to extract patterns from malicious files for investigation
		- You can perform static and dynamic analysis together to identify the intent and capabilities of the malware

	- Prominence of Setting Up a Controlled Malware Analysis Lab
		- Usually, malware analysis is carried out by infecting a system with a malicious code and then evaluating its behavior using a set of monitoring tools
		- Therefore, a dedicated laboratory system is required that can be infected while keeping the production environment safe
		- Best way to set up such a lab system involves:
		- Using a physical system isolated from the production network to prevent the spread of malware
		- Using virtualization software such as Virtualbox, VMware, Parallels, etc. (to set up single physical system with multiple VMs installed in it, each running a different OSs)
	- Importance of virtual environment for malware analysis:
		- Protects real systems and network from being infected by the malware under analysis
		- Easy to analyze malware interaction with other systems
		- Allows screen capturing during analysis
		- Ability to take snapshots of the laboratory system, which can be used to easily revert to a previous system state

	- Preparing Testbed for Malware Analysis
		- Allocate a physical system for the analysis lab
		- Install virtual machine (VMware, Hyper-V, etc.) on the system
		- Install guest OSs in the virtual machines such as Windows and Linux (Ubuntu). These machines serve as forensic workstations
		- Isolate the system from the network by ensuring that the NIC card is in “host only” mode
		- Simulate internet services using tools such as INetSim
		- Disable “shared folders” and the “guest isolation”
		- Install malware analysis tools
		- Generate hash value of each OS and tool
		- Copy the malware collected from the suspect machines onto the forensic workstations
	- Several tools are required for testing
		- Imaging tool: To get a clean image for forensics and prosecution
		- File/data analysis: To perform static analysis of potential malware files
		- Registry/configuration tools: Malware infects the Windows registry and other configuration variables. These tools help identify the last saved settings
		- Sandbox: To perform dynamic analysis manually
		- Log analyzers: The devices under attack record the activities of malware and generate log files. Log analyzers are used to extract log files
		- Network capture: To understand how the malware leverages a network

	- Supporting Tools for Malware Analysis
		- Hypervisors
			- Virtual Box (https://www.virtualbox.org)
			- Parallels Desktop (https://www.parallels.com)
			- VMware vSphere Hypervisor (https://www.vmware.com)
		- Network and Internet Simulation Tools
			- NetSim (https://www.tetcos.com)
			- ns-3 (https://www.nsnam.org)
			- Riverbed Modeler (https://www.riverbed.com)
			- QualNet (https://www.scalable-networks.com)
		- Screen Capture and Recording Tools
			- Snagit (https://www.techsmith.com)
			- Camtasia (https://www.techsmith.com)
			- Ezvid (https://www.ezvid.com)
		- OS Backup and Imaging Tools
			- Genie Backup Manager Pro (https://www.zoolz.com)
			- Macrium Reflect Server (https://www.macrium.com)
			- R-Drive Image (https://www.drive-image.com)
			- O&O DiskImage 16 (https://www.oo-software.com)
	
	- General Rules for Malware Analysis
		- During malware analysis, pay attention to the key features instead of looking at each and every detail
		- Try different tools and approaches to analyze the malware, as a single approach may not be helpful
		- Identify, understand, and defeat new malware analysis prevention techniques
	
	- Types of Malware Analysis
		- Static Malware Analysis 
			- Also known as code analysis, it involves going through the executable binary code without its actual execution to have a better understanding of the malware and its purpose
			- Disassemblers such as IDA Pro can be used to disassemble the binary file
		- Dynamic Malware Analysis
			- Also known as behavioral analysis, it involves executing the malware code to know how it interacts with the host system and the network
			- This type of analysis requires virtual machines and sandboxes to deter the spread of malware
			- Debuggers such as GDB, OllyDbg, WinDbg, etc., are used to debug a malware at the time of its execution to study its behavior
		
		- Both techniques are intended to understand how the malware works, but differ in the tools used, and time and skills required for performing the analysis
		- Both static and dynamic analysis are recommended to better understand the functionality of a malware

- Static Malware Analysis 
	- Analyzing the binary code provides information such as data structures, function calls, call graphs, etc.
	- Load the binary code on to the test system (preferably the OS on which the malware is not designed to run) to analyze its static properties
	- Some of the static properties of the binary code to be examined include strings embedded into the file, header details, hashes, embedded resources, packer signatures, metadata, etc.
	
	- Some static malware analysis techniques:
		- File fingerprinting
		- Online malware scanning
		- Performing strings search
		- Identifying packing / obfuscation methods
		- Finding the portable executables (PE) information
		- Identifying file dependencies
		- Malware disassembly

	- Static Malware Analysis: File Fingerprinting
		- It is recommended to compute the hash value for a given binary code before carrying out the investigation
		- Common hash calculators include HashTab, HashMyFiles, HashCalc, md5sum, md5deep, etc.
		- You can use the computed hash value to periodically verify if any change is made to the binary code during analysis
		- HashMyFiles https://www.nirsoft.net

	- Static Malware Analysis: Online Malware Scanning
		- Scan the binary code using renowned and up-to-date anti-virus software
		- If the code under analysis is a component of a well-known malware, it may have been already discovered and documented by many anti-virus vendors
		- Go through their documentation to recognize the code capabilities, signatures, etc.
		- You can also upload the code to websites such as VirusTotal to get it scanned by different scan engines
		- VirusTotal is a free service that analyzes suspicious files and URLs, and facilitates the detection of viruses, worms, Trojans, etc.
		- VirusTotal https://www.virustotal.com

	- Static Malware Analysis: Performing Strings Search
		- Strings communicate information from the program to its user
		- Analyze embedded strings of the readable text within the program’s executable file Ex: Status update strings and error strings
		- Use tools such as Strings, ResourcesExtract, Bintext, Hex Workshop, etc. to extract embedded strings from executable files
		- Ensure that the tool-extracted strings are represented in both ASCII and Unicode formats 
		- On extracting, you can see the input of strings of interest in search engine for more information
		- ResourcesExtract https://www.nirsoft.net

	- Static Malware Analysis: Identifying Packing/Obfuscation Methods
		- Attackers often use packers to compress, encrypt, or modify a malware executable file
		- It complicates the task of the reverse engineers in finding the actual program logic and other metadata via static analysis
		- Use tools such as PEiD, which detects most common packers, cryptors, and compilers for PE executable files
		- PEiD https://github.com

	- Static Malware Analysis: Finding the Portable Executables (PE) Information
		- PE format is the executable file format used on Windows OSs
		- Information available for examining the metadata of a PE file:
			- Time and date of compilation
			- Functions imported and exported by the program
			- Linked libraries
			- Icons, menus, version info, strings, etc. embedded in resources
		- You can use tools, such as Pestudio, PEview, PE Explorer, Dependency Walker, etc. to extract the above-mentioned information
		- Pestudio https://www.winitor.com

	- Static Malware Analysis: Identifying File Dependencies
		- Programs store the import and export functions in kernel32.dll file
		- Examine the dynamically linked libraries in the malware executable file
		- Finding all library functions may allow you to guess what the malware program can do
		- You can use tools such as Dependency Walker, which lists all dependent modules within the executable file
		- Dependency Walker https://www.dependencywalker.com

		- Some of the standard DLLs are listed below:
			- Kernel32.dll: Core functionality, such as access and manipulation of memory, files, and hardware
			- Advapi32.dll: Provides access to advanced core Windows components such as the Service Manager and Registry
			- User32.dll: User-interface components, such as buttons, scroll bars, and components for controlling and responding to user actions
			- WSock32.dll & Ws2_32.dll: Networking DLLs that help connect to a network or perform network-related tasks
			- Wininet.dll: Supports higher-level networking functions
			- Gdi32.dll: Functions for displaying and manipulating graphics
			- Ntdll.dll: Interface to the Windows kernel

	- Static Malware Analysis: Malware Disassembly
		- Disassemble the binary code and analyze the assembly code instructions
		- You can use tools such as IDA Pro that can reverse machine code to assembly language
		- Based on the reconstructed assembly code, you can inspect the program logic and recognize its threat potential
		- This process is carried out using debugging tools such as OllyDbg and WinDbg
		- OllyDbg http://www.ollydbg.de
		
- Analyze Suspicious Word Documents 
	- Finding Suspicious Components
		- Analyze the suspect Office document with oleid to detect any specific components that can be labeled as malicious/suspicious
		- To use oleid, open a new terminal on the linux (Ubuntu) workstation and typeoleid ‘<path to the suspect document>’
		- Here, the analysis has revealed that the Word document named infected_doc contains VBA macros
	- Finding Macro Streams
		- Parse the suspect Office document with oledump to identify the streams that contain macros
		- Run the following command- python oledump.py ‘<path to the suspect document>’
		- In this Word document, stream 8 has been identified to store malicious macro codes
	- Dumping Macro Streams
		- Extract the contents of any particular macro stream with oledump by running the following commandpython oledump.py -s <stream number> ‘<path to the suspect document>’
	- Identifying Suspicious VBA Keywords
		- Parse the suspect document with olevba to view the source codes of all VBA macros, and detect the suspicious keywords and potential IOCs
		- Run the following command: olevba ‘<path to the suspect document>’
		- Here, the keywords and IOCs detected by olevba show that the macros in the Word document:
			- have AutoOpen functionality
			- contain shellcode and strings obfuscated with Base64 and dridex
			- might download files named test.exe and sfjozjero.exe from http://germanya.com.ec/logs and store them in Temp directory

- Dynamic Malware Analysis 
	- It refers to the process of studying the behavior of a malware by running it in a monitored environment
	- Dynamic malware analysis makes it easy for the investigators to observe in real-time how the malware interacts with the system properties and the network
	
	- Two approaches to dynamic malware analysis:
		- Monitoring Host Integrity 
			- It involves taking snapshots of the system state using the same tools before and after the analysis to detect changes made to the entities residing in the system
		- Observing Runtime Behavior
			- It involves live monitoring the behaviour of the chosen malware as it runs on the system

	- Dynamic Malware Analysis: Pre-Execution Preparation
		- Create a fresh baseline of the forensic workstations		
		- Take a snapshot of the registry keys, file system, running processes, and event log files
		- List all Windows services, device drivers and startup programs
		- Install tools that will capture the changes performed by the malware on system resources, such as registry, file system, processes, etc., as well as network properties
		- Generate hash values of the OSs and the tools
		- Run the malware on the forensic workstations

	- Monitoring Host Integrity
		- Upon creating the baseline image, run the malware on the
		- Windows forensic workstation for a certain time period. Note: In this scenario, we will be executing a malware named payload.exe
		- Take the second snapshot of the workstation and compare it with the baseline to detect all changes made in the file systems and registries
		- Use Tools like WhatChanged Portable that scans for modified files and registry entries and lists them in text file format
		- WhatChanged Portable https://portableapps.com

	- Observing Runtime Behavior
		- It refers to the execution of the malware on forensic workstation and observing its operations in real-time to understand its intent and functionality
		- You can learn about the behavioral characteristics of the malware by monitoring its activities on the system and the network
		- Runtime behavior analysis of malware can be done in two ways: system behavior analysis and network behavior analysis

		- System Behavior Analysis 
			- It involves monitoring the changes on operating system resources upon malware execution.
			- System behavior analysis includes:
				- Monitoring Registry Artifacts
				- Monitoring Processes
				- Monitoring Services and Startup Folders
				- Examining Event Logs
				- Monitoring API calls
				- Monitoring Device Drivers
				- Monitoring Files and Folders
		- Network Behavior Analysis
			- It involves tracking the malware’s network-level activities. 
			- Network behavior analysis includes:
				- Monitoring IP Addresses
				- Looking for Connected Ports
				- Examining the DNS Entries

- System Behavior Analysis 
	- Malware manipulates the registry to ensure that it runs automatically whenever the computer boots, or the user logs in
	- By running the malware on a forensic workstation, you can observe its activity on the registry and look for specific keys or values that are read, created, modified, or deleted by it
	- Look for Windows AutoStart registry locations that are commonly targeted by malware to persist on the system

	- Windows AutoStart Registry Keys
		- Run/RunOnce Keys
			- HKLM\SOFTWARE\Microsoft\Windows\CurrentVersion\Run
			- HKCU\SOFTWARE\Microsoft\Windows\CurrentVersion\Run
			- HKLM\Software\Microsoft\Windows\CurrentVersion\Policies\Explorer\Run
			- HKLM\SOFTWARE\Microsoft\Windows\CurrentVersion\RunOnce
			- HKCU\SOFTWARE\Microsoft\Windows\CurrentVersion\RunOnce
		- Startup Keys
			- HKLM\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\Shell Folders
			- HKLM\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\User Shell Folders
			- HKCU\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\Shell Folders
			- HKCU\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\User Shell Folders

	- Analyzing Windows AutoStart Registry Keys
		- Use tools like Regripper that comes with both GUI and command line tools that can parse keys, values, and data from registry
		- Command to parse Autostart registry key contents from the NTUSER.dat file of a specific user (Robert) on Regripper
		- RegRipper https://github.com

	- System Behavior Analysis: Monitoring Processes
		- Some malware also use PEs (Portable Executable) to inject themselves into various processes (such as explorer.exe or web browsers)
		- Process monitoring after the execution of the malware on the forensic workstation helps in identifying the processes the malware initiates or takes over
		- Use process monitoring tools like Process Monitor to scan for suspicious processes created by the malware
		- Process Monitor: Process Monitor shows real-time file system, Registry, and process/thread activity
		- Process Monitor https://docs.microsoft.com

	- System Behavior Analysis: Monitoring Windows Services
		- Windows Service Manager (SrvMan): This tool can help trace malicious services initiated by the malware. It can create services without restarting Windows, delete existing services, and change service configuration.
		- Malware spawn Windows services that allow attackers to remotely control the victim machine and pass malicious instructions
		- Malware may also employ rootkit techniques to manipulate HKEY_LOCAL_MACHINE\System\CurrentControlSet\Services registry keys to hide its processes
		- Examining Windows services upon malware execution helps in identifying any suspicious services created by the malware that might run automatically or require manual intervention to get started
		- Windows Service Manager (SrvMan) https://sysprogs.com

	- System Behavior Analysis: Monitoring Startup Programs
		- Malware can alter the system settings and add themselves to the startup menu to perform malicious activities whenever the system starts
			- Steps to manually detect hidden malware
				- Check startup program entries in the registry
				- Check automatically loaded drivers 
					- C:\Windows\System32\drivers
				- Check boot.ini or bcd (bootmgr) entries
				- Check Startup Windows services
					- Go to Run / Type services.msc / Sort by Startup Type
				- Check startup folders
					- C:\ProgramData\Microsoft\Windows\Start Menu\Programs\Startup
					- C:\Users\<UserName>\AppData\Roaming\Microsoft\Windows\Start Menu\Programs\Startup

	- Startup Programs Monitoring Tool: Autoruns for Windows https://docs.microsoft.com
		- Autoruns For Windows displays programs that are configured to run automatically during user login or system boot and can help detect suspicious startup programs and processes
			- Syntax: autorunsc [-a <*|bdeghiklmoprsw>] [-c|-ct] [-h] [-m] [-s] [-u] [-vt] [[-z ] | [user]]]

	- System Behavior Analysis: Monitoring Windows Event Logs
		- Windows event logs are stored in C:\Windows\System32\winevt\Logs folder with a .etvx extension
		- Execute the malware on the Windows forensic workstation and monitor the events triggered by its execution and operations
		- Use Windows built-in Event Viewer utility to monitor events based on specific details, such as event ID,event name, event description, etc., to look for malware indicators on the workstation

	- System Behavior Analysis: Monitoring API Calls
		- Malicious programs often make use of Windows APIs to access operating system information, such as file systems, threads, registry, and kernel
		- API call monitoring helps in understanding a malware's interaction with the OS, and might provide valuable information regarding its system and network-level activities
		- Use tools like API Monitor to intercept API calls made by the malware during runtime
		- The examination of the API calls made by the malware upon execution via API Monitor tool reveals the following:
			- The malware has repetitively used “CreateFileA” and “NtCreateFile” functions to create malicious files in the system folder of the Windows forensic workstation
		- API Monitor http://www.rohitab.com

	- System Behavior Analysis: Monitoring Device Drivers
		- Malware gets installed along with the device drivers downloaded from untrusted sources, and use them as a shield to avoid detection
		- You must scan for suspicious device drivers and verify if they are genuine and downloaded from the publisher's original site
		- Go to Run / Type msinfo32 / Software Environment / System Drivers

	- Device Driver Monitoring Tool: DriverView https://www.nirsoft.net
		- DriverView utility displays a list of all device drivers currently loaded on the system. For each driver in the list, additional information, such as the load address of the driver, description, version, product name, and the company that created the driver, is displayed.

	- System Behavior Analysis: Monitoring Files and Folders
		- You can use files and folder integrity monitoring tools to examine file system and folder activity in realtime on an infected system
			- SIGVERIF 
				- It checks the integrity of critical files that have been digitally signed by Microsoft
				- To launch SIGVERIF, go to Start / Run, type sigverif, and press Enter
			- FCIV
				- It is a command line utility that computes MD5 or SHA1 cryptographic hashes for files
				- You can download FCIV at https://docs.microsoft.com
			- TRIPWIRE ENTERPRISE
				- It is an enterprise class system integrity verifier that scans and reports critical system files for changes
				- Tripwire Enterprise https://www.tripwire.com

	- File and Folder Monitoring Tool: PA File Sight https://www.poweradmin.com
		- PA file sight is a file monitoring utility that audits which user/application is deleting files, moving files, or reading files. It can generate reports with details, such as:
			- User account, including domain/Active Directory
			- User computer name
			- Target file and folder
			- Activity done on the file (read, write, delete)
			- Date and time of action

	- Files and Folders Integrity Checkers: FastSum and WinMD5
		- FastSum https://www.fastsum.com
			- FastSum is used for checking integrity of the files
			- It computes checksums according to the MD5 checksum algorithm
		- WinMD5 https://www.winmd5.com
			- WinMD5 is a Windows utility tool for computing the MD5 hashes of files
			- These fingerprints can be used to ensure that the file is uncorrupted

- Network Behavior Analysis 
	- Network Behavior Analysis: Monitoring Network Activities
		- Malware tries to communicate with the network for various activities, such as propagation, downloading malicious content, transmitting sensitive files and information, offering a remote control to attackers, etc.
		- While inspecting the forensic workstation upon malware execution, you should check the following aspects:
			- IP addresses going from and connecting to the workstation
			- Ports being opened on the workstation
			- List of DNS entries recorded on the workstation

	- Monitoring IP Addresses
		- Run Wireshark on Windows forensic workstation
		- Execute the file that is suspected to be a malware on the workstation
		- Monitor the live network traffic to look for suspicious activities
		- Locate any remote IP address that the workstation is trying to communicate to
		- Scan the IP address via online malware scanning tools to know whether it is really suspicious

	- Network Behavior Analysis: Monitoring Port
		- Malicious programs open system ports to establish a connection with remote systems, networks, or servers, and accomplish various malicious tasks
		- Reviewing port activity in realtime on the forensic workstation after malware execution helps in understanding its network capabilities
		- Example: A malware requesting port number 25 might indicate that it to trying to get connected to an email server
		- Use command line tool like Netstat to monitor all active ports and their status on the workstation

		- Netstat https://docs.microsoft.com
			- Syntax: netstat [-a] [-e] [-n] [-o] [-p Protocol] [-r] [-s] [Interval]

	- Port Monitoring Tools: TCPView and CurrPorts
		- TCPView 
			- TCPView shows a detailed listing of all TCP and UDP endpoints on your system, including the local and remote addresses, and state of TCP connections
			- TCPView https://docs.microsoft.com
		- Currports
			- CurrPorts is a network monitoring software that displays the list of all currently opened TCP/IP and UDP ports on your local computer
			- Currports https://www.nirsoft.net

	- Network Behavior Analysis: Monitoring DNS
		- Malicious programs use Domain Name System (DNS) to communicate with the Command and Control (C&C) server
		- Upon malware execution, review the DNS records stored on the workstation to understand whether it is trying to call out to a specific domain name
		- Note: Before executing the malware, clear the existing DNS cache on the workstation by entering “ipconfig /flushdns” command in the command prompt

	- DNS Monitoring Tool: DNSQuerySniffer https://www.nirsoft.net
		- DNSQuerySniffer is a network sniffer utility that shows the DNS queries sent on your system
		- It helps in identifying the DNS servers the malware tries to connect to, and the type of connection




