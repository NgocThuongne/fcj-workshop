---
title: "Week 1 Worklog"
date: 2026-04-20
weight: 1
chapter: false
pre: " <b> 1.1. </b> "
---


### Week 1 Objectives:

* Attend the project kickoff event (AWS Kickoff).
* Connect and get acquainted with the First Cloud AI Journey (FCAJ) team, and study as well as comply with the rules and regulations at the internship unit.
* Research access management and control mechanisms using the AWS IAM service.
* Practice building a basic permission model using IAM Users, Groups, and Roles, and test the role-switching feature.

### Tasks to be carried out this week:
| Day | Task | Start Date | Completion Date | Reference Material |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ | --------------- | ----------------------------------------- |
| 2 | - Meet and connect with members in the FCAJ project <br> - Study the rules and operational regulations of the internship unit <br> - Attend the AWS Kickoff event to start the internship <br> - Research the overview of AWS cloud infrastructure and core service groups (Compute, Storage, Network, Database) | 20/04/2026 | 20/04/2026 |  |
| 3 | - Setup an AWS Free Tier account for practice <br> - Complete the introductory challenges to receive $100 AWS Credit support <br> - Configure Multi-Factor Authentication (MFA) to protect the root account <br> - Configure the AWS Budgets management tool | 21/04/2026 | 21/04/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 4 | - Study the mechanism and concepts of IAM Users and IAM Groups <br> - Initialize the Admin Group and the corresponding Admin User for system administration <br> - Assign the `AdministratorAccess` policy to the Admin Group <br> - Practice logging in and operating using the new Admin User account | 22/04/2026 | 22/04/2026 | <https://000002.awsstudygroup.com/> |
| 5 | - Study the role and real-world application of IAM Roles <br> - Create specialized permission roles (AdminRole, S3Role) <br> - Create an Operator User and assign the role assumption configuration policy | 23/04/2026 | 23/04/2026 | <https://000002.awsstudygroup.com/> |
| 6 | - Practice the Switch Role technique from Operator to Admin to handle tasks <br> - Check and verify access limits to S3 storage via S3Role permissions <br> - Practice setting permissions based on the principle of least privilege | 24/04/2026 | 24/04/2026 | <https://000002.awsstudygroup.com/> |


### Week 1 Achievements:

* **Workspace Integration:**
  * Fully attended the Kickoff opening ceremony and got acquainted with the First Cloud AI Journey (FCAJ) team.
  * Clearly understood and complied with the code of conduct, internal regulations, and internship procedures at the company.

* **Foundational Knowledge of AWS Infrastructure:**
  * Gained a general overview of AWS Cloud Computing and clearly distinguished the core service groups:
    * **Compute:** Mastered the functions of EC2, Lambda.
    * **Storage:** Understood S3.
    * **Networking:** Learned the basic operations of VPC, Route53, CloudFront.
    * **Database:** Got familiar with RDS, DynamoDB.
    * **Security & Identity:** Grasped the roles of IAM, KMS.

* **Account Administration & Cost Control:**
  * Successfully set up the AWS Free Tier practice environment.
  * Accumulated $100 in AWS Credits by completing the initial guidance challenges.
  * Enhanced information security by configuring Multi-Factor Authentication (MFA) for the Root account.
  * Proactively set up spending thresholds and automated alerts using the AWS Budgets service to prevent unexpected costs.

* **Mastering AWS IAM Identity Management Service:**
  * Distinctly differentiated the use cases of IAM Users (providing long-term credentials) and IAM Roles (granting short-term temporary access).
  * Successfully configured the Admin Group using the `AdministratorAccess` policy and assigned the corresponding users.
  * Designed and deployed specialized roles: `AdminRole` (comprehensive administration) and `S3Role` (exclusive access to S3 storage).
  * Built an authorization mechanism by creating an Operator User with an Assume Role policy.
  * Successfully tested the Switch Role workflow in practice, transitioning smoothly from a standard user to the Admin role.
  * Established safe operational habits by logging in and working via an IAM User instead of the Root account.

* **Applying Best IAM Security Practices:**
  * Fully implemented the Principle of Least Privilege, granting only the necessary permissions required for the job.
  * Encouraged using IAM Roles for temporary authorization to minimize the exposure of long-term Access Keys/Secret Keys.
  * Set a mandatory requirement to enable MFA for high-privilege accounts.
  * Utilized the AWS CloudTrail tool to track activity history and monitor access behavior.
  * Minimized the use of the Root account for daily operational tasks.
