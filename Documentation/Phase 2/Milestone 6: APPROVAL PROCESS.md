# AI-Powered Recruitment System – Salesforce Approval Process

## Project Overview

This project implements an automated approval process for high-value candidate offers in Salesforce. The solution ensures that offers exceeding the organization's salary threshold are reviewed and approved by the Hiring Manager before proceeding. The project also includes email notifications, approval workflows, and validation to maintain compliance with recruitment policies.

---

# Features

* High Salary Offer Approval Process
* Automated Approval Routing
* Email Notifications to Hiring Managers
* Approval and Rejection Actions
* Recruitment Workflow Automation
* Salesforce Declarative Development (No Apex)

---

# Technologies Used

* Salesforce CRM
* Approval Process
* Classic Email Templates
* Email Alerts
* Process Automation
* Salesforce Setup

---

# Prerequisites

Before implementing the approval process, the following configurations were completed:

* Created User Profiles

  * Recruiter
  * Hiring Manager
  * System Administrator
* Configured Role Hierarchy
* Created Users and Assigned Roles

---

# Activity 1: High Salary Candidate Offer Approval Process

## Objective

Automatically route candidate offers with high salary amounts to the Hiring Manager for approval before the hiring process can continue.

### Components Implemented

### 1. Classic Email Template

Created an email template to notify the Hiring Manager whenever a high salary offer is submitted for approval.

**Purpose**

* Notify approvers instantly
* Provide candidate offer details
* Allow quick review of the request

---

### 2. Approval Process

Configured an Approval Process for the **Candidate_Application__c** object.

### Approval Criteria

* Candidate offer exceeds the organization's defined salary threshold.
* Record is automatically submitted for approval.

### Approval Workflow

1. Recruiter submits a candidate offer.
2. Salesforce checks the approval criteria.
3. High salary offers are routed to the Hiring Manager.
4. The Hiring Manager reviews the application.
5. The request is either Approved or Rejected.
6. Salesforce updates the approval status and sends notifications.

---

### Approval Actions

#### Initial Submission

* Record submitted for approval.
* Notification email sent to the Hiring Manager.

#### Approval Actions

* Candidate offer marked as Approved.
* Recruitment process continues.

#### Rejection Actions

* Candidate offer marked as Rejected.
* Recruiter is notified to review or modify the offer.

---

# Workflow Summary

| Step                         | Description                             |
| ---------------------------- | --------------------------------------- |
| User submits candidate offer | Recruiter submits an offer              |
| Approval criteria evaluated  | Salary threshold is checked             |
| Approval request created     | Sent to Hiring Manager                  |
| Email notification           | Hiring Manager receives notification    |
| Review                       | Hiring Manager approves or rejects      |
| Final status updated         | Salesforce updates the approval outcome |

---

# Business Benefits

* Prevents unauthorized high salary approvals
* Standardizes recruitment approval workflow
* Improves transparency and accountability
* Reduces manual approval effort
* Ensures compliance with organizational hiring policies

---

# Learning Outcomes

* Created Classic Email Templates
* Configured Salesforce Approval Processes
* Implemented automated approval routing
* Managed approval and rejection actions
* Integrated email notifications into business workflows
* Built recruitment automation without Apex

---

# Conclusion

This project demonstrates how Salesforce Approval Processes can automate high-value recruitment approvals. By combining email notifications and declarative automation, the recruitment workflow becomes more secure, efficient, and compliant with company hiring policies, while eliminating the need for custom Apex development.
