Respond and recover from a data breach

🔐 Cybersecurity Lab: Analyzing and Remediating a Data Breach in Google Cloud

📌 Overview

This project showcases my work in identifying, analyzing, and remediating a security breach in a cloud environment using Google Cloud Security Command Center. The lab involves detecting vulnerabilities, mitigating risks, and strengthening security controls across cloud resources.

🚀 Tasks Completed

1️⃣ Analyze the Data Breach
Investigated a massive security breach affecting applications, networks, and data repositories.
Used Google Cloud Security Command Center to identify vulnerabilities, including:
Publicly accessible Cloud Storage buckets
Overly permissive firewall rules
Compromised virtual machines
Examined PCI DSS compliance reports to detect non-compliant security settings.

2️⃣ Fix Compute Engine Vulnerabilities
Shut down the compromised VM (cc-app-01).
Created a new VM (cc-app-02) from a clean snapshot to restore system integrity.
Enhanced security settings by:
Removing public IP addresses.
Enabling Secure Boot for stronger OS integrity.
Restricting service account permissions.
Deleted the compromised VM to eliminate security risks.

3️⃣ Fix Cloud Storage Bucket Permissions
Revoked public access to the storage bucket containing sensitive data.
Enabled Uniform Bucket-Level Access to enforce stricter permission controls.
Removed unnecessary user permissions to prevent unauthorized access.

4️⃣ Limit Firewall Ports Access
Restricted SSH access to only trusted sources (Google Cloud IAP address range).
Created a new firewall rule to enforce controlled access for compute instances.

5️⃣ Fix the Firewall Configuration
Deleted overly permissive firewall rules allowing unrestricted ICMP, RDP, and SSH access.
Enabled firewall rule logging to improve audit capabilities and detect unauthorized activity.

🛠️ Key Security Improvements

✔ Eliminated publicly accessible cloud resources.

✔ Strengthened firewall rules to block unauthorized remote access.

✔ Removed excessive permissions from service accounts.

✔ Ensured secure VM configurations with proper access controls.

✔ Improved compliance with PCI DSS standards.

📌 Conclusion

Through this lab, I successfully remediated critical security vulnerabilities and reinforced cloud security best practices. This exercise provided valuable hands-on experience in incident response, security hardening, and cloud governance in Google Cloud Platform (GCP).

