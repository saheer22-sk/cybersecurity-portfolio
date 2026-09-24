# Security Controls Assessment

## Overview

This security controls assessment identifies appropriate safeguards to reduce the cybersecurity risks discovered during the NovaMart security audit.

The controls are categorized as:

- **Technical Controls** – Security measures implemented using technology.
- **Administrative Controls** – Policies, procedures, training, and management processes.
- **Physical Controls** – Controls used to physically protect systems and facilities.

---

## 1. Administrator Account Security

**Risk:** Weak administrator password and no Multi-Factor Authentication (MFA).

### Recommended Control 1: Strong Password Policy

**Control Type:** Administrative

Implement a strong password policy for administrator accounts. Administrators should use strong and unique passwords.

**Why:**  
Strong password requirements reduce the risk of password guessing and credential-based attacks.

### Recommended Control 2: Multi-Factor Authentication (MFA)

**Control Type:** Technical

Enable MFA for administrator accounts.

**Why:**  
MFA requires an additional authentication factor. If an attacker obtains the administrator password, the additional factor can help prevent unauthorized access.

---

## 2. Unpatched Windows Computers

**Risk:** Some Windows computers have not received security updates for eight months.

### Recommended Control 1: Install Security Updates

**Control Type:** Technical

Install required security patches and updates on affected Windows computers.

**Why:**  
Security updates fix known vulnerabilities and reduce the possibility of attackers exploiting known weaknesses.

### Recommended Control 2: Patch Management Process

**Control Type:** Administrative

Implement a regular patch management policy and process.

**Why:**  
A patch management process helps ensure that security updates are checked, tested, and installed regularly.

---

## 3. Company Wi-Fi Security

**Risk:** One shared Wi-Fi password is used by all employees.

### Recommended Control 1: Individual Authentication

**Control Type:** Technical

Replace the shared Wi-Fi password with individual employee authentication where possible.

**Why:**  
Individual authentication makes it easier to control network access. Access for a specific employee can be removed without affecting other employees.

### Recommended Control 2: Wi-Fi Access Management

**Control Type:** Administrative

Create a process for reviewing Wi-Fi access and removing access when employees leave the company.

**Why:**  
This reduces the risk of former employees or other unauthorized users retaining access to the company network.

---

## 4. Phishing Risk

**Risk:** Employees are receiving phishing emails.

### Recommended Control 1: Security Awareness Training

**Control Type:** Administrative

Provide regular phishing and cybersecurity awareness training to employees.

**Why:**  
Training helps employees recognize suspicious emails, links, attachments, and requests for credentials. Employees should also know how to report suspicious emails.

---

## 5. Database Backup Security

**Risk:** The customer database and its only backup are stored on the same server.

### Recommended Control 1: Separate Backup Location

**Control Type:** Technical

Store backups in a separate and secure location instead of keeping the only backup on the production database server.

**Why:**  
If the main server fails, becomes corrupted, or is affected by ransomware, a separate backup can be used to restore important data.

### Recommended Control 2: Backup and Recovery Process

**Control Type:** Administrative / Technical

Implement regular backups and test the recovery process.

**Why:**  
Regular backup and recovery testing helps ensure that NovaMart can recover customer and order data following an incident.

---

## 6. Excessive Cloud File Access

**Risk:** Employees can access cloud files that are not required for their jobs.

### Recommended Control 1: Principle of Least Privilege

**Control Type:** Technical

Restrict employee access according to their job responsibilities.

**Why:**  
Employees should only have access to the files and systems required to perform their jobs. This reduces the risk of unauthorized viewing, modification, or deletion of sensitive information.

### Recommended Control 2: Regular Access Reviews

**Control Type:** Administrative

Regularly review employee access permissions.

**Why:**  
Access reviews help identify unnecessary permissions and ensure that access is changed or removed when an employee changes roles or leaves the company.

---

## Conclusion

The assessment identified several controls that can reduce NovaMart's cybersecurity risks. Priority should be given to protecting privileged administrator accounts, patching vulnerable systems, improving authentication, strengthening backup practices, reducing unnecessary access, and improving employee security awareness.

Implementing these controls can improve the confidentiality, integrity, and availability of NovaMart's systems and information.
