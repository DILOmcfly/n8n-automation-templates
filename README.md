# N8N Demo Workflows — Fiverr Portfolio
> By DiegoAutomates | 6 production-ready templates

## Workflows

### 1. 🚀 Lead Capture → CRM + Auto Email
**File**: `01-lead-capture-crm.json`
**Nodes**: Webhook → Validation → HubSpot + Google Sheets → Email + Slack
**Use case**: Capture leads from any form, create CRM contacts, send welcome emails, notify sales team.
**Apps**: HubSpot (or any CRM), Google Sheets, Email (SMTP), Slack

### 2. 🤖 AI Content Generator → Multi-Platform Publisher
**File**: `02-ai-content-generator.json`
**Nodes**: Schedule → Content Calendar → OpenAI (x2) → LinkedIn + Twitter → Update Status + Slack
**Use case**: Auto-generate and publish daily content across platforms using AI.
**Apps**: OpenAI, Google Sheets, LinkedIn, Twitter/X, Slack

### 3. 🛒 E-Commerce Order Processing (Shopify → Fulfillment)
**File**: `03-ecommerce-order-processing.json`
**Nodes**: Shopify Trigger → VIP Check → Email + Sheets + AI Thank You → Slack → Fulfillment API
**Use case**: Process Shopify orders: confirmation email, logging, VIP treatment, fulfillment.
**Apps**: Shopify, Email, Google Sheets, OpenAI, Slack, HTTP (fulfillment API)

### 4. 🎫 AI Customer Support Bot
**File**: `04-ai-customer-support.json`
**Nodes**: Webhook → Validate → OpenAI Classify → FAQ Branch (Auto-Reply) / Complex Branch (Draft + Slack Approval) → Google Sheets Log
**Use case**: AI-powered support that classifies tickets (urgency/category/sentiment), auto-replies to FAQs, drafts responses for human review, and logs everything.
**Apps**: OpenAI, Email (SMTP), Slack, Google Sheets
**Highlights**:
- 🧠 Ticket classification (urgency, category, sentiment, FAQ detection)
- ⚡ Instant auto-replies for common questions
- ✏️ AI-drafted responses sent to Slack for human approval
- 📊 Full ticket logging with status tracking
- 🔐 Input validation + error alerting

### 5. 📡 Social Media Brand Monitor
**File**: `05-social-media-monitor.json`
**Nodes**: Schedule (6h) → Brand Config → RSS Feeds → Filter → OpenAI Sentiment → Slack Alert (if negative) → Google Sheets Log + Weekly Report
**Use case**: Monitor brand mentions across the web, analyze sentiment with AI, get instant alerts for negative press, and receive weekly summary reports.
**Apps**: RSS Feeds, OpenAI, Slack, Google Sheets
**Highlights**:
- 🔍 Multi-source monitoring (Google News, Reddit, Hacker News RSS)
- 😊 AI sentiment analysis with impact scoring
- 🚨 Instant Slack alerts for negative mentions
- 📈 Automated weekly reports with metrics
- 🏷️ Topic extraction and action recommendations

### 6. 💰 Smart Invoicing System
**File**: `06-invoice-automation.json`
**Nodes**: Webhook → Validate → Process Data → Generate HTML Invoice → Email to Customer → Google Sheets Log → Slack Notify + Daily Overdue Check + Monthly Summary
**Use case**: Automated invoicing — generate professional invoices, email them, track payments, alert on overdue, and generate monthly revenue reports.
**Apps**: Email (SMTP), Slack, Google Sheets, Code (HTML generation)
**Highlights**:
- 📄 Professional HTML invoice generation (customizable template)
- ✉️ Auto-email invoices to customers
- 📒 Full accounting log in Google Sheets
- ⏰ Daily overdue payment alerts (>7 days)
- 📊 Monthly revenue reports with top customers
- 🧮 Auto-calculates subtotals, tax, and totals
- 📌 Includes sample test data for quick demos

---

## How to Import
1. Open n8n (self-hosted or cloud)
2. Click **"..."** → **Import from File**
3. Select the `.json` file
4. Update credentials (API keys, OAuth tokens)
5. Activate the workflow ✅

## Customization
Each workflow is designed to be easily customizable:
- Swap CRM (HubSpot → Salesforce, Airtable, Notion)
- Change notification channel (Slack → Discord, Teams, Email)
- Adjust AI prompts for your industry/tone
- Modify invoice template branding/colors
- Add/remove monitoring sources
- Customize classification categories

## Error Handling
All workflows include:
- ✅ Input validation with error responses
- 🔔 Slack error alerts for failed executions
- 🛡️ Graceful JSON parsing with fallbacks
- 📝 Comprehensive logging for debugging

## Need a Custom Workflow?
👉 **[Hire me on Fiverr](https://fiverr.com)** — I build n8n + AI automations tailored to your business.

### Pricing Guide
| Tier | What You Get | Price |
|------|-------------|-------|
| ⚡ Starter | 1 workflow setup + customization | $75 |
| 🚀 Pro | 3 workflows + integration | $200 |
| 💎 Enterprise | Full automation suite + support | $500+ |
