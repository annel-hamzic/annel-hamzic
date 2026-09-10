# Hi, I'm Annel!

**`Pricing Analyst | Aspiring Systems Administrator & IT Operations Specialist`**

I specialize in systems administration, hybrid identity infrastructure, and Linux virtualization. I enjoy building hands-on labs to solve real-world enterprise infrastructure challenges, with a focus on Active Directory, Microsoft Entra ID, and cloud governance.

---

## Technical Skill Set

* **Directory & Identity Management:** Active Directory DS, Microsoft Entra ID (Azure AD), Entra Connect Sync, Password Hash Sync (PHS), Group Policy (GPO), Cloud RBAC.
* **Virtualization & Hypervisors:** KVM/QEMU, `virt-manager`, VirtualBox, Windows Server 2025/2022, Fedora Linux Workstation.
* **Networking & Security Audit:** Wireshark, Nmap, OpenVAS, Timeshift (RSYNC), Network Protocol Analysis.
* **Certifications:** CompTIA Security+

---

## Featured Portfolio Projects

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

* **LinkedIn:** [linkedin.com/in/annel-hamzic](https://linkedin.com/in/)
* **Portfolio Repository:** [Hybrid AD & Entra ID Lab](https://github.com/annel-hamzic/Hybrid-Active-Directory-Entra-ID-Lab) , [Fedora Server Hardening Lab](https://github.com/annel-hamzic/Fedora-Server-Hardening-Vulnerability-Assessment-Lab)
