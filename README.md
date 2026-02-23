# passive-active-reconnaissance-project
Cybersecurity reconnaissance lab demonstrating OSINT collection, DNS resolution, web enumeration, and vulnerability discovery against a controlled vulnerable target using industry security tools.



# Passive & Active Reconnaissance Project

## 📄 Full Report
[Download the Full PDF Report](https://github.com/M-Java86/passive-active-reconnaissance-project/blob/main/Executive%20Summary%20.pdf))

---

## Step 1: Whois Analysis

![Whois Findings](https://github.com/M-Java86/passive-active-reconnaissance-project/blob/main/Whois%20Findings%20(vulnweb.com).png))

**Finding:** Domain ownership, registrar, hosting provider, and infrastructure details were publicly accessible.

---

## Step 2: DNS Lookup
![DNS Lookup](https://github.com/M-Java86/passive-active-reconnaissance-project/blob/main/Step%202-DNS%20Lookup%20Findings.png))

**Finding:** Subdomain resolved to an AWS-hosted IP address.

---

## Step 3: Hosting & Technology Identification
![Netcraft Findings](https://github.com/M-Java86/passive-active-reconnaissance-project/blob/main/Step%203-Hosting%20%26%20Technology%20Findings%20(Netcraft).png))

**Finding:** Server hosted on AWS, Debian-based OS, PHP enabled, no HTTPS.

---

## Step 4: Google Dorking
### Admin Page Exposure
![Admin Page](https://github.com/M-Java86/passive-active-reconnaissance-project/tree/main))

### Login Page Discovery
![Login Page](https://github.com/M-Java86/passive-active-reconnaissance-project/blob/main/Step4%20login.php(Query%203).png))

**Finding:** Sensitive endpoints publicly indexed.

---

## Step 5: OSINT on Public Organization
![Course Description](https://github.com/M-Java86/passive-active-reconnaissance-project/blob/main/Step%205-Course%20description%20page.png))
![Course Syllabus]((https://github.com/M-Java86/passive-active-reconnaissance-project/blob/main/Step%205-Course%20syllabus%20page.png))
![Public PDF](https://github.com/M-Java86/passive-active-reconnaissance-project/blob/main/Step%205-Public%20course%20PDF.png))

**Finding:** Public documents reveal organizational structure and program details.

---

## Tools Used
- Whois
- nslookup
- Netcraft
- Google Dorking
- Nmap
- Kali Linux
