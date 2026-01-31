# 🛡️ Security Fundamentals & Pentesting Methodology

My notes on core information security principles and the standard penetration testing workflow, based on TryHackMe's "Introduction to Pentesting" path.

## 1. The CIA Triad
The fundamental model for information security.

* **Confidentiality:** Ensuring that data is accessed only by authorized personnel (e.g., Two-Factor Authentication, Encryption).
* **Integrity:** Assuring that data has not been modified or tampered with by unauthorized actors (e.g., Hashing, Checksums).
* **Availability:** Guaranteeing that systems and data are accessible when needed (e.g., Redundancy, DDoS protection).

## 2. The Privilege Principles
* **Principle of Least Privilege (PoLP):** Users and systems should only have the minimum level of access necessary to perform their function. This limits the potential damage if a specific account is compromised.

## 3. The Pentesting Methodology (The Cycle)
Standard phases of a penetration test:

1.  **Information Gathering (Reconnaissance):** Collecting open-source intelligence (OSINT) about the target (domains, employees, IP ranges).
2.  **Enumeration / Scanning:** Using tools (like Nmap) to discover open ports, services, and running applications.
3.  **Exploitation:** leveraging vulnerabilities found during enumeration to gain initial access.
4.  **Privilege Escalation:** Attempting to gain higher permissions (e.g., from a standard user to Administrator/Root).
5.  **Post-Exploitation:** Maintaining access, gathering loot (data), and pivoting to other systems.
6.  **Reporting:** Documenting findings, impact, and remediation steps.

## 4. Legal Framework
* **Rules of Engagement (RoE):** A formal document created before the engagement that defines the scope, allowed methods, and timeline. **Permission is everything.**
