# NovaMart Cybersecurity Risk Assessment

## Overview

This risk assessment identifies cybersecurity risks affecting
NovaMart's systems, accounts, network, and sensitive information.

Each identified risk is evaluated using:

- Asset
- Vulnerability
- Threat
- Likelihood
- Impact
- Overall Risk Level

Likelihood and impact are classified as **Low, Medium, or High**.
The overall risk level is classified as **Low, Medium, High, or Critical**.

---

## Risk Register

| # | Asset | Vulnerability | Threat | Likelihood | Impact | Risk Level |
|---|---|---|---|---|---|---|
| 1 | Administrator Account | Weak password and no MFA | Unauthorized account access through credential attacks | High | High | Critical |
| 2 | Windows Computers | Security updates have not been installed for 8 months | Attackers could exploit known unpatched vulnerabilities | High | High | High |
| 3 | Company Wi-Fi / Network | One shared Wi-Fi password is used by all employees | Unauthorized users, including former employees, could access the network | Medium | High | High |
| 4 | Employee Accounts and Devices | Employees may be susceptible to phishing and existing protections require assessment | Phishing attacks could steal credentials or compromise accounts/devices | High | High | Critical |
| 5 | Customer Database and Backups | Main database and only backup are stored on the same server | Ransomware, hardware failure, or system corruption could affect both copies | High | High | Critical |
| 6 | Company Cloud Files | Employees have access to files they do not require for their jobs | Insider misuse or compromised employee accounts could expose, modify, or delete sensitive files | High | High | Critical |

---

## Risk 1 - Administrator Account

**Asset:** Administrator account and privileged access

**Vulnerability:** The administrator account uses a weak password
and does not have multi-factor authentication (MFA).

**Threat:** An attacker could attempt to gain unauthorized access
using password guessing, stolen credentials, or other credential attacks.

**Likelihood:** High

**Impact:** High

**Risk Level:** Critical

**Reason:** The administrator account has elevated privileges.
If compromised, an attacker could potentially access sensitive
information, modify system configurations, create or change accounts,
or disrupt company systems.

---

## Risk 2 - Unpatched Windows Computers

**Asset:** Windows computers and company systems/data accessible
from them

**Vulnerability:** Some Windows computers have not received
security updates for 8 months and may contain unpatched vulnerabilities.

**Threat:** An attacker could exploit known vulnerabilities in
outdated software to gain unauthorized access or install malware.

**Likelihood:** High

**Impact:** High

**Risk Level:** High

**Reason:** Unpatched systems may contain known security
vulnerabilities. Successful exploitation could compromise computers,
expose company information, install malware, or disrupt business
operations.

---

## Risk 3 - Shared Wi-Fi Password

**Asset:** Company Wi-Fi/network and systems accessible through
the network

**Vulnerability:** NovaMart uses one shared Wi-Fi password for
employees, making individual access difficult to control.

**Threat:** An unauthorized person, including a former employee
who still knows the password, could potentially connect to the
company network.

**Likelihood:** Medium

**Impact:** High

**Risk Level:** High

**Reason:** A shared password makes network access more difficult
to manage. If the password is disclosed or retained by former
employees, unauthorized users could potentially access the network.

---

## Risk 4 - Phishing

**Asset:** Employee accounts, credentials, company devices, and
sensitive company information

**Vulnerability:** Employees may be susceptible to phishing
attempts, and existing email-security and awareness controls
should be assessed.

**Threat:** Attackers could send phishing emails designed to
trick employees into revealing credentials, clicking malicious
links, or opening malicious attachments.

**Likelihood:** High

**Impact:** High

**Risk Level:** Critical

**Reason:** Employees have already received phishing emails.
A successful phishing attack could result in stolen credentials,
compromised accounts or devices, and unauthorized access to
company information.

---

## Risk 5 - Database Backup

**Asset:** Customer database and backup data

**Vulnerability:** The production database and its only backup
are stored on the same server, creating a single point of failure.

**Threat:** Ransomware, hardware failure, system corruption, or
another server incident could affect both the production database
and its backup.

**Likelihood:** High

**Impact:** High

**Risk Level:** Critical

**Reason:** If the server fails or is affected by ransomware,
NovaMart could lose access to both the main database and its backup.
This could prevent timely recovery of customer and order information
and affect business availability.

---

## Risk 6 - Excessive Cloud Permissions

**Asset:** Company cloud files and sensitive information

**Vulnerability:** Employees have access to cloud files that are
not required for their job responsibilities, violating the
principle of least privilege.

**Threat:** An employee could intentionally or accidentally access,
modify, delete, or disclose sensitive information. A compromised
employee account could also expose unnecessary files.

**Likelihood:** High

**Impact:** High

**Risk Level:** Critical

**Reason:** Excessive permissions increase the number of users
who can access sensitive company information, increasing the risk
of unauthorized disclosure, modification, or deletion.

---

## Conclusion

The assessment identified several high and critical cybersecurity
risks affecting NovaMart.

Priority should be given to protecting privileged accounts,
improving phishing defenses, securing database backups, applying
least-privilege access controls, patching systems, and strengthening
network access controls.

These findings will be used in the next stage of the security audit
to identify appropriate security controls and remediation actions.
