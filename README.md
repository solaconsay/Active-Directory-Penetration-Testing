# 🛡️ Active Directory Penetration Testing - Learning Journal

This project documents my hands-on journey in learning and conducting internal Active Directory (AD) penetration testing. The exercises simulate real-world cyberattacks to better understand security weaknesses in AD environments and how to detect, exploit, and mitigate them.

## 📚 About

This repository contains detailed notes, proof-of-concepts (PoCs), attack paths, and defense strategies used in various phases of an AD-focused penetration test. The project is structured week-by-week and includes environment setup, enumeration, exploitation, post-exploitation, and reporting.

## 🧠 Learning Goals

- Understand Active Directory architecture and its security mechanisms.
- Perform internal network reconnaissance and enumeration.
- Simulate real-world attacks such as LLMNR poisoning, SMB relay, Kerberoasting, Pass-the-Hash, and Golden Ticket attacks.
- Practice privilege escalation using tools like PowerView, BloodHound, and Mimikatz.
- Write structured, actionable penetration testing reports with executive summaries and mitigation steps.

## 🛠️ Tools Used

- 🔍 Enumeration & Scanning:
  - `Nmap`
  - `NetExec`
  - `Kerbrute`
  - `Responder`
  - `Greenbone OpenVAS`
  - `Passive_discovery6`

- 🧨 Exploitation:
  - `Impacket toolkit`
  - `Responder + ntlmrelayx`
  - `Hashcat`
  - `Metasploit`
  - `MITM6`

- 🔐 Post-Exploitation & Privilege Escalation:
  - `PowerView`
  - `BloodHound`
  - `Mimikatz`
  - `Secretsdump`
  - `Ticketer.py`

## 🧪 Attack Techniques Demonstrated

- LLMNR/NBT-NS Poisoning
- SMB Relay Attack
- Kerberoasting / AS-REP Roasting
- Pass-the-Hash & Pass-the-Ticket
- Golden Ticket Attack
- Token Impersonation
- RID Brute-Forcing
- IPv6 MITM6 Attacks
- LDAP Injection & DNS Poisoning
- Zero-Day Testing (CVE-2024-49113 - LDAP Nightmare)

## 🧱 Lab Setup

The test environment includes:

- **DC1**: Domain Controller for `FAMILYGUY.local`
- **PC1 / PC2**: Domain-joined clients with local admin misconfigurations
- **Attacker VM**: Kali/Parrot with all tools installed
- **Hack The Box AD VM**: External closed-box test environment

## 📄 Structure

The content is divided by weekly progress:

- `Week 1`: AD fundamentals & pentesting concepts
- `Week 2-3`: Reconnaissance & enumeration
- `Week 4-5`: Exploitation techniques
- `Week 6-7`: Privilege escalation
- `Week 8-9`: Post-exploitation & mitigation
- `Week 10-11`: HTB AD pentest simulation & reporting

## 📖 Reporting Template Included

A sample pentest report is included following industry standards:
- Executive summary
- Severity rating
- Technical findings with screenshots
- Remediation recommendations

## 🔐 Disclaimer

This project is intended **strictly for educational and ethical use only**. Do not use any techniques documented here on systems you do not own or have permission to test.

## 📎 References

- HackTheBox Blog: [AD Pentest Cheatsheet](https://www.hackthebox.com/blog/active-directory-penetration-testing-cheatsheet-and-guide)
- MITRE ATT&CK: [AD-related techniques](https://attack.mitre.org/)
- Microsoft Security Docs
- Other resources listed in the journal

## 👨‍💻 Author

**Sherwin Laconsay**  
Cybersecurity Enthusiast | Network Analyst

Connect with me on [LinkedIn](https://www.linkedin.com/in/s-laconsay/) or check out more of my work [here](https://laconsaylab.com/).

---

