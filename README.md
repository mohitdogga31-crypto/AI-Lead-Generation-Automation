# AI Lead Generation Automation

## Overview

This n8n workflow automates the lead generation process by capturing form submissions, storing lead information, sending automated emails, categorizing leads based on predefined rules, and updating lead records in Google Sheets.

The workflow helps streamline lead management and ensures timely communication with potential customers.

## Features

* Automatic lead capture from form submissions
* Store lead information in Google Sheets
* Automated email communication
* Lead categorization using Switch logic
* Personalized follow-up emails
* Automatic lead record updates
* Centralized lead tracking

## Tools Used

* n8n
* Form Trigger
* Google Sheets
* Gmail
* Switch Node

## Workflow Logic

### Step 1: Lead Submission

A new lead submits a form, triggering the workflow automatically.

### Step 2: Store Lead Information

Lead details are added to Google Sheets for record keeping and tracking.

### Step 3: Initial Email Response

An automated email is sent to acknowledge the lead submission.

### Step 4: Lead Categorization

The Switch node evaluates the lead based on predefined conditions and routes it to the appropriate path.

### Step 5: Personalized Follow-Up

Depending on the category, a customized email is sent to the lead.

### Step 6: Update Lead Records

The workflow updates the corresponding Google Sheets record with the latest lead status and communication details.

## Workflow Screenshot

![Lead Generation Workflow]<img width="1907" height="965" alt="lead generation-workflow" src="https://github.com/user-attachments/assets/8bc66761-5764-4600-98fe-ed582c7afd74" />

## Execution Screenshot

![Lead Generation Execution]<img width="1915" height="967" alt="lead generation-execution" src="https://github.com/user-attachments/assets/6e883b2a-aed8-42d5-a8e5-974deab0a86d" />


## Technologies

* n8n
* Google Sheets API
* Gmail API

## Benefits

* Eliminates manual lead processing
* Improves response time
* Organizes lead information automatically
* Ensures consistent communication
* Simplifies lead management
* Saves time through automation

## Author

Mohit Dogga
