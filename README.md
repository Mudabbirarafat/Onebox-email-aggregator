# ReachInbox Onebox Email Aggregator

This project is part of the **ReachInbox Backend Engineer Assignment**.  
It’s a full-stack system that synchronizes multiple IMAP email accounts in real-time, provides AI-based categorization, and integrates with Slack and Webhooks.

---

## 🚀 Features

### 1. Real-Time Email Synchronization
- Syncs multiple IMAP accounts in **real time** (no cron jobs!)
- Fetches the last 30 days of emails
- Uses persistent IMAP IDLE connections

### 2. Searchable Storage (Elasticsearch)
- Emails indexed in **Elasticsearch (Docker)**
- Full-text search by account, folder, and content

### 3. AI Email Categorization
- Classifies emails into:
  - Interested
  - Meeting Booked
  - Not Interested
  - Spam
  - Out of Office

### 4. Slack & Webhook Integration
- Sends Slack alerts for **Interested** leads
- Triggers webhooks for automation workflows

### 5. Frontend Interface
- Displays categorized emails
- Search and filter options via Elasticsearch

### 6. (Bonus) AI-Powered Suggested Replies
- Uses RAG (Retrieval-Augmented Generation)
- Suggests context-aware replies using product and outreach info

---

## 🧰 Tech Stack

**Backend:** Node.js (TypeScript)  
**Search Engine:** Elasticsearch (Docker)  
**AI Categorization:** OpenAI / Local LLM  
**Frontend:** React + Tailwind  
**Integration:** Slack API, Webhooks  
**Database (optional):** MongoDB / PostgreSQL  

---

## ⚙️ Setup Instructions

1. Clone the repository:
   ```bash
   git clone https://github.com/Mudabbirarafat/Onebox-email-aggregator.git
   cd Onebox-email-aggregator
