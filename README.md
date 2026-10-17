# Microsoft Entra ID – Identity & Access Management Lab

## Project Overview

This hands-on lab demonstrates foundational Identity and Access Management (IAM) tasks in Microsoft Entra ID. The project focuses on user lifecycle administration, group-based access, enterprise application assignment, Conditional Access, MFA configuration, sign-in monitoring, and basic identity troubleshooting.

> **Lab note:** Maya Johnson and the Finance Employees group are fictional test identities created only for this lab. Screenshots were sanitized/redacted for privacy.

## Objectives

- Create and manage test user accounts in Microsoft Entra ID
- Create a security group and manage group membership
- Assign group-based access to an enterprise application
- Configure a Conditional Access policy requiring MFA
- Keep the Conditional Access policy in **Report-only** mode for safe testing
- Review sign-in activity and filter logs by user/date
- Troubleshoot a failed user sign-in
- Reset a test-user password and validate successful access in a private browser session

## Environment & Tools

- Microsoft Entra ID
- Microsoft Entra admin center
- Microsoft 365 / My Account
- Conditional Access
- Enterprise Applications
- Sign-in Logs
- Private/InPrivate browser session
 ## Lab Evidence

### 1. Test Users Created
Created and managed test users in Microsoft Entra ID, including Maya Johnson.

![Test Users Created](images/01_Test_Users_Created.jpg)

### 2. Security Group Created
Created a security group named **Finance Employees**.

![Security Group Created](images/02_Security_Group_Created.jpg)

### 3. Group Membership
Added Maya Johnson to the **Finance Employees** security group.

![Group Membership](images/03_Group_Membership.jpg)

### 4. Enterprise Application Created
Created the **Finance Portal - Lab** enterprise application.

![Enterprise Application Created](images/04_Enterprise_Application_Created.jpg)

### 5. App Access Assignment
Assigned the **Finance Employees** group to the Finance Portal application.

![App Access Assignment](images/05_App_Access_Assignment.jpg)

### 6. Conditional Access Policy
Created a Conditional Access policy requiring MFA and kept it in **Report-only** mode for safe testing.

![Conditional Access Policy](images/06_Conditional_Access_Policy.jpg)

### 7. Sign-In Logs
Reviewed Maya Johnson's sign-in activity and filtered the sign-in logs to investigate authentication attempts.

![Sign-In Logs](images/07_Sign_In_Logs_All_Events.jpg)

### 8. Successful Sign-In Details
Reviewed the successful authentication event after resolving the sign-in issue.

![Successful Sign-In Details](images/08_Successful_Sign_In_Details.jpg)

### 9. User Sign-In Verification
Verified the test user's account access and security information.

![User Sign-In Verification](images/09_User_Sign_In_Verification.jpg)

### 10. Conditional Access Policy Overview
Reviewed the Conditional Access policy configuration, including the Report-only state, targeted group, resource, and MFA requirement.

![Conditional Access Policy Overview](images/10_Conditional_Access_Policy_Overview.jpg)

### 11. Policy Assignment
Verified that the Conditional Access policy was assigned to the **Finance Employees** group.

![Policy Assignment](images/11_Policy_Assignment_Users_and_Groups.jpg)

### 12. Grant Access – MFA Requirement
Verified the access control was configured to grant access while requiring multifactor authentication.

![Grant Access MFA Requirement](images/12_Grant_Access_MFA_Requirement.jpg)

### 13. Failed Sign-In Investigation
Investigated a failed sign-in event using Microsoft Entra sign-in logs.

![Failed Sign-In Investigation](images/13_Failed_Sign_In_Investigation.png)

### 14. Successful Sign-In Verification
Reset the test user's password, signed in again, and verified the authentication succeeded.

![Successful Sign-In Verification](images/14_Successful_Sign_In_Verification.png)

### 15. Private Browser User Verification
Used a private browser session to sign in as the test user and confirm access after the password reset.

![Private Browser User Verification](images/15_Private_Browser_User_Verification.png)
