# Hi, I'm Annel!

**`Pricing Analyst | Aspiring Systems Administrator & IT Operations Specialist`**

I specialize in systems administration, hybrid identity infrastructure, and Linux virtualization. I enjoy building hands-on labs to solve real-world enterprise infrastructure challenges, with a focus on Active Directory, Microsoft Entra ID, and cloud governance.

---

## Technical Skill Set

* **Directory & Identity Management:** Active Directory DS, Microsoft Entra ID (Azure AD), Entra Connect Sync, Password Hash Sync (PHS), Group Policy (GPO), Cloud RBAC.
* **Security Monitoring & Hybrid Cloud:** Microsoft Sentinel, Microsoft Defender portal, Azure Arc, Azure Monitor Agent, Data Collection Rules, KQL.
* **Scripting & Automation:** PowerShell, Python (Azure SDK), Bash.
* **Virtualization & Hypervisors:** KVM/QEMU, `virt-manager`, VirtualBox, Windows Server 2025/2022, Fedora Linux Workstation.
* **Networking & Security Audit:** Wireshark, Nmap, OpenVAS, Timeshift (RSYNC), Network Protocol Analysis.
* **Certifications:** CompTIA Security+

---

## Featured Portfolio Projects

### [Sentinel Hybrid SIEM Lab](https://github.com/annel-hamzic/sentinel-hybrid-siem-lab)
* Built a hybrid security monitoring lab: on-premises **Windows Server 2022** and **Ubuntu Server** VMs on **KVM/virt-manager**, onboarded to Azure with **Azure Arc** and sending security logs to **Microsoft Sentinel** through the **Azure Monitor Agent**.
* Wrote three custom **KQL** analytics rules mapped to **MITRE ATT&CK** (SSH brute force, Windows failed-logon brute force, and accounts added to the Administrators group), and confirmed each one by triggering a real incident.
* Automated attack simulation with **PowerShell** and security reporting with **Python** (Azure Monitor Query SDK).
* Worked around a tenant policy that blocked device-code sign-in by onboarding servers with a least-privilege **service principal**, scoped to one resource group, with a one-day secret.

### [Hybrid Active Directory & Microsoft Entra ID Identity Lab](https://github.com/annel-hamzic/Hybrid-Active-Directory-Entra-ID-Lab)
* Designed and deployed a virtualized hybrid identity lab bridging an on-premises Windows Server Domain Controller with Microsoft Entra ID on a **Fedora Linux** host via **KVM/virt-manager**.
* Configured Organizational Unit (OU) filtering and alternative UPN suffix mappings to scope **Password Hash Synchronization (PHS)** using Microsoft Entra Connect.
* Diagnosed and resolved MSAL application registration failures (`AADSTS700027`) by troubleshooting VM-to-host clock skews using `w32tm`.
* Enforced cloud Zero Trust security controls through **Security Defaults** and scoped **Role-Based Access Control (RBAC)** delegation (Helpdesk Administrator).

### [Fedora Server Hardening & Vulnerability Assessment Lab](https://github.com/annel-hamzic/Fedora-Server-Hardening-Vulnerability-Assessment-Lab)
* Deployed a **Fedora Server 44** VM on **KVM/QEMU**, then hardened it from a default install to a locked-down baseline: non-standard SSH port, disabled root login, and **ED25519** key-based authentication in place of passwords.
* Updated **SELinux** port policy (`semanage port`, `ssh_port_t`) and **firewalld** rules in tandem so the relabeled SSH port stayed enforced under SELinux rather than working around it.
* Ran before/after **Nmap** scans and NSE vulnerability scripts to validate the reduced attack surface and check for exposed CVEs on remaining open services.
* Applied and verified security patches via `dnf update --security`, closing the loop from baseline scan to remediation.

---

## Connect With Me

* **LinkedIn:** [linkedin.com/in/annelhamzic](https://linkedin.com/in/annelhamzic)
* **Portfolio Repository:** [Sentinel Hybrid SIEM Lab](https://github.com/annel-hamzic/sentinel-hybrid-siem-lab), [Hybrid AD & Entra ID Lab](https://github.com/annel-hamzic/Hybrid-Active-Directory-Entra-ID-Lab), [Fedora Server Hardening Lab](https://github.com/annel-hamzic/Fedora-Server-Hardening-Vulnerability-Assessment-Lab)
