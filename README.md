# 🏢 Basic Employee Onboarding (AD) (RBAC)

**Building a secure and structured Active Directory environment for a growing healthcare organization.**

---

## 📌 Problem Statement

Northstar Medical Group was a fast-growing healthcare organization that relied on a third-party Managed Service Provider (MSP) to manage its IT operations. Over time, the Active Directory environment became disorganized due to a lack of structure, documentation, and standardized processes.

User accounts were created manually with inconsistent naming conventions, there was no clear Organizational Unit (OU) structure, and Role-Based Access Control (RBAC) had not been properly implemented. Users were often assigned permissions on an ad-hoc basis rather than according to their job responsibilities.

In addition, some former employees still had active accounts, creating unnecessary security risks. The lack of centralized onboarding and access management processes also created audit gaps and increased potential HIPAA compliance risks.

The goal of this project was to redesign the Active Directory environment and create a secure, repeatable employee onboarding process based on least privilege and role-based access.

---

## 💡 Solution Overview

I built a structured Active Directory environment to improve employee onboarding, account management, and access control at Northstar Medical Group.

I created a new Active Directory domain, **NMG.com**, and designed Organizational Units for the company's primary departments, including **Finance, Human Resources, IT, and Operations**.

I then created security groups for each department and implemented a **flat Role-Based Access Control (RBAC) model**. Instead of assigning permissions directly to individual users, employees were added to the appropriate security groups based on their job roles.

I also developed a standardized user provisioning process that included consistent usernames, proper OU placement, security group membership, and least-privilege access.

To test the environment, I simulated a mock onboarding ticket and provisioned a new employee account. I verified that the user received only the resources and permissions required for their role.

I also simulated an access-control incident, **NMG-0047**, where a user received incorrect access. I investigated the issue, identified the incorrect group membership, removed the unauthorized access, assigned the correct permissions, and documented the resolution.

This solution improved the organization's Active Directory structure, simplified user administration, reduced unnecessary access, and created a more secure and scalable employee onboarding process.

---

## 🎥 Video Walkthrough

**Video walkthrough coming soon.**

I will provide a recorded demonstration of the lab showing the Active Directory environment, Organizational Units, security groups, user provisioning process, RBAC implementation, and troubleshooting scenario.

---

## 🛠️ Tools Used

- Windows Server
- Active Directory Domain Services (AD DS)
- Windows 10/11
- VirtualBox
- UTM
- Role-Based Access Control (RBAC)
- GitHub

---

## 📅 Project Timeline

| Day | Task |
|-----|------|
| **Day 1** | Domain creation and Domain Controller promotion |
| **Day 2** | Organizational Unit and security group design |
| **Day 3** | User provisioning and RBAC implementation |
| **Day 4** | Incident investigation and resolution (NMG-0047) |
| **Day 5** | Documentation, video walkthrough, and GitHub portfolio packaging |

---

## 🏆 Key Accomplishments

- Built a new Active Directory domain (**NMG.com**).
- Designed a structured Organizational Unit hierarchy for Finance, HR, IT, and Operations.
- Created department-based security groups.
- Implemented a flat RBAC model for managing employee access.
- Applied the principle of least privilege when provisioning users.
- Standardized employee account creation and group assignment.
- Simulated a real-world employee onboarding request.
- Investigated and resolved an incorrect access issue (**NMG-0047**).
- Documented the environment and troubleshooting process.
- Created a complete Active Directory project for my cybersecurity and IT portfolio.

---

## 📂 Repository Structure

AD-RBAC-Onboarding-Lab/
│
├── README.md
│   └── Main project documentation
│
├── docs/
│   └── Project documentation and diagrams
│
├── screenshots/
│   └── Active Directory and lab screenshots
│
└── videos/
    └── Video walkthrough

---

## 🔐 Security Concepts Demonstrated

This project demonstrates practical knowledge of:

- Active Directory administration
- Identity and Access Management (IAM)
- Role-Based Access Control (RBAC)
- Organizational Units (OUs)
- Active Directory security groups
- User provisioning
- Joiner processes
- Least privilege
- Access control
- Incident troubleshooting
- Account lifecycle management
- Security documentation

---

## 📚 What I Learned

This project helped me strengthen my understanding of how Active Directory can be used to manage identities and access within an enterprise environment.

I learned the difference between **Organizational Units and Security Groups**. Organizational Units are primarily used to organize and manage Active Directory objects and apply Group Policies, while Security Groups are used to control access to resources.

I also gained practical experience creating users, assigning users to the correct Organizational Units, managing security group memberships, and applying role-based access.

Most importantly, I learned why organizations should avoid assigning permissions directly to individual users. Using security groups and RBAC makes access easier to manage, audit, troubleshoot, and scale as an organization grows.

---

## 🚀 Next Steps

The next phase of this project will expand the environment by implementing additional enterprise identity and security controls, including:

- Group Policy Objects (GPOs)
- Password and account lockout policies
- Shared folder permissions
- NTFS permissions
- PowerShell user provisioning
- User offboarding
- Account disablement
- Access reviews
- Microsoft Entra ID integration
- Hybrid identity concepts
