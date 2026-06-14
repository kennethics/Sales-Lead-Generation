# 🚀 Sales Lead Gen Automation (n8n)

AI-powered lead generation and outreach automation built with n8n, OpenAI, Perplexity, Phantombuster, and Gmail.

This workflow automatically discovers qualified prospects, enriches lead data, generates personalized outreach emails, and sends them at scale.

---

## 📌 Business Problem

Sales teams spend significant time on repetitive tasks such as:

* Finding potential leads
* Researching decision-makers
* Collecting contact information
* Writing personalized outreach emails
* Tracking outreach activity

These manual processes slow down pipeline generation and reduce overall sales productivity.

This workflow automates the entire prospecting and outreach process, allowing sales professionals to focus on conversations, meetings, and closing deals.

---

## ⚙️ What This Workflow Does

1. Runs automatically on a scheduled basis.
2. Searches for companies and decision-makers matching your target criteria.
3. Enriches lead information using AI and LinkedIn data.
4. Filters and qualifies prospects.
5. Generates personalized outreach emails for each lead.
6. Sends emails automatically through Gmail.
7. Stores lead and campaign data for reporting and future follow-ups.

---

## 🏗 Workflow Architecture

```text
Schedule Trigger
       │
       ▼
Define Search Criteria
       │
       ▼
AI Lead Generation Agent
       │
 ┌─────┼──────────┬──────────┐
 ▼     ▼          ▼          ▼
Perplexity   LinkedIn   HTTP Request
 Search      Scraper     Enrichment
       │
       ▼
Qualified Leads
       │
       ▼
Extract Leads
       │
       ▼
Loop Through Leads
       │
       ▼
AI Email Generator
       │
       ▼
Gmail Outreach
       │
       ▼
Campaign Summary Storage
```

---

## 🔌 Integrations Used

### OpenAI

Used for:

* Lead qualification
* Lead analysis
* Personalized email generation

### Perplexity

Used for:

* Company research
* Prospect discovery
* Market intelligence

### Phantombuster

Used for:

* LinkedIn profile enrichment
* Professional data extraction

### Gmail

Used for:

* Automated email delivery
* Personalized outreach campaigns

### HTTP Request

Used for:

* Additional API integrations
* Data enrichment

### n8n Data Tables

Used for:

* Lead storage
* Campaign tracking
* Reporting

---

## 📊 Expected Outcomes

### Faster Prospecting

Reduce manual lead research by up to 80%.

### Better Lead Quality

AI qualification prioritizes high-fit prospects.

### Personalized Outreach at Scale

Generate custom emails for every lead automatically.

### Consistent Pipeline Growth

Discover new opportunities daily without manual effort.

### Improved Sales Productivity

Spend more time selling and less time researching.

---

## 🛠 Prerequisites

Before using this workflow, configure:

* OpenAI API Credentials
* Perplexity API Credentials
* Gmail OAuth Credentials
* Phantombuster Account
* n8n Data Tables

---

## 🔧 Required Configuration

Update the following fields before activating the workflow:

| Field          | Example                |
| -------------- | ---------------------- |
| targetIndustry | Technology             |
| targetRole     | VP of Sales            |
| targetLocation | United States          |
| companySize    | 50–500 Employees       |
| senderName     | Your Name              |
| dataTableId    | Your n8n Data Table ID |

---

## 📥 Installation

### Step 1

Download the workflow JSON file.

### Step 2

Open your n8n instance.

### Step 3

Navigate to:

```
Workflows → Import from File
```

### Step 4

Select:

```
Sales Lead Gen Automation.json
```

### Step 5

Configure all required credentials.

### Step 6

Update the search criteria and sender details.

### Step 7

Activate the workflow.

---

## 📈 Example Use Cases

* B2B Lead Generation
* Agency Prospecting
* SaaS Sales Outreach
* Recruitment Lead Sourcing
* Consulting Client Acquisition
* Account-Based Marketing (ABM)

---

## 🔒 Notes

* Always comply with email marketing regulations in your region.
* Review generated emails before large-scale campaigns.
* Ensure LinkedIn and data collection activities comply with platform policies and local regulations.

---

## 📄 License

MIT License

---

## 👨‍💻 Author

Built with n8n, AI, and workflow automation to streamline modern sales prospecting and outreach.
