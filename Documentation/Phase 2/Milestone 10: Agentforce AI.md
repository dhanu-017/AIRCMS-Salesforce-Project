# AI-Powered Recruitment System using Salesforce Agentforce

## Project Overview

This project demonstrates the implementation of an AI-powered Recruitment Management System using **Salesforce Agentforce**. The solution enables recruiters and hiring managers to leverage Generative AI for candidate evaluation, hiring risk analysis, intelligent recommendations, and recruitment decision support while ensuring secure AI governance through Salesforce AI Trust features.

---

# Features

* Secure Agentforce AI configuration
* AI Trust and Permissions setup
* Candidate Application Summary generation
* Hiring Risk Analysis using Prompt Builder
* Recruitment AI Assistant Agent
* Intelligent Agent Actions
* Salesforce Data Library integration
* AI agent testing with recruitment scenarios
* Lightning Experience deployment for recruiters and hiring managers

---

# Technologies Used

* Salesforce Agentforce
* Prompt Builder
* AI Trust Layer
* Agent Builder
* Data Library
* Salesforce Lightning Experience
* Generative AI
* Salesforce CRM

---

# Activity 1: Enable Agentforce & AI Trust Settings

## Objective

Enable Agentforce securely for recruitment decision-making.

### Configuration

* Enabled Agentforce.
* Configured AI Trust & Permissions.
* Enabled:

  * Data Masking
  * Zero Data Retention
  * Audit Logging
* Granted Agentforce access to:

  * System Administrator
  * Hiring Manager

### Outcome

Established a secure AI environment with governance, privacy protection, and audit capabilities.

---

# Activity 2: Candidate Application Summary Prompt

## Objective

Generate AI-powered summaries of candidate applications.

### Prompt Type

Summary

### Object

Candidate_Application__c

### Summary Includes

* Candidate Name
* Job Opening Applied
* Experience Level
* Proposed Offer Amount
* AI Candidate Score
* Application Status
* Candidate strengths
* Hiring risks
* Special considerations

### Outcome

Recruiters can quickly understand candidate profiles through AI-generated summaries.

---

# Activity 3: Hiring Risk Analysis Prompt

## Objective

Evaluate candidate hiring risks using Generative AI.

### Prompt Type

Flex

### Object

Candidate_Application__c

### AI Analysis Includes

* Probability of successful hiring
* Financial risk based on salary
* Candidate stability
* Candidate suitability
* Overall hiring risk level
* Approval recommendation

### Outcome

Supports hiring managers with data-driven recruitment decisions.

---

# Activity 4: Recruitment Assistant Agent

## Objective

Create an AI assistant for recruitment activities.

### Agent Name

Recruitment Assistant Agent

### Responsibilities

* Candidate screening
* Offer approval assistance
* Hiring recommendations

### Topics

* Candidate Application Summary
* Hiring Risk Analysis
* Offer Approval Guidance

### Outcome

Created an intelligent AI assistant to streamline recruitment workflows.

---

# Activity 5: Configure Agent Actions

## Objective

Enable intelligent actions for the Recruitment Assistant Agent.

### Configured Actions

* Generate Candidate Application Summary
* Analyze Hiring Risk
* Recommend Approval Decision

### Configuration

Each action was mapped to its corresponding Prompt Template.

### Outcome

Enabled the AI agent to perform recruitment-specific tasks automatically.

---

# Activity 6: Configure Agent Data Library

## Objective

Provide secure Salesforce data access for Agentforce.

### Objects Added

* Contact (Candidate)
* Job_Opening__c
* Candidate_Application__c

### Access Settings

* Read Only
* Field-Level Security Enabled

### Outcome

Allowed the AI agent to answer recruitment questions using Salesforce data while maintaining data security.

---

# Activity 7: Test the Recruitment Assistant Agent

## Objective

Validate AI responses using real recruitment records.

### Test Questions

* Summarize this candidate application.
* Is this candidate safe to hire?
* What risks are involved in this salary offer?

### Validation

Verified:

* Response accuracy
* Clarity
* AI recommendations
* Recruitment insights

### Outcome

Confirmed that the AI agent generates meaningful recruitment assistance.

---

# Activity 8: Deploy Agentforce

## Objective

Deploy the Recruitment Assistant Agent for end users.

### Deployment

Deployment Type:

* Lightning Experience

Assigned Users:

* Recruiters
* Hiring Managers

### Outcome

Successfully deployed the AI recruitment assistant for organizational use.

---

# Project Workflow

1. Enable Agentforce and AI Trust Settings.
2. Create AI Prompt Templates.
3. Build the Recruitment Assistant Agent.
4. Configure Agent Actions.
5. Connect Salesforce Data Library.
6. Test AI responses.
7. Deploy the agent in Lightning Experience.

---

# Learning Outcomes

* Configured Salesforce Agentforce
* Implemented AI Trust and Security features
* Created Prompt Templates using Prompt Builder
* Built an AI Recruitment Assistant
* Configured intelligent Agent Actions
* Connected Salesforce Data Library
* Tested AI-generated recruitment responses
* Deployed Agentforce in Lightning Experience

---

# Conclusion

This project showcases the implementation of Salesforce Agentforce to enhance recruitment through Generative AI. By combining Prompt Builder, AI Trust, Agent Actions, and Salesforce Data Library, the Recruitment Assistant Agent provides intelligent candidate summaries, hiring risk analysis, and approval recommendations while maintaining enterprise-grade security and governance.
