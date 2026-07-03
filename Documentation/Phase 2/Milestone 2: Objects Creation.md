# Milestone 2: Objects Creation

## Overview

This milestone focuses on creating the core custom objects required for the Recruitment Management System in Salesforce. Custom objects are used to store business-specific data that is not available in Salesforce's standard objects.

Two custom objects are created to represent the recruitment process:

* **Job Opening**
* **Candidate Application**

These objects form the foundation of the recruitment data model and enable efficient management of job postings and candidate applications.

---

# Objective

The objectives of this milestone are to:

* Create custom objects using Salesforce Object Manager.
* Design the basic recruitment data structure.
* Enable reporting and search capabilities.
* Maintain field history for auditing purposes.
* Prepare the system for future relationships and automation.

---

# Custom Objects Created

## 1. Job Opening

The **Job Opening** object stores information about available job positions within the organization.

### Object Configuration

| Property            | Value        |
| ------------------- | ------------ |
| Object Label        | Job Opening  |
| Plural Label        | Job Openings |
| Record Name         | Job Title    |
| Data Type           | Text         |
| Allow Reports       | Enabled      |
| Allow Search        | Enabled      |
| Track Field History | Enabled      |

### Purpose

The Job Opening object is used to:

* Maintain job vacancy details.
* Track available positions.
* Associate candidates with job openings.
* Generate recruitment reports.

---

## 2. Candidate Application

The **Candidate Application** object stores information about candidates applying for different job openings.

### Object Configuration

| Property            | Value                  |
| ------------------- | ---------------------- |
| Object Label        | Candidate Application  |
| Plural Label        | Candidate Applications |
| Record Name         | Application ID         |
| Data Type           | Auto Number            |
| Auto Number Format  | CA-{0000}              |
| Starting Number     | 1                      |
| Allow Reports       | Enabled                |
| Allow Search        | Enabled                |
| Track Field History | Enabled                |

### Purpose

The Candidate Application object is used to:

* Store candidate application details.
* Generate unique application IDs automatically.
* Track recruitment progress.
* Maintain application history.
* Support reporting and analytics.

---

# Implementation Steps

## Activity 1: Create Job Opening Object

1. Open **Setup** in Salesforce.
2. Navigate to **Object Manager**.
3. Click **Create → Custom Object**.
4. Configure the object:

   * Label: **Job Opening**
   * Plural Label: **Job Openings**
   * Record Name: **Job Title**
   * Data Type: **Text**
5. Enable:

   * Allow Reports
   * Allow Search
   * Track Field History
6. Click **Save & New**.

---

## Activity 2: Create Candidate Application Object

1. From **Object Manager**, click **Create → Custom Object**.
2. Configure the object:

   * Label: **Candidate Application**
   * Plural Label: **Candidate Applications**
   * Record Name: **Application ID**
   * Data Type: **Auto Number**
   * Display Format: **CA-{0000}**
   * Starting Number: **1**
3. Enable:

   * Allow Reports
   * Allow Search
   * Track Field History
4. Click **Save**.

---

# Expected Outcome

After completing this milestone:

* Job Opening custom object is successfully created.
* Candidate Application custom object is successfully created.
* Automatic Application IDs are generated.
* Both objects support reporting and searching.
* Field history tracking is enabled for auditing.
* The recruitment data model is established for future development.

---

# Skills Learned

* Salesforce Object Manager
* Custom Object Creation
* Record Name Configuration
* Auto Number Fields
* Field History Tracking
* Search Configuration
* Report Configuration
* Recruitment Data Modeling

---

# Business Benefits

* Centralized storage of recruitment information.
* Structured management of job openings and applications.
* Improved data consistency.
* Easy search and reporting capabilities.
* Better auditability through field history tracking.
* Strong foundation for workflows, relationships, and automation.

---

# Conclusion

Creating the **Job Opening** and **Candidate Application** custom objects is a crucial step in building the Recruitment Management System. These objects provide a structured and scalable data model that supports the complete recruitment lifecycle. They also prepare the Salesforce environment for future enhancements such as relationships, automation, security, reports, dashboards, and AI-powered recruitment features.
