## Key Areas
- Understand risk and apply risk analysis process
- Threat Modeling concepts and processes 
- Compliance, legal, regulatory, and privacy
- Professional ethics - ISC<sup>2</sup> code
- Security governance principles (ITIL, oversight)
- Security policies, standards, procedures and guidelines (know "suggested vs. "mandatory")  
## Intro
Security professionals evaluate risks against our critical assets and deploy safeguards to mitigate those risks. The Security and Risk Management domain focuses on risk analysis and mitigation. It details security governance, or the organizational structure required for a successful information security program. Success is usually tied to the right people in the right roles. Not typically budget or staff size.

## 1.1 Understand, adhere to, and promote professional ethics
### 1.1.1 ISC<sup>2</sup> Code of Ethics
### 1.1.2 Organizational code of ethics


## 1.2 Understand and apply security concepts
### 1.2.1 Confidentiality, integrity, and availability, authenticity and non-repudiation
#### CIA Triad
![](../resources/Pasted%20image%2020230108185812.png)  
Confidentiality, integrity, and availability are referred to as the CIA triad, which is the cornerstone concept of information security. It is sometimes also described by its opposite: disclosure (Confidentiality), alteration (Integrity), and destruction (Availability) (DAD).  

##### Confidentiality
- Seeks to prevent the unauthorized disclosure of information; it keeps data a secret.
###### Example Attack
Theft of personally identifiable information (PII), such as credit card information.  
##### Integrity
- Prevents unauthorized modification of information; unauthorized write access to data.
- There are two types of integrity.  
	- Data Integrity - protect information from unauthorized modification
	- System Integrity - protect a system (such as a server), from unauthorized modification.  
##### Availability
- Ensures that information is available when needed.
###### Example Attack
- Denial of Service (DoS) attack
#### Accountability
- Holds users accountable for their action.
- Typically done by logging and analyzing audit data.
- Keeps honest people honest. For some users, knowing that data is logged is not enough to provide accountability; they must know the data is logged and audited.
#### Non-repudiation
- User cannot deny (repudiate) having performed a transaction.
- Combines and relies on authentication and integrity
- Authenticates the identity of a user who performs a transaction
**Example:** Proving you signed a contract to buy a car (authenticating your identity as the purchaser) is not useful if the car dealer can change the price from $20k to $40k (violate the integrity of the contract).  
#### Least Privilege and Need to Know
Users should be granted the minimum amount of access (authorization) required for job duty. Need to know is **more** granular. The user <u>must</u> need to know that specific piece of information before accessing it.
#### Subjects and Objects
- **subject** - active entity on a data system. Most examples invole people accessing data files, but computer programs can be subjects as well. A dll or script that updates database files with new information is also a subject.
- **object** - passive data within the system. Can range from documents on physical paper to database tables to text file. <u>They are passive and do not manipulate other objects.</U>
#### Defense in Depth
- Also called layered defense; applies multiple safeguards/controls to reduce risk and protect an asset. Any single control may fail, but by deploying multiple controls, you improve the confidentiality, integrity, and availability of your data.


## 1.3 Evaluate and apply security governance principles
### 1.3.1 Alignment of the security functions to business strategy, goals, mission, and objectives
#### Security Planning
*Should include three types of plans*  
**Strategic** - Long term, stable plan that should include a risk assessment. (5-yr horizon, annual updates)  
**Tactical** - Midterm plan developed to provide more details on goals of the strategic plan. (usually ~1 year)  
**Operational** - Short-term, highly detailed plan based on the strategic and tactical plans. (montly, quarterly)    

### 1.3.2 Organizational processes (e.g., acquisitions, divestitures, and governance committes)  

### 1.3.3 Organizational roles and responsiblities  

### 1.3.4 Security control frameworks  

### 1.3.5 Due care/due diligence

## 1.4 Determine compliance and other requirements
### 1.4.1 Contractual, legal, industry standards, and regulatory requirements  
### 1.4.2 Privacy requirments  



## 1.5 Understand legal and regulatory issues that pertain to information security in a holistic context
Complying with laws and regulations is a priority for top information security management. Ignorance is never a valid excuse for breaking the law.  
#### Major Legal Systems
The three major systems of law are civil, common, and religious law.
#### Civil law (legal system)
- The most common of the major legal systems and is employed by many countries.
- Leverages codified laws or statutes to determine what is considered to be within the bounds of law.
- Legislative branch typically wields the power to create laws, thee is still a judicial branch that is tasked with the interpretation of existing laws.
- The most significant difference between civil and common law is that under civil law judicial precedents and particular case rulings do not carry the weight they would have under common law.
#### Common law
- Used in the United States, Canada, the UK, and most former British colonies, amongst others.
- English influence has been the main indicator of common law being used.
- Primary distinguishing feature is the significant emphasis on particular cases and judicial precedents as determinants of laws.
- Though there is typically also a legislative body responsible for the creation of new statutes and laws, judicial rulings can sometimes supersede those laws.
- Due to the emphasis on judges' interpretations, thee is significant possibility that as society changes, judicial interpretations may also change.
#### Religious and customary law
- Religious doctrine or interpretation serves as the primary source of legal understanding and statutes.
- Wile Christianity, Judaism, and Hinduism have influenced national legal systems, **Islam** serves as the most common source.
- **Customary** law refers to customs or practices that are so commonly accepted by a group that the custom is treated as a law. Can be later codified as laws, but the emphasis on the acceptance by a group is quite important.
### 1.5.1 Cybercrimes and data breaches  
### 1.5.2 Licensing and intellectual Property (IP) requirements  
### 1.5.3 Import/export controls  
### 1.5.4 Transborder data flow
### 1.5.5. Privacy
## 1.6 Understand requirements for investigation types (i.e., administrative, criminal, civil, regulatory, industry standards)
## 1.7 Develop, document, and implement security policy, standards, procedures, and guidelines  
## 1.8 Identify, analyze, and prioritize Business Continuity (BC) requirements  
### 1.8.1 Business Impact Analysis (BIA)  
### 1.8.2 Develop and document the scope and the plan  

## 1.9 Contribute to and enforce personnel security policies and procedures.
### 1.9.1 Candidate screening and hiring  
### 1.9.2 Employment agreements and policies  
#### Security Policy Development  
##### Four Levels of Security Policy Development  
###### Acceptable Use Policy  
*Assign roles and responsiblities.  
###### Security Baselines  
*Define "minimum levels".  
- Developing new safeguards equals establishing a **new baseline**. Current compliance with existing baselines is not a valid consideration point.  
###### Security Guidelines  
*Offer Recommendations.  
###### Security Procedures  
*Detailed step-by-step.  

### 1.9.3 Onboarding, transfers, and termination processes  
### 1.9.4 Vendor, consultant and contractor agreements and controls  
### 1.9.5 Compliance policy requirements  
### 1.9.6 Privacy policy requirements  



## 1.10 Understand and apply risk management concepts
### 1.10.1 Identify threat and vulnerabilities  
### 1.10.2 Risk assessment/analysis  
#### Risk Factors
*Increases risk or susceptibility*  

**Physical damage** - Natural disaster, power loss or vandalism  
**Malfunctions** - Failure of systems, networks, or peripherals  
**Attacks** - Purposeful acts wheter from the inside or outside, such as unauthorized disclosure  
**Human Errors** - Usually considered accidental incidents vs attacks are on purpose  
**Application Errors** - Failures of the application, including the operating system.  

#### Risk Categories  
*Category is a group of potential causes of risk*  
**Damage** - Results in physical loss of an asset or the inability to access the asset.  
**Disclosure** - Disclosing critical information regardless of where or how it was disclosed.  
**Loses** - These might be permanent or temporary, including altered dta or inaccessible data.  


### 1.10.3 Risk response  
### 1.10.4 Countermeasure selection and implementation  
### 1.10.5 Applicable types of controls (e.g., preventive, detective, corrective)  
### 1.10.6 Control assessments (security and privacy)  
### 1.10.7 Monitoring and measurement  
### 1.10.8 Reporting  
### 1.10.9 Continuous improvement (e.g., Risk maturity modeling)  
### 1.10.10 Risk frameworks  
## 1.11 Understand and apply threat modeling concepts and methodologies  
## 1.12 Apply Supply Chain Risk Management (SCRM) concepts  
### 1.12.1 Risks associated with hardware, software, and services  
### 1.12.2 Third-party assessment and monitoring  
### 1.12.3 Minimum security requirments  
### 1.12.4 Service level requirments  
## 1.13 Establish and maintain a security awareness, education, and training program  
### 1.13.1 Methods and techniqes to present awareness adn training (e.g., social engineering, phishing, security champions, gamification)  
### 1.13.2 Periodic content reviews  
### 1.13.3 Program effectiveness evaluation  




