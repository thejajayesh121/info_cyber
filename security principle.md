# security principles
## learning objectives:
- Understanding the CIA Triad and its importance.
- Explain Risk,privecy,and Accountability.
- Relate security principles to real-world cyber incidents.

# CIA Triad
- The Triad forms the foundations ofn information security.
- Each element ensures the information remains safe and trustworthy.

|Element             |Description                                               |Example                                               |
|------------------- |----------------------------------------------------------|------------------------------------------------------|
|**confidentiality** |ensure the data is accessible only to authorized users.   |Encrypting files,using passwords,access control lists.|
|**integrity**       |Ensure data is accurate, consistent,and not tampered with.|Using hashing, digital,signatures,checksums.          |
|**Availability**    |Ensure systems and data are available when needed.        |Redundant servers,backups,DDoS protection             |

![download](https://github.com/user-attachments/assets/46096255-a8b3-4efa-93f3-a299ad9c7aa1)
# key concepts 
-Data breaches often occur when one or more CIA principles are comprimised.
-Balance is key-too much focus on one(e.g.availability)can weaken another(e.g.,confidentiality).

# examples
-confidentiality


## Risk,privecy aand Accountability
#Risk
-Definition:probability of a threat exploiting a vulnerability to cause harm.

**components:**
-Threat-->something that can cause damage.
-vulnerability-->weakness that can be exploited
-impact-->damage if threat is realized

**Formula:**
Risks=Threat x vulnerability x Impact

**Example:**
-Threat: phishing 
-vulnerability:Employee lack of awareness 
-Impact:Creadential theft,financial loss
![GettyImages-1343006928-1401x788-49696df](https://github.com/user-attachments/assets/134a5f69-afa3-4404-a3be-5b53388bce8b)

# Privecy
- Protecting personal and sensitive infrormation of indiividuals.
- Governed by laws like GDPR,DPDP,Act(India),HIPM.
![download](https://github.com/user-attachments/assets/c302ab2b-ad48-41c0-9011-b0e0ef80a233)

**key practices**
-Data minimization
-informed consent
-Data anonymization

Example:A healthcare app must not share user health data without consent.

# Accountability
Ensure every action in an IT system can be traced back to an individual.

**Acheived through:**
-Logging&auditing 
-Users access tracking 
-Non-repudiation mechanisms
Example: Audit logs in firewalls to trace malicious users actions.

# Real-World Case Studies
|**case**           |**Description**                               |**Violated priciple**         |
|-------------------|----------------------------------------------|------------------------------|
| Wanna cry(2017)   | Ransomware disabled hospital systems worldwide | Availability                  |
| Equifax Breach(2017)   | Personal data 143M users leaked               | confidentiality&Intergrity    |
| Twitter Hack(2020) | Insider access to admin tools                 | confidentiality&Accountability



