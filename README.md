# Enterprise IAM Hybrid Identity Lab (AD DS + Entra ID)

A simulated enterprise Identity and Access Management (IAM) environment demonstrating hybrid identity architecture, automated user lifecycle management, and cloud-based access control using Microsoft Entra ID.

# Enterprise IAM Hybrid Identity Lab (AD DS + Entra ID)

A simulated enterprise Identity and Access Management (IAM) environment demonstrating hybrid identity architecture, automated user lifecycle management, and cloud-based access control using Microsoft Entra ID.

## What this lab simulates

This project replicates a real enterprise IAM environment:

- HR-driven user creation process (simulated via CSV input)
- On-prem Active Directory as the authoritative identity source
- Automated Joiner/Mover/Leaver (JML) lifecycle using PowerShell
- Synchronisation of identities to Microsoft Entra ID using Entra Connect
- Cloud-based authentication and access control using MFA and Conditional Access policies

- ## What this lab simulates

This project replicates a real enterprise IAM environment:

- HR-driven user creation process (simulated via CSV input)
- On-prem Active Directory as the authoritative identity source
- Automated Joiner/Mover/Leaver (JML) lifecycle using PowerShell
- Synchronisation of identities to Microsoft Entra ID using Entra Connect
- Cloud-based authentication and access control using MFA and Conditional Access policies

- ## Key technologies used

- Active Directory Domain Services (AD DS)
- Microsoft Entra ID
- Microsoft Entra Connect
- PowerShell (automation for identity lifecycle)
- Windows Server
- Conditional Access (Entra ID)
- Multi-Factor Authentication (MFA)

- ## Identity lifecycle (Joiner / Mover / Leaver)

This lab demonstrates a full identity lifecycle model:

- Joiner: New user created in Active Directory from HR-style CSV input
- Mover: User group/department changes reflected in access updates
- Leaver: User account disabled and access revoked across on-prem and cloud systems

These processes simulate real enterprise identity governance practices used to ensure secure and compliant access management.
## Next steps

- Implement PowerShell automation for bulk user provisioning
- Configure Entra ID synchronization with on-prem Active Directory
- Implement Conditional Access policies for cloud applications
- Build SSO integration using SAML/OIDC for enterprise applications
