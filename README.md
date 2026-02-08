# n8n-workflows-library
A collection of production-ready n8n workflows to automate CRM, lead generation, and business operations.



# n8n Automation & AI Library

A collection of production-ready n8n workflows designed to automate real estate operations, lead generation, and AI-driven customer service.

## 🚀 Workflows Overview

### 1. Real Estate Data Suite (ShBarcelona)
A two-part system to monitor and analyze property listings automatically.
* **Scraper**: Extracts flat listings from ShBarcelona and saves them to Google Sheets.
* **Enricher**: Automatically visits each listing to extract square meters, energy ratings, and neighborhood details.
* **Tools**: n8n, HTTP Request, HTML Parser, Google Sheets.

### 2. AI Content & Lead Gen Agent
A full-cycle automation that turns web forms into researched professional articles.
* **Process**: Captures lead data → AI researches and writes a 500-word article → Creates and shares a Google Doc → Emails the link to the lead.
* **CRM**: Automatically updates lead status to "Enviado" in Google Sheets and notifies the team via Slack.
* **Tools**: OpenAI (GPT-4.1 Mini), Google Workspace, Slack.

### 3. Advanced Multi-Stage AI Assistant
A sophisticated AI agent capable of handling complex interactions with safety and memory.
* **Message Queue**: Batches messages within 5 seconds to respond with full context.
* **Vision & Safety**: Analyzes images using AI vision and passes all text through a content moderation filter before responding.
* **Tools**: Supabase (Queueing), OpenAI Vision, Telegram, Gmail.

### 4. Smart WhatsApp Real Estate Bot
An AI-powered assistant that acts as a 24/7 sales agent for property inquiries.
* **Features**: Queries the property database, sends photos of flats, and captures customer data into a CRM.
* **Tools**: WhatsApp Business API, n8n, Google Sheets.

### **5. MotoGenius E-commerce Sales Assistant**
* **Purpose**: A specialized retail bot for motorcycle gear.
* **Capabilities**: Real-time product lookups, automated price-drop alerts, and multimedia (image) delivery.
* **Tools**: n8n LangChain, GPT-4o Mini, Google Sheets.

## 🛠️ How to Use
1.  **Download**: Choose the `.json` file for the workflow you want to use.
2.  **Import**: In your n8n instance, click "Import from File" and select the JSON.
3.  **Configure**: Set up your own credentials for Google Sheets, OpenAI, or Slack.
4.  **Execute**: Activate the trigger node to start the automation.

---
**Contact**: Reach out via GitHub if you have questions about these implementations.
