# AI-Powered Recruitment System – Salesforce Flow Automation

## Project Overview

This project demonstrates the implementation of automation in Salesforce for an AI-powered Recruitment Management System using Salesforce Flows. The solution automates candidate notifications, approval processes, follow-ups, and provides a guided application creation wizard without using Apex code.

---

# Features

* Automated notification for high-priority candidate applications
* Automatic approval submission for high salary offers
* Daily follow-up reminders for pending candidate applications
* Screen Flow for easy candidate application creation
* Fully built using Salesforce Flow Builder (No Apex)

---

# Technologies Used

* Salesforce Flow Builder
* Record-Triggered Flows
* Scheduled-Triggered Flows
* Screen Flow
* Email Alerts
* Approval Processes
* Salesforce Objects

---

# Object Used

**Candidate_Application__c**

Key Fields:

* Candidate
* Job Opening
* Application Date
* Offer_Amount__c
* Experience_Level__c
* AI_Candidate_Score__c
* Approval_Status__c

---

# Activity 1: High Priority Candidate Notification

## Objective

Automatically notify the recruiter when AI identifies a candidate application as high priority.

### Trigger

Record-Triggered Flow

### Object

Candidate_Application__c

### Condition

AI_Candidate_Score__c ≥ 85

### Actions Performed

* Triggered when a record is created or updated.
* Checks whether the AI Candidate Score is greater than or equal to 85.
* Sends the **High Priority Candidate Application Email Alert** to the application owner.
* Flow is activated for automatic execution.

---

# Activity 2: High Salary Offer Approval

## Objective

Automatically submit high-value candidate offers for approval.

### Trigger

Record-Triggered Flow

### Object

Candidate_Application__c

### Condition

Offer_Amount__c > 1,000,000

### Actions Performed

* Triggered when a record is created or updated.
* Evaluates the Offer Amount.
* Automatically submits the record to the **High Salary Candidate Offer Approval** process.
* Flow is activated.

---

# Activity 3: Pending Candidate Follow-Up

## Objective

Notify recruiters about candidate applications that have remained pending for more than three days.

### Trigger

Scheduled-Triggered Flow

### Schedule

* Frequency: Daily
* Example Time: 9:00 AM

### Conditions

* Approval_Status__c = Pending
* LastModifiedDate older than 3 days

### Actions Performed

* Runs once every day.
* Finds pending applications that have not been updated for over three days.
* Sends the **Candidate Application Approval Status Email Alert** to the recruiter.
* Flow is activated.

---

# Activity 4: Candidate Application Creation Wizard

## Objective

Provide recruiters with a guided interface for creating candidate applications.

### Flow Type

Screen Flow

### Screens

#### Candidate Details

* Candidate
* Job Opening
* Application Date

#### Offer Details

* Offer Amount
* Experience Level
* AI Candidate Score

### Automation

* Calculates the Final Offer Amount using Assignment/Formula.
* Creates a new Candidate_Application__c record.
* Displays a confirmation screen indicating successful creation.

---

# Flow Summary

| Activity   | Flow Type                | Purpose                                       |
| ---------- | ------------------------ | --------------------------------------------- |
| Activity 1 | Record-Triggered Flow    | Notify recruiter for high-priority candidates |
| Activity 2 | Record-Triggered Flow    | Submit high salary offers for approval        |
| Activity 3 | Scheduled-Triggered Flow | Send reminders for pending approvals          |
| Activity 4 | Screen Flow              | Guided candidate application creation         |

---

# Learning Outcomes

* Built Record-Triggered Flows
* Implemented Scheduled-Triggered Flows
* Designed interactive Screen Flows
* Configured Email Alerts
* Automated Approval Processes
* Applied conditional automation using Flow Builder
* Improved recruitment workflow efficiency without Apex development

---

# Conclusion

This project demonstrates how Salesforce Flow Builder can automate the recruitment lifecycle using declarative tools. The implementation enhances recruiter productivity by automating notifications, approval workflows, scheduled reminders, and candidate application creation, resulting in a streamlined and efficient recruitment process.

