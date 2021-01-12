# Annex 1: Technical and Organizational Data Security Measures

Last updated: 01/08/2021

The data security measures defined by the Processor in this Annex have been agreed as binding.

## 1. Confidentiality (Art. 32(1)(b) GDPR)

### 1.1. Entry control

Data processing by the Processor shall be performed in a secure computer centre. The computer centre is certified
according to ISO 27001 concerning its information security management system. Access to the computer centre is
secured by state-of-the-art control systems. This includes the following security measures and infrastructure:

- Subdivision of the facility into individual security areas;
- Physical access protection, for example through steel doors, windowless rooms or secured windows;
- Protection of security areas through an electronic access control system;
- Monitoring of the facility by security services and logging access to the facility;
- Video surveillance of all security-relevant security areas, such as entrances, emergency exits and server rooms;
- Central assignment and revocation of access authorisations;
- Identification of all visitors by means of identity card;
- Obligatory identification within the security areas for all employees and visitors;
- Visitors must be accompanied by employees at all times.

### 1.2. Access control

The Processor is required to prevent the intrusion by unauthorised persons into systems and applications used for
the processing of personal data. The Processor ensures this by granting access to the data processing systems of
the IaaS provider solely to explicitly authorised administrators. Login takes place exclusively via multi-factor authentication based on the login information stored in the respective personal user account. In addition, the Pro-
cessor employs a differentiated rights system based on security groups and access control lists. It is only possible
to log in via connections that are encrypted using state-of-the-art technology.
Individual services and components are divided into several network segments to further secure access. Isolation
is provided by means of a hardware-based firewall systems and Virtual Private Clouds (VPC). Every access to systems and applications is documented, monitored and logged centrally.
The internal office network is protected against unauthorised access from outside by a hardware-based firewall.
Access to computers in the Processor's offices is controlled via user accounts. The internal office network can only
be accessed from outside the premises via an encrypted VPN connection (Virtual Private Network).
The Controller can only access their OpenProject instance via an encrypted connection (SSL/HTTPS).

### 1.3. Access controls

The Processor is required to prevent unauthorised activities within the data processing systems. Accordingly, only
the respective Controller and a small group of individually-named administrators have access to the data. Technical
measures shall ensure that a Controller cannot view, modify or erase data of other controllers. Within an Open-
Project instance, access is controlled via a comprehensive role-based access control and authorisation concept.
Within an OpenProject instance, rights are allocated by the Controller by assigning appropriate roles and rights. In
addition, the Controller has the option of adapting the preconfigured roles and rights for their organisation to their
needs via an administrative interface.
Access to the Controller's data by the Processor’s customer service representatives is limited to master data and
billing data necessary for the performance of their customer service functions and invoicing hosting services. Customer service representatives do not have access to customer data within an OpenProject instance.
Administrators are only allowed access to customer data if there is a fault that cannot be resolved by the Controller
and/or the Processor's customer service alone.

### 1.4. Separation control

All data records that are collected, processed or used by the Processor's systems and applications are explicitly
and clearly assigned to the respective Processor and technically separated from other data. The Processor's data
processing systems are specially designed for data processing that is limited to a specific purpose and specific
client. Access to the data of another client is thus technically impossible.

### 1.5. Pseudonymisation (Art. 32(1)(a) in conjunction with Art. 25(1) GDPR)

Pseudonymisation is intended to ensure that the identification of a data subject affected by data processing is not
possible or is made considerably more difficult.
Data concerning deleted users in OpenProject are anonymised so that it is no longer possible to associate such
data with the respective persons.

## 2. Integrity (Art. 32(1)(b) GDPR)

### 2.1. Transfer control

Control of the transfer of the Controller’s data is ensured by various technical and organisational security
measures. As part of these measures, the Processor never stores the Controller's data outside the computer centre. Employees of the computer centre operator have no physical or technical access to the Controller’s data such
that they can neither view, erase or modify such data. Data backups are only stored solely in encrypted form. The
Controller's data are not transported on physical data carriers. For the purpose of invoicing for services, billing data
is transferred to the Processor's accounting systems via an encrypted connection.

### 2.2. Input control

The Processor must guarantee the transparency and/or documentation of data processing. For this purpose, all
entries made into the systems and applications are logged by the Processor. The logs are archived and erased once
the purpose has been achieved or on the basis of legal requirements. The OpenProject application supports the
entry and modification of its own data exclusively via user interfaces and interfaces provided for this purpose in
accordance with a detailed role-based access control and authorisation concept. For many objects, the Controller
may also view the change history for data via the web interface (e.g. work packages, wiki pages, SCM repositories). 

## 3. Integrity (Article 32(1)(b) GDPR)

### 3.1. Availability control

The Processor must protect personal data against accidental destruction or loss. For this purpose, the architecture
of the Processor's data processing systems, including network infrastructure, the power supply and the connection
to the Internet must be designed redundantly.
A comprehensive backup and recovery concept must be in place to prevent data loss. The Controller's data is
continuously backed-up in a separate availability zone via a replication mechanism. In addition, complete backups
of all systems and data are made on a daily basis.
The systems and applications are continuously monitored with regard to availability, functionality, safety and utilisation. A written emergency plan is in place to restore the backups in the event of loss or destruction.

### 3.2. Rapid recoverability (Art. 32(1)(c) GDPR)

Measures must be taken to ensure that data can be recovered quickly in the event of data loss.
A combination of redundant systems and backup solutions is used to protect against the loss of the Controller’s
data. All data are backed up at least once a day. In case of data loss, this data can be recovered from the existing
backups. Data are stored in independent availability zones.

## 2. Availability and resilience (Art. 32(1)(b GDPR)

Resilience means the ability to resist attacks or to quickly bring systems back into working order after an attack.
The technical systems of the OpenProject platform are able to cope with expected disruptive events without their
functionality being significantly impaired. IT systems are continuously hardened to protect against known attacks
such as denial-of-service attacks.
In addition, each essential component is designed redundantly so that in the event of a fault, a switch to a defect-free component takes place automatically. Additional capacities can also be flexibly exchanged or expanded.
The OpenProject platform has modern, multitier architecture. As part of this architecture, access to the aspects
via network disconnections is technically so limited that, for example, the database management system cannot
be accessed from the Internet but rather only the load balancers.
Emergency plans exist which, in the event of a fault, provide precise instructions for restoring the desired condition. These emergency plans, and the protection concepts, are continuously reviewed and the relevant employees
receive regular training in connection with their deployment.

## 5. Data protection management

### 5.1. Contact details of the Processor (s) or the Processor’s representative (s)

Mr. David Heimburger (Data Protection Officer)

Friedensallee 114

22763 Hamburg

Email: [dh@davidheimburger.de](mailto:dh@davidheimburger.de)

GPG Key: [BC5D D292 8DD3 3B95 B6F7 0272 FE3F 95A3 135C 46A1](https://keys.openpgp.org/vks/v1/by-fingerprint/BC5DD2928DD33B95B6F70272FE3F95A3135C46A1)

### 5.2. Process for regular testing, assessment and evaluation (Art. 32(1)(d); Art. 25(1) GDPR)

A process for regularly testing, assessing and evaluating the effectiveness of technical and organisational measures for ensuring the security of the processing must be implemented.
This measure is to be implemented with the aid of a data protection management system. The effectiveness of the technical and organisational measures implemented is to be tested and optimised within the scope of a continuous improvement process. Regular audits are to be conducted by an external accredited expert as part of these efforts.

### 5.3. Incident response management; reporting channel

Measures must be in place to ensure that the Processor informs the Controller without undue delay in the event of a personal data breach or the suspicion of a personal data breach.
All contractual partners are contractually obliged to report data protection incidents within the legal deadlines.
Internal processes ensure that the Data Protection Officer is involved in case of data protection incidents.

### 5.4. Data protection by default (Art. 25(2) GDPR)

Appropriate technical and organisational measures must be implemented for ensuring that, by default, only personal data that are necessary for each specific purpose of the processing are processed.
After expiration of the test phase, as well as after termination of the contractual relationship, customer data that
have been collected must be erased within three months. In addition, the customer can independently delete
individual users within its OpenProject installation. This results in the deletion of the following personal data:

- Name,
- Email address,
- Telephone number,
- User name,
- User profile picture (avatar image).

Data that has been created, such as comments on work packages, are assigned to an anonymous user after deletion.

### 5.5. Contractor control

The Processor processes data submitted to them in accordance with the applicable contract and, in doing so, ensures compliance with statutory provisions and requirements defined by contract within the scope of the instructions provided by the Controller. The OpenProject platform has an administration interface through which the
Controller can manage their customer account. The Controller specifies their access data within their user account
during the initial account creation process. Only persons who have such access data can enter, change or delete
customer data within the scope of their assigned authorisations. The written form requirement applies to all other
tasks that the Controller cannot perform independently via the administration interface.