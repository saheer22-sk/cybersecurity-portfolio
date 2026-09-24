# Security Recommendations

## Overview

Based on the cybersecurity risk assessment conducted for NovaMart (Pvt) Ltd,
the following security improvements are recommended.

The recommendations are prioritized according to the potential impact of
the identified security risks.

---

## 1. Secure the Administrator Account

**Priority:** High

Immediately replace the weak administrator password with a strong,
unique password and enable Multi-Factor Authentication (MFA).

The administrator account has elevated privileges. If an attacker gains
access to this account, they could potentially access sensitive systems
and data or make unauthorized changes.

---

## 2. Improve Database Backup Security

**Priority:** High

Store database backups in a separate and secure location, such as secure
cloud backup storage or a separate backup system.

The customer database and its only backup are currently stored on the
same server. If the server fails or is affected by ransomware, both the
original database and backup could become unavailable.

Regular backup and recovery testing should also be performed.

---

## 3. Improve Phishing Awareness

**Priority:** High

Provide regular cybersecurity and phishing awareness training for all
employees.

Employees should learn how to identify suspicious emails, links,
attachments, and requests for sensitive information. They should also
know how to report suspicious emails to the appropriate person or team.

This can reduce the likelihood of successful phishing attacks.

---

## 4. Restrict Cloud File Access

**Priority:** High

Apply the Principle of Least Privilege (PoLP).

Employees should only have access to files and systems required for
their job responsibilities.

Access permissions should also be reviewed regularly and changed when
an employee changes roles or leaves the company.

This reduces the risk of unauthorized access, modification, deletion,
or exposure of sensitive information.

---

## 5. Patch Windows Computers

**Priority:** High

Install missing security updates and patches on all affected Windows
computers.

NovaMart should establish a regular patch management process to ensure
operating systems and applications remain updated.

Unpatched systems may contain known vulnerabilities that attackers
could potentially exploit.

---

## 6. Improve Wi-Fi Access Security

**Priority:** High

Replace the shared Wi-Fi password with individual employee
authentication where possible.

Network access should be reviewed regularly, and access should be
removed when an employee leaves the company.

This makes it easier to control who can access the company network and
reduces the risk of unauthorized access.

---

## Recommended Implementation Order

NovaMart should initially focus on:

1. Securing the administrator account with a strong password and MFA.
2. Creating secure, separate database backups.
3. Restricting unnecessary employee access to cloud files.
4. Installing missing Windows security updates.
5. Providing phishing awareness training.
6. Improving Wi-Fi authentication and access management.

These improvements should be followed by regular security reviews,
patch management, access reviews, backup testing, and employee
cybersecurity awareness activities.

---

## Conclusion

Implementing these recommendations will reduce the cybersecurity risks
identified during the NovaMart security audit.

The recommended controls will help improve the confidentiality,
integrity, and availability of NovaMart's systems and information.
