# Incident-Handling-Journal


---

## Date: 10/04/2024
**Entry #1**

### Description
A small U.S. health care clinic experienced a security incident which severely disrupted their business operations.

### Tool(s) Used
None

### The 5 W's
- **Who:** Small group of unethical hackers who are known to target organizations in healthcare and transportation industries.
- **What:** The attackers gained access to the company's network through targeted phishing emails sent to several employees. The emails contained a malicious attachment that installed malware on the employee's computer once downloaded.
- **When:** Tuesday 9:00 AM
- **Where:** At a healthcare company
- **Why:** The attackers demanded a large sum of money in return for giving back access to the encrypted files, which caused disruption to ongoing business activities.

### Additional Notes
- How can this be prevented in the future?
- Is there enough employee training and awareness on phishing attacks?
- How are they going to recover?

---

## Date: 15/04/2024
**Entry #2**

### Description
An employee received an email containing a password-protected spreadsheet file. The password was provided in the email. Upon entering the password to open the file, a malicious payload was executed on their computer.

### Tool(s) Used
- VirusTotal
- Zenbox Sandbox
- Venus Eye Sandbox
- Rising MOVES Sandbox

### The 5 W's
- **Domain names:** `org.misecure.com` is reported as a malicious domain in the VirusTotal report.
- **IP address:** `207.148.109.242` is listed in the VirusTotal report and associated with the `org.misecure.com` domain.
- **Hash value:** `287d612e29b71c90aa54947313810a25` is an MD5 hash listed in the VirusTotal report.
- **Network/host artifacts:** HTTP requests to `org.misecure.com` were observed.
- **Tools:** Input capture used to steal sensitive information.
- **TTPs:** Command and control channels used by the malware.

### Additional Notes
- The file hash has been reported as malicious by over 50 vendors.
- The file hash is known as the malware Flagpro, commonly used by the advanced threat actor BlackTech.

---

## Date: 16/04/2024
**Entry #3**

### Description
A phishing alert was received about a suspicious file being downloaded on an employee's computer. The attachment’s hash was already verified as malicious.

### Tool(s) Used
None

### The 5 W's
- **Who:** An email from “def communications”
- **What:** A SERVER-MAIL phishing attempt with a potential malware download.
- **When:** Wednesday, July 20, 2022, 09:30:14 AM
- **Where:** Sent to company email
- **Why:** The threat actor wanted to access the organization's files through malware in the downloadable attachment.

### Additional Notes
- Known malicious file hash: `54e6ea47eb04634d3e87fd7787e2136ccfbcc80ade34f246a12cf93bab527f6b`
- The email contained grammatical errors and a password-protected attachment, “bfsvc.exe,” which was downloaded and opened on the affected machine.

---

## Date: 21/04/2024
**Entry #4**

### Description
Phishing attack on company employees.

### Tool(s) Used
- Email spoofing tools

### The 5 W's
- **Who:** Unidentified threat actors sent phishing emails impersonating the IT department.
- **What:** Emails requested urgent password resets due to a system upgrade. The emails contained a link to a fake login page resembling the company’s internal portal. Some employees entered their credentials.
- **When:** 9:00 AM
- **Where:** The incident occurred within the company's email system.
- **Why:** The attackers aimed to gain unauthorized access to company systems and data by exploiting employee trust.

### Additional Notes
- Employees need to be more aware of phishing emails.
- Training is needed.
- How were the attackers aware of the company’s internal portal?

