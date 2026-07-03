# Salesforce Recruitment System – Validation Rules

## Overview

This project implements validation rules in a Salesforce Recruitment Management System to ensure data accuracy and maintain data integrity. The validation rules prevent users from entering invalid values in the Candidate Application and Job Opening objects.

---

# Activity 1: Offer Amount Validation Rule

## Object
**Candidate Application**

## Validation Rule Name
**Offer Amount Validation**

## Purpose
This validation rule ensures that the Offer Amount entered for a candidate is always greater than zero. It prevents users from saving records with zero or negative offer amounts.

### Error Condition Formula

```text
Offer_Amount__c <= 0
```

### Error Message

```text
Offer amount must be greater than zero.
```

### Error Location

Top of the Page

### Expected Result

- Users can save records only if the Offer Amount is greater than 0.
- If the Offer Amount is 0 or a negative value, Salesforce displays the validation error message.

---

# Activity 2: Job Vacancies Validation Rule

## Object
**Job Opening**

## Validation Rule Name
**Job Vacancies Validation**

## Purpose
This validation rule ensures that the number of vacancies for a job opening cannot be negative.

### Error Condition Formula

```text
Vacancies__c < 0
```

### Error Message

```text
Vacancies cannot be negative.
```

### Error Location

Top of the Page

### Expected Result

- Users can save the record only when the vacancy count is zero or greater.
- If a negative vacancy value is entered, Salesforce prevents the record from being saved and displays the validation message.

---

# Activity 3: AI Candidate Score Validation Rule

## Object
**Candidate Application**

## Validation Rule Name
**AI Candidate Score Validation**

## Purpose
This validation rule ensures that the AI Candidate Score does not exceed the maximum allowed value of 100.

### Error Condition Formula

```text
AI__Candidate_Score__c > 100
```

### Error Message

```text
AI Candidate score cannot exceed 100.
```

### Error Location

Top of the Page

### Expected Result

- Users can enter AI Candidate Scores from 0 to 100.
- If the score exceeds 100, Salesforce displays the validation error and prevents the record from being saved.

---

# Summary

The following validation rules were successfully implemented:

| Object | Validation Rule | Purpose |
|---------|-----------------|---------|
| Candidate Application | Offer Amount Validation | Prevents zero or negative offer amounts |
| Job Opening | Job Vacancies Validation | Prevents negative vacancy values |
| Candidate Application | AI Candidate Score Validation | Restricts AI Candidate Score to a maximum of 100 |

---

# Outcome

These validation rules improve data quality within the Salesforce Recruitment System by:

- Ensuring valid offer amounts are entered.
- Preventing invalid vacancy counts.
- Restricting AI Candidate Scores to the accepted range.
- Improving overall data consistency and reliability.

---

## Technologies Used

- Salesforce CRM
- Salesforce Object Manager
- Validation Rules
- Formula Expressions
- Salesforce Lightning Experience

---

## Author

**Phani**  
B.Tech Student  
Salesforce Recruitment System Project
