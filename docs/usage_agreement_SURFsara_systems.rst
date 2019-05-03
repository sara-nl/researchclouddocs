Terms and Conditions Research Cloud (3/5/2019)
***********************************************

1) Introduction
====================================

SURF Research Cloud provides a National Self Service Virtual Research Environment (VRE), consisting of a portal and its underlying platform, over a broad range of services, which enables collaborative working across institutes in a federated and secure manner to accelerate research.

It is a SURF innovation project, currently in the pre-production phase.

The environtment is available on the base of “best effort”. This means we do our best to keep the environment steadily available as long as possible, but we cannot guarantee any specific uptime yet. 

2) Helpdesk
====================================

* Support is available mostly Monday to Friday from 9:00 until 17:00:
* Telephone: 020 800 14 00
* Email: helpdesk@surfsara.nl

Find more details about our helpdesk here: https://www.surf.nl/en/purchasing-services-from-surfsara/helpdesk-surfsara-services

3) Security Measures 
====================================

Organizational level
----------------------

1. SURFsara is an ISO 27001 certified company where privacy, continuity and security policies are audited every year.
2. Information security is maintained by specifying roles and responsibilities and granting minimal access based on these roles and responsibilities.
3. All personnel at SURFsara is screened and trained in securing systems and data. 
4. SURFsara has an Acceptable Use Policy for employees to prevent misuse of equipment and services. 
5. Equipment for services is securely placed in a ISO 27001, ISO 22301, PCI/DSS and SSAE 16 / SOC2 certified datacenter which is classified to store data with the highest data classification.
6. All Logons to any system are only allowed with encrypted connections.
7. SURFsara has a supplier security policy.

Service component level
------------------------

Research Cloud is based on a variety of services or service components. Currently the main components are:

* SURF Research Cloud Portal and Platform: Supports workflows to create and manage Virtual Research Environments 
* Science Collaboration Zone: Federated identity and access management, and creation and management of Collaborative Organizations
* SURF Research Drive: Persistent Storage for Collaborative Organizations
* HPC Cloud: SURF Private Cloud solution for deployment of Workspaces

Some of these components are in production and others are in development. But all components take security measures.
Utimately all service components will be audited against either the SURF normenkader or ISO 27001.

See the following paragraphs for more details:

A. Security measures SURF Research Cloud Portal and Platform
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

  * Standard Services

    1. Hardware and software used by the service is governed by an asset and configuration management system on the service or unit level. Procedures are in place to prevent data loss or leakage when discarding equipment.
    2. Virtual and physical access restrictions are in place based on the minimal needed privileges. Access to systems is logged and monitored. 
    3. Systems are scanned for vulnerabilities. Announced vulnerabilities and scanned vulnerabilities are registered and mitigated through the change management process.
    4. Upgrading the services is based on an OTAP process.
    5. The software used is open-source or developed at SURFsara. This allows for inspection of the source-code and effectively review and pentest the production software on security issues.


  * Security Services which can be taken by users to increase security levels

    6. Two factor authentication (not avialable yet)
    7. Use security features of Cloud providers
    8. Anonymize data

B. Security measures Science Collaboration Zone 
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

  * Standard Services

  * Security Services which can be taken by users to increase security levels


.. TODOcument

C. Security measures SURF Research Drive
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

  * Standard Services

    1. Annual audits 

        1. Technical audits with pen-testing
        2. Compliancy with SURF Standard Framework for Cloud Services, AVG & GDPR Security

    2. Server-side encryption
    3. Data encrypted in transit (SSL) (Qualys SSLtest A rating)
    4. 2-factor authentication (near future) to check both knowledge (username/password) and possession (SMS, token)
    5. Review and if applicable improvement of used open-source software
    6. Vulnerability scans performed regularly. Issues are solved following ISO 27001 standards


  * Security Services which can be taken by users to increase security levels

    7. Options to encrypt data at rest 
    8. Recommendation to users to install virus checkers on their laptops in order to prevent malware from being uploaded. 
    9. In the future we would also like to offer a service to chach data stored for malware in consultation with institutions.


D. Security measures HPC Cloud
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

  * Standard Services

    1. Hardware and software used by the service is governed by an asset and configuration management system on the service or unit level. Procedures are in place to prevent data loss or leakage when discarding equipment.
    2. Virtual and physical access restrictions are in place based on the minimal needed privileges. Access to systems is logged and monitored. 
    3. Data encryption is supported for data in transit and data at rest.
    4. Systems are scanned for vulnerabilities. Announced vulnerabilities and scanned vulnerabilities are registered and mitigated through the change management process.
    5. Upgrading the services is based on an OTAP process.
    6. The software used is open-source or developed at SURFsara. This allows for inspection of the source-code and effectively review and pentest the production software on security issues.


  * Security Services which can be taken by users to increase security levels

    7. Encrypt data in transit and at rest
    8. Implement tight network and firewall rules to limit access to VMs


4) Acceptable Usage Agreement SURF Research Cloud
==================================================

This usage agreement (hereinafter: “the Agreement”) sets out the terms and conditions that apply to the use of SURF Research Cloud (hereinafter: “the System”), made available by SURFsara, located at Science Park 140, 1098 XG Amsterdam (hereinafter: “SURFsara”). By accessing or otherwise using the System, User agrees to be fully bound by this Agreement. Please read this Agreement carefully before using the System. If you do not agree to be bound by all of these terms and conditions, please do not access or use the System.

Article 1. Usage of the System
-------------------------------

1. SURFsara hereby grants to User a limited license to use the functionalities made available to User through the System. This license is non-exclusive and non-transferable. No rights are granted to User hereunder other than as expressly set forth in this Agreement.
2. The System, any parts or specific functionalities thereof may only be accessible after login. User must keep its username, password and other access credentials confidential and must make use of adequate security tools against unauthorized use of the System made available by SURFsara.
3. SURFsara may assume that all actions undertaken from User’s account after logging in with its username and password are authorized and supervised by User. This means User is solely liable for the loss of usernames, passwords or any other access credentials (for example; SSH keys) and account numbers, and for any misuse by third parties resulting thereof.
4. In case personal data is processed by User on the System, a separate DPA needs to be agreed on between Institute/User and SURFsara.
5. PLEASE NOTE, the components of System in production are suitable for processing of personal data that falls in risk level ‘Medium’. The security measures on the System components in production are attuned to this risk level. In case a User intends to process sensitive data (such as special categories of personal data) on components of the System, the Institute and/or User himself is required and responsible for taking additional measures to adequately secure the data.


Article 2. Acceptable use
-------------------------------

1. User is not permitted to use the System for other purposes than the ones the project was granted for. Moreover, User is not permitted to use the System for any purpose that violates Dutch laws or other applicable laws and regulations.
2. User is not permitted to exceed the allocated computer time and/or storage limits. User is responsible for the consequences of exceeding the allocated computer time and/or storage limits .
3. User is not permitted to attempt to try to access or use parts of the System, programs and/or files that do not belong to the User or to which the User has not been granted access.
4. User is not permitted to license, sub-license, rent, lease, transfer, time share or otherwise make the System available for access by third parties in whole or in part.
5. Upon encountering any kind of errors in the System, software, compilers, data communication, and system disruptions, User agrees to report these without undue delay to SURFsara.
6. Within thirty (30) days of a request from SURFsara, User will fully document and certify that User’s use of the software and System at the time of the request is in conformity with the terms of this Agreement, and User agrees to permit SURFsara to verify the accuracy of this certification. Any non-conformities and the costs to solve these will be borne by User.


Article 3. Intellectual property
---------------------------------

1. All copyrights, trademarks and all other intellectual property rights in and to the software made available by SURFsara and the System are and shall remain the sole and exclusive property of SURFsara (and/or its affiliates).

Article 4. Availability and maintenance
----------------------------------------

1. To the extent reasonable within its power, SURFsara grants the User shared access to the “the System”.
2. SURFsara reserves the right to manage all System usage in order to assure full optimal usage of the System. SURFsara will limit as much as possible the time of the System’s unavailability due to maintenance or any unforeseen reason. However, maintenance can take place at any time, even if this may negatively impact the availability of the System. Maintenance is announced in advance whenever possible.
3. Support on the Systems is available conform the description that can be found on the website under “Helpdesk SURFsara services”.
4. All processor hours User lost as a result of failure or defective functioning of the System will be refunded to User.
5. User agrees not to request any indemnity or compensation from SURFsara and the suppliers of the various equipment and software for any damage suffered as a result of imperfections of the System.
6. User will take the necessary precautions to avoid unnecessary loss of processor hours.

Article 5. Privacy
-------------------

1. SURFsara respects the privacy of User. (Personal) data provided by User will be handled with due care and in line with the General Data Protection Regulation and other applicable privacy laws and regulations.
2. More information regarding the processing of personal data can be found in the privacy statement available on the website of SURFsara.

Article 6. Liability
---------------------

1. The liability limitations referred to in this Agreement shall not apply in cases of intentional misconduct or deliberate recklessness on the part of SURFsara, or for any other liability that may not otherwise be lawfully excluded or limited.
2. Notwithstanding the first paragraph of this article, the total liability of SURFsara for attributable direct damages shall be limited to the amount of EUR 50.000 (fifty thousand euros).
3. In no event shall SURFsara be liable for indirect damages, consequential damages, lost profits, missed savings or damages through business interruption, loss of (business) data, or any other pecuniary loss in connection with any claim, damage or other proceeding arising under this Agreement.
4. Damages may only be claimed if reported in writing to SURFsara within two (2) weeks after the damage occurred.
5. In case of force majeure, SURFsara is never required to compensate for damages suffered by User. Force majeure will be deemed to include, among other things, communications and/or power failure, (distributed) denial of service and other network attacks, riots, insurrections, labor disputes, actions of government, restrictions on import and/or export and/or any inability to perform which is caused by SURFsara’s suppliers. In case of force majeure SURFsara will use its best efforts to find a suitable remedy or alternative source to overcome said force majeure.

Article 7. Changes to Agreement
--------------------------------

1. SURFsara may change or add additional terms and conditions to this Agreement as well as change any prices at any time.
2. SURFsara shall announce changes or additions to this document in the user information.
3. Use of the System after the publishment of aforementioned changes shall constitute User’s acceptance of the changed or added-to terms and conditions.

Article 8. Termination of Agreement
------------------------------------

1. This Agreement is automatically terminated on the closing date assigned to the project.
2. Upon termination of this Agreement, User will secure on local (not SURFsara) storage all of his/her and his collaborators’ files remaining in the System.
3. Within a maximum period of six (6) months after the termination of this Agreement SURFsara will proceed to remove all usernames falling under this Agreement as well as the remaining files. If only a part of the agreement (access to specific systems) is terminated only these related usernames and data will be removed. SURFsara will not be liable for the loss of this data.

Article 9. Disclaimer of Warranties
------------------------------------

SURFsara disclaims responsibility for any harm resulting from your use of the System. SURFsara disclaims to the fullest extent permitted, all guarantees and express, implied and statutory warranties, including without limitation the warranties of merchantability, fitness for a particular purpose and non-infringement of proprietary rights, and any warranties regarding the availability, security, reliability, timeliness and performance of the System. You are solely responsible for any damages to your hardware devices or loss of data that result from the use of the System. 

Article 10. Miscellaneous provisions
-------------------------------------

1. At all times User (the Workspace Owner), must be able to prove to SURFsara its connection to a scientific institution or contracted party with access to or systems.
2. If any provision in this Agreement proves to be null and void, or otherwise unenforceable, this shall not affect the applicability of this Agreement as a whole. In such cases, SURFsara will adopt one or more new provisions that implement the intention of the original Agreement as much as possible.
3. This Agreement and all acts and transactions pursuant hereto and the rights and obligations of the parties hereto shall be governed, construed and interpreted in accordance with the laws of The Netherlands.
4. If there is any dispute about any parts and/or implementation of this Agreement, the Court of Amsterdam has exclusive jurisdiction.
