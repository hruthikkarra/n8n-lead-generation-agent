<img width="1758" height="658" alt="image" src="https://github.com/user-attachments/assets/2b7b733a-fea1-4f3f-b21b-b99a9dbbffbf" />
# 🚀 n8n Lead Generation Agent

An automated lead generation and enrichment system built using **n8n**, **Apify**, and external APIs.  
This workflow collects leads, removes duplicates, enriches data, and stores structured records for further automation.

---

## 📌 Overview

This automation pipeline is designed to:

1. Capture form input
2. Trigger an Apify actor
3. Extract dataset results
4. Clean and normalize lead data
5. Remove duplicates
6. Enrich leads via HTTP requests
7. Convert HTML responses to structured markdown
8. Store records in Airtable
9. Merge processed data streams
10. Automate wait logic & rate handling

This workflow is ideal for:
- AI Agencies
- Marketing Automation
- Sales Teams
- Lead Generation Businesses
- Growth Hackers

---

## 🧠 Workflow Architecture

### Trigger
- **On Form Submission**

### Data Collection
- Run Apify Actor
- Get Dataset Items

### Data Processing
- Edit Fields
- Loop Over Items
- Remove Duplicates
- JavaScript Transformation

### Data Enrichment
- HTTP Request (external enrichment API)
- HTML to Markdown conversion

### Storage
- Create Record (Airtable)

### Flow Control
- Merge Nodes
- Wait Nodes (rate limit & batching)
- Filter Conditions

---

## 🛠 Tech Stack

| Tool | Purpose |
|------|---------|
| n8n | Workflow automation engine |
| Apify | Data scraping & lead extraction |
| Airtable | Lead database storage |
| HTTP APIs | Data enrichment |
| JavaScript Node | Custom data transformation |

---

