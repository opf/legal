# Service Level Agreement OpenProject Enterprise Cloud

Last change to this document: 2020-12-09

This SLA amends the Service Agreement between [OpenProject](https://www.openproject.org/legal/imprint) and Customer. It specifies the service level in relation to the Services [OpenProject Enterprise Cloud](https://www.openproject.org/hosting/). We may update this SLA from time to time in our sole discretion.

## 1. Support

### 1.1 Support service level 

 OpenProject provides its services at different support levels defined as follows:

| Support service levels                   | Professional Support     | Premier Support          | Corporate Support        |
| ---------------------------------------- | ------------------------ | ------------------------ | ------------------------ |
| Service hours                            | Mon-Fri, 09:30-17:30 CET | Mon-Fri, 09:30-17:30 CET | Mon-Fri, 09:00-18:00 CET |
| Response time – critical incidents       | 8 h                      | 6 h                      | 2 h                      |
| Response time – major incidents          | best effort              | 12 h                     | 6 h                      |
| Response time – minor incidents          | best effort              | 48 h                     | 24 h                     |
| Scheduled standby and upgrade assistance | -                        | included                 | included                 |
| Priority development and escalation      | -                        | included                 | included                 |

### 1.2 Incident priorities

**Critical incidents** are incidents which prevent or significantly impact the use of OpenProject, e.g. through malfunctions, wrong results or response times, and which cannot be resolved with reasonable organizational tools (critical operating errors).

*Example:*

- Display of full screen error message when accessing the OpenProject landing page.

**Major incidents** are incidents which can be circumvented without major difficulties or which affect a part of OpenProject which do not impact the usage directly or significantly.

*Example:*

- The OpenProject application does not send any automatic email notifications.

**Minor incidents** are incidents affecting functionalities which are not frequently relevant for the users and which are of little importance so that the user does not need the functionality for an extended time.

*Example:*

- When accessing a certain work package query the error message „Internal Server Error“ is shown.
- Saving a cost report is not possible. 
- In the project overview page two widgets overlap but are still useable.

### 1.3 Support communication channel 

 OpenProject provides its support services with different communication channels as follows: 

| Support service levels     | Professional Support | Premier Support | Corporate Support |
| -------------------------- | -------------------- | --------------- | ----------------- |
| Ticket                     | -                    | included        | included          |
| Email                      | included             | included        | included          |
| Phone                      | -                    | included        | included          |
| Remote login/remote hands  |                      | included        | included          |
| Dedicated support engineer |                      |                 | included          |
| Named support contacts     | 1                    | 3               | 8                 |

## 2. Service availability

### 1.1 Availability 

OpenProject GmbH will make the Services available 99.9% of the time, excluding any *Excused Downtime*. In a given calendar month, we calculate *Service Availability* as follows:

**Service Availability = total minutes Services are available x 100 / (total minutes in the month – Excused Downtime)**

### 2.1 Excused downtime

**Excused Downtime** means the length of time the Services are unavailable due to:

1. Scheduled maintenance;
2. Emergency maintenance;
3. Beta services;
4. Force majeure events; and
5. the actions or omissions of you, your Authorized Users, or any third-party acting on your behalf or at your direction, including any unauthorized use of the Services, breach of the Agreement or Acceptable Use Policy, or any use or configuration of the Services that exceeds OpenProject's recommendations or advertised limits.

### 2.2 Schedule maintenance

**Scheduled Maintenance** includes any maintenance performed during the following windows or for which we provide reasonable notice or coordination with you in advance of the maintenance.

| **Data Center location** | **Maintenance window** |
| ------------------------ | ---------------------- |
| European Union           | 6:00 am - 08:00 am CET |

**Emergency Maintenance** means any maintenance performed outside the Scheduled Maintenance windows without advance notice where such maintenance is reasonably and urgently required to protect the integrity, availability, or security of any online systems.

### 2.2 SLA credits

You are entitled to a credit of 5% of the applicable monthly Fees for each full hour of downtime in excess of the Service Availability targets. (For example, you will receive a 5% credit for between 1 and 60 minutes of downtime in excess of the Service Availability targets, a 10% credit for between 61 and 120 minutes, etc.) In order to receive a credit, you must contact Support within 30 days of the event giving rise to the credit. Credits are based on our monitoring, shall not exceed 100% of the applicable monthly Fees, may not be carried over or aggregated, are forfeited at the expiration or termination of the Agreement, and will not be paid or provided as a refund.

## 3. Backup

### 3.1 Database

Automated Amazon Relational Database Service (RDS) backups are performed. Daily snapshots and transaction logs are retained for 30 days to allow for point-in-time data restoration within that time frame. Both snapshots and transaction logs are securely stored in S3.

OpenProject Enterprise Cloud does not support the use of backup data to roll back changes.

### 3.2 Attachments

Attachments are stored securely in S3 as well. The S3 storage is encrypted and replicated across multiple availability zones within the same region.
This offers an availability of 99.99%. On top of that files are versioned. That is even if deleted they may be restored if absolutely necessary.
The attachments and their versions are retained throughout the whole subscription period.

## 4. Software updates

OpenProject will update the software providing the Service to the highest released [version](https://docs.openproject.org/release-notes/)of the OpenProject application within x days after a release. OpenProject might also install yet unreleased patches to the software in case they improve the service. Every installed software version will be tested by OpenProject prior to the deployment. In case the update requires a downtime, OpenProject will inform the Customer of the scheduled downtime with a 3 days notice.

## 5. Acceptable use policy

You may not interfere with our business or our ability to provide services to other customers, nor take any action nor make any use of the Services that places excessive burdens on the network or systems used to provide such services. Specifically, you may not use the service for use cases other than project management, team collaboration, product management and product lifecycle management. If your use of the Services materially exceeds the use by similarly situated customers, we may offer to move you to a different plan or charge you for the additional use. If you refuse, we may place restrictions on your use of the Services. You may not perform any vulnerability or penetration testing of OpenProject’s network or systems without our prior written approval.
