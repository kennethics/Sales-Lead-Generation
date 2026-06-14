Sales Lead Gen Automation (n8n)
AI-powered lead generation and personalized outreach workflow built with n8n that automatically discovers qualified prospects, enriches lead information, generates personalized emails, and sends outreach campaigns.

Business Problem
Sales teams spend countless hours:

Searching for qualified prospects
Researching companies and decision-makers
Personalizing outreach emails
Managing lead databases
Tracking outreach activity

This manual process slows pipeline growth and limits the number of high-quality prospects sales teams can engage.

This workflow automates the entire lead discovery and outreach process, allowing sales professionals to focus on conversations and closing deals instead of repetitive research tasks.

Schedule Trigger
        │
        ▼
Define Search Criteria
        │
        ▼
Lead Generation Agent (GPT-5)
        │
 ┌──────┼────────┬─────────┐
 ▼      ▼        ▼         ▼
Perplexity  LinkedIn   HTTP   Data
Search     Scraper    Request Storage
        │
        ▼
Structured Lead Output
        │
        ▼
Extract Leads
        │
        ▼
Loop Through Leads
        │
        ▼
Personalized Email Generation
        │
        ▼
Send Email (Gmail)
        │
        ▼
Store Campaign Summary


Integrations Used

OpenAI GPT-5

Used for:

Lead qualification
Prospect analysis
Personalized email creation
Perplexity Search

Used to:

Discover companies
Find relevant decision-makers
Gather business intelligence
Phantombuster

Used for:

LinkedIn profile enrichment
Professional data extraction
Gmail

Used for:

Sending personalized outreach emails
HTTP Request

Used for:

External API calls
Additional data enrichment
n8n Data Tables

Used for:

Lead storage
Campaign tracking
Reporting

Workflow Features

Automated Lead Discovery

Searches for prospects based on:

Industry
Job Title
Location
Company Size
AI Lead Qualification

Filters and prioritizes prospects that best match target criteria.

Personalized Outreach

Generates custom email copy for every lead using AI.

Automated Email Delivery

Sends personalized outreach directly from Gmail.

Campaign Reporting

Tracks:

Number of leads found
Emails sent
Campaign completion status

Expected Outcomes
After implementation, users can expect:

Increased Prospecting Efficiency

Reduce manual lead research by up to 80%.

Faster Outreach

Automatically generate and send personalized emails at scale.

Higher Lead Quality

AI-driven qualification helps prioritize high-fit prospects.

Consistent Pipeline Growth

Daily automated prospect discovery ensures a continuous flow of new opportunities.

Centralized Lead Management

Store and track all leads and outreach activity in one workflow.

Prerequisites
Before running this workflow, configure:

OpenAI API Credentials
Perplexity API Credentials
Gmail OAuth
Phantombuster Account
n8n Data Tables

Replace all placeholder values:
targetIndustry
targetRole
targetLocation
companySize
senderName
dataTableId

Installation
Download the workflow JSON.
Open n8n.
Click Import Workflow.
Select:
Sales Lead Gen Automation.json

License

MIT License

Author
Kenneth Soriano
AI Automation Specialist | Sales Operations | Workflow Automation | n8n Builder
