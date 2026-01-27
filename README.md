# HR Support Group Membership & Validation

## Overview
This repository demonstrates how HR support users are assigned to real-world assignment groups within ServiceNow. The focus is on establishing group membership so users can participate in HR case routing, workload distribution, and service delivery operations.

The implementation reflects a realistic HR support model where analysts belong to multiple functional groups based on the types of cases they handle.

## Use Case
As HR support operations scale, cases must be routed to the appropriate teams based on subject matter and service type. Assignment groups allow organizations to categorize work, distribute cases efficiently, and ensure that only qualified HR analysts can access and resolve sensitive employee issues.

In this scenario, HR support analysts are added to both a payroll-focused group and a Tier 1 HR support group. This enables them to receive and work payroll-related inquiries while also participating in general HR case handling.

This project simulates the administrative task of assigning HR support users to operational groups in preparation for active case management.

## Features
- Assignment of HR support users to multiple HR groups
- Support for payroll and Tier 1 HR case routing
- Validation of group membership at both the group and user level
- Confirmation of readiness for HR case assignment

## Technologies Used
- ServiceNow Platform
- Users and Groups
- Group Membership Management
- HR Service Management

## Implementation Walkthrough

### Objective
Assign HR support users to appropriate HR assignment groups to enable accurate case routing and participation in HR service operations.

### Step 1: Locate HR Assignment Groups
HR assignment groups were accessed through the Groups module. This allows review and management of group records used for HR case assignment.

### Step 2: Add HR Support Users to the HR Payroll Group
The HR Payroll group was opened and updated to include the HR support users. Group membership was modified to ensure both users could receive and work payroll-related HR cases.

This group supports HR services related to compensation and payroll inquiries.

### Step 3: Add HR Support Users to the HR Tier 1 Group
The HR Tier 1 group was then updated to include the same HR support users. This ensures they can participate in general HR case intake and Tier 1 support activities.

Assigning users to multiple groups reflects a realistic HR support structure where analysts handle a range of case types.

### Step 4: Validate Group Membership
Group membership was validated by:
- Reviewing the member list on each HR group
- Confirming both users appear in the HR Payroll and HR Tier 1 groups
- Verifying group memberships from the user record level
<img width="1907" height="878" alt="Screen Shot 2026-01-27 at 6 48 42 PM" src="https://github.com/user-attachments/assets/ce9ce0f6-35e0-4a9e-bd12-ed1c9d6b7802" />
<img width="1907" height="878" alt="Screen Shot 2026-01-27 at 6 50 45 PM" src="https://github.com/user-attachments/assets/7fc8a0ca-1f2f-4051-b8ac-89e66566e5b6" />

This validation ensures accurate routing and visibility when HR cases are created.

## Sample Group Memberships

**HR Payroll Group**
- Taylor Johnson
- Alex Martinez
<img width="1901" height="799" alt="Screen Shot 2026-01-27 at 6 37 33 PM" src="https://github.com/user-attachments/assets/37cf371b-c7db-4414-b2d0-283793e1695d" />


**HR Tier 1 Group**
- Taylor Johnson
- Alex Martinez
<img width="1901" height="827" alt="Screen Shot 2026-01-27 at 6 41 07 PM" src="https://github.com/user-attachments/assets/08a00354-e56c-48c0-9d3d-245547ac2683" />


## Lessons Learned
- Assignment groups play a critical role in HR case routing and workload management
- Users can belong to multiple HR groups to support different service areas
- Validating group membership from both group and user perspectives helps prevent routing issues
- Proper group configuration is essential before enabling case creation and assignment
