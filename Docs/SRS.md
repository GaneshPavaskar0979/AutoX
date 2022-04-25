![SRS](/Docs/Images/Software-Requirement-Specifications.jpg)








# AutoX - SSO Client with automated COCI from & to the Vault









Index
-------------------------------------------------------------------------------------------------------------------------------
1. Introduction
           1.1 Purpose
           1.2 Intended Audience
           1.3 Intended Use
           1.4 Scope
           1.5 Definitions and Acronyms

2. Overall Description
           2.1 User Needs
           2.2 Assumptions and Dependencies

3. System Features and Requirements
            3.1 Functional Requirements
            3.2 External Interface Requirements
            3.3 System Features
            3.4 Nonfunctional Requirements









1. Introduction
-----------------------------------------------------------------------------------------------
1.1 Purpose
The purpose of this document is to present a detailed description of the AutoX tool/system. It will explain the purpose and features of the system, the interfaces of the system, what the system will do, the constraints under which it must operate and how the system will react to external stimuli.

1.2 Intended Audience
This document is intended for both the stakeholders and the developers of the system.

1.3 Scope
This software system will act as SSO client/agent which automates check-out and check-in of credentials from Credential store (Vault). 
Provides automated check-out and check-in of shared access credentials from the credential store - Vault.
AutoX is the single sign-on client that is installed on user workstations. This agent automates the check-out and single sign-on with privileged credentials into various systems.

1.4 Definitions and Acronyms
Vault: Digital secure store.
COCI: Check-out (read) and Check-in (release).
Privileged credentials: Administrative credentials of business critical systems.
Privileged Users: Users who are authorized to access privileged credentials or have access.




2. Overall Description
-----------------------------------------------------------------------------------------------
2.1 User Needs
This system will be designed to maximize the privileged user’s productivity by providing tools to single sign on with automated COCI and injection, which would otherwise have to be performed manually.
More specifically, this tool is designed to allow user to access all applications with automated COCI. It will add ease in daily work and user can focus on important tasks.

2.2 Assumptions and Dependencies
- HashiCorp Vault should be reachable from user’s workstation.
- Customer should have windows systems in environment.

2.3 System environment /architecture 
 





3. System Features and Requirements
-----------------------------------------------------------------------------------------------
3.1 Functional Requirements
3.1.1 System should able to check out credentials from Vault.
3.1.2 System should able to inject credentials into web, think and thick clients.
3.1.3 System should able to check in credentials into Vault after user exits/logout from session.

3.2 External Interface Requirements
3.2.1 System interfaces
The application runs in the all latest version of windows and windows server OS.

3.2.2 User interfaces
The application GUI provides menus, toolbars, buttons, panes allowing for easy control by a keyboard and a mouse.

3.2.3 Software interfaces
Application allows integration with Vault.

3.3 System Feature
SSO for web, thin and thick client applications with automated COCI process.
Credentials stored into secure location i.e. Vault.

3.4 Nonfunctional Requirements
3.4.1 Usability Requirements
Home page should be centralized dashboard to go to launch any application & all labels should be meaningful.

3.4.2 Performance Requirements
It should support concurrent sessions & launch application in minimal time.
	
3.4.3 Compatibility Requirements
It should support all types of windows based OS.
