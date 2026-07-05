# AI-Powered Recruitment System – Salesforce Email Alerts

## Project Overview

This project implements automated email alerts for an AI-powered Recruitment Management System using Salesforce Email Alerts. These alerts ensure that recruiters and hiring managers receive timely notifications during critical stages of the recruitment process, improving communication and workflow efficiency.

---

# Features

* High Priority Candidate Application Email Alert
* High Salary Candidate Offer Approval Email Alert
* Candidate Application Approval Status Email Alert
* Automated Recruiter Notifications
* Automated Hiring Manager Notifications
* Integration with Salesforce Email Templates

---

# Technologies Used

* Salesforce CRM
* Salesforce Email Alerts
* Classic Email Templates
* Salesforce Flow Automation
* Recruitment Management System

---

# Object Used

**Candidate_Application__c**

---

# Activity 1: High Priority Candidate Application Email Alert

## Objective

Automatically notify the recruiter when AI identifies a candidate application as high priority.

### Configuration

* **Email Alert Name:** High Priority Candidate Application Email Alert
* **Object:** Candidate Application
* **Email Template:** High Priority Candidate Application Notification
* **Recipient Type:** User
* **Recipient:** Candidate Application Owner

### Outcome

Whenever a candidate application is marked as high priority by AI, the assigned recruiter automatically receives an email notification for immediate action.

---

# Activity 2: High Salary Candidate Offer Approval Email Alert

## Objective

Notify the Hiring Manager when a candidate offer with a high salary is submitted for approval.

### Configuration

* **Email Alert Name:** High Salary Candidate Offer Approval Email Alert
* **Object:** Candidate Application
* **Email Template:** High Salary Candidate Offer Approval Notification
* **Recipient Type:** User
* **Recipient:** Manager

### Outcome

The Hiring Manager automatically receives an email requesting approval for high-value candidate offers.

---

# Activity 3: Candidate Application Approval Status Email Alert

## Objective

Notify the recruiter after the Hiring Manager approves or rejects a candidate offer.

### Configuration

* **Email Alert Name:** Candidate Application Approval Status Email Alert
* **Object:** Candidate Application
* **Email Template:** Candidate Application Approval Status Notification
* **Recipient Type:** User
* **Recipient:** Candidate Application Owner

### Outcome

The assigned recruiter automatically receives the approval outcome, allowing the recruitment process to continue without delay.

---

# Email Alert Summary

| Activity   | Email Alert                                       | Recipient                   | Purpose                                                          |
| ---------- | ------------------------------------------------- | --------------------------- | ---------------------------------------------------------------- |
| Activity 1 | High Priority Candidate Application Email Alert   | Candidate Application Owner | Notify recruiter about AI-identified high-priority candidates    |
| Activity 2 | High Salary Candidate Offer Approval Email Alert  | Manager                     | Notify Hiring Manager about high salary offers awaiting approval |
| Activity 3 | Candidate Application Approval Status Email Alert | Candidate Application Owner | Notify recruiter of approval or rejection decisions              |

---

# Business Benefits

* Automates recruitment communication
* Reduces manual notification efforts
* Improves recruiter and hiring manager collaboration
* Ensures timely approval actions
* Enhances recruitment workflow efficiency
* Supports faster hiring decisions

---

# Learning Outcomes

* Created Salesforce Email Alerts
* Linked Email Alerts with Classic Email Templates
* Configured recipients based on business roles
* Automated recruitment notifications
* Integrated Email Alerts into Salesforce recruitment workflows

---

# Conclusion

This project demonstrates the implementation of Salesforce Email Alerts to automate communication throughout the recruitment lifecycle. By notifying recruiters and hiring managers at key stages such as high-priority candidate identification, salary approval requests, and approval outcomes, the recruitment process becomes faster, more efficient, and better organized.
