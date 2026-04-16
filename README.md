# Cloud IAM Help Desk Lab (Microsoft Entra ID)

## Overview
## 🔐 Cloud IAM Help Desk Lab (Microsoft Entra ID)

Simulated real-world IT support and Identity & Access Management (IAM) tasks using Microsoft Entra ID. This lab demonstrates user lifecycle management, password resets, account deactivation (offboarding), and group-based access control in a cloud environment.

## Technologies Used
- Microsoft Entra ID
- Microsoft Azure Portal

## Objectives
- Manage user identities in a cloud environment
- Simulate help desk support tasks
- Demonstrate onboarding and offboarding workflows
- Use group-based access control

## Help Desk Ticket Simulations

### Ticket 1: Password Reset Request
### 📸 Screenshots

**Step 1: User account overview**  
![Step 1](./images/ticket-1/step1.png)

**Step 2: Initiating password reset**  
![Step 2](./images/ticket-1/step2.png)

**Step 3: Temporary password generated**  
![Step 3](./images/ticket-1/step3.png)

**Issue:** User was unable to log in due to a forgotten password.  
**Resolution:** Reset the user password in Microsoft Entra ID and required password change at next login.  
**Result:** User regained access successfully.

### Ticket 2: Account Deactivation (Offboarding)

#### 📸 Screenshots

**Step 1: Locate user in Microsoft Entra ID**  
![Step 1](./images/ticket-1/ticket-2/2step1.png)

**Step 2: Review user account details**  
![Step 2](./images/ticket-1/ticket-2/2step2.png)

**Step 3: Verify account is currently enabled**  
![Step 3](./images/ticket-1/ticket-2/2step3.png)

**Step 4: Disable account by blocking sign-in**  
![Step 4](./images/ticket-1/ticket-2/2step4.png)

**Issue:** An employee left the company and account access needed to be removed.  

**Resolution:** Disabled the user account by blocking sign-in in Microsoft Entra ID and revoking access.  

**Result:** Account access was successfully removed, preventing further login.


### Ticket 3: Access Request (Group-Based Access)

#### 📸 Screenshots

**Step 1: Navigate to Groups in Microsoft Entra ID**  
![Step 1](./images/ticket-1/ticket-3/3step1.png)

**Step 2: Select the appropriate group (IT Team)**  
![Step 2](./images/ticket-1/ticket-3/3step2.png)

**Step 3: Review current group members**  
![Step 3](./images/ticket-1/ticket-3/3step3.png)

**Step 4: Add user to group**  
![Step 4](./images/ticket-1/ticket-3/3step4.png)

**Step 5: Confirm user successfully added to group**  
![Step 5](./images/ticket-1/ticket-3/3step5.png)

**Issue:** User required access to IT resources to perform job responsibilities.  

**Resolution:** Added the user to the IT Team security group in Microsoft Entra ID to grant appropriate access permissions.  

**Result:** User successfully gained access to required systems through group-based access control.

### Ticket 4: User Onboarding (Account Creation + Group Assignment)

#### 📸 Screenshots

**Step 1: Navigate to Users in Microsoft Entra ID**  
![Step 1](./images/ticket-1/ticket-4/4step1.png)

**Step 2: Click "New user" to begin account creation**  
![Step 2](./images/ticket-1/ticket-4/4step2.png)

**Step 3: Enter basic user details (name, username, password)**  
![Step 3](./images/ticket-1/ticket-4/4step3.png)

**Step 4: Configure user properties (job title, department, company)**  
![Step 4](./images/ticket-1/ticket-4/4step4.png)

**Step 5: Review and create the new user account**  
![Step 5](./images/ticket-1/ticket-4/4step5.png)

**Step 6: Confirm user appears in directory**  
![Step 6](./images/ticket-1/ticket-4/4step6.png)

**Step 7: Navigate to Groups**  
![Step 7](./images/ticket-1/ticket-4/4step7.png)

**Step 8: Select appropriate department group**  
![Step 8](./images/ticket-1/ticket-4/4step8.png)

**Step 9: Add new user to group**  
![Step 9](./images/ticket-1/ticket-4/4step9.png)

**Step 10: Confirm user successfully added to group**  
![Step 10](./images/ticket-1/ticket-4/4step10.png)

**Issue:** A new employee required an account and access to company resources.  

**Resolution:** Created a new user account in Microsoft Entra ID and assigned the user to the appropriate department security group.  

**Result:** User account was successfully created and granted proper access based on role and group membership.

## Key Concepts Demonstrated
- Identity Management
- Group-Based Access Control
- User Onboarding
- User Offboarding
- Password Reset Support

## Screenshots
Screenshots will be added to the images folder for each ticket scenario.

## What I Learned
- How to manage users in Microsoft Entra ID
- How to use groups for access control
- How to support common help desk identity tasks
- How IAM supports daily IT operations
