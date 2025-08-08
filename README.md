# n8nworkflow
# 📲 WhatsApp Automation using n8n + Meta API

This project connects WhatsApp (via Meta's Cloud API) to n8n for automated messaging. It includes setup steps for Meta Business Account, WhatsApp API, and n8n workflow integration.

---

## 🔧 Setup Instructions

### 1. Create n8n Account & Workflow
- Sign up at [n8n.io](https://n8n.io)
- Create a new workflow
- Add nodes: Webhook (optional), HTTP Request, and any logic nodes needed

### 2. Meta Business Account Setup
- Go to [Meta for Developers](https://developers.facebook.com/)
- Create a Business Account
- Create an App and enable **WhatsApp** product
- Generate:
  - Access Token
  - Phone Number ID
  - Business Account ID

### 3. WhatsApp API Configuration
- Add **Sender Phone Number** (registered with Meta)
- Add **Receiver Phone Number** (must opt-in to receive messages)
- Test message sending via Meta’s Graph API

### 4. n8n Integration
Use an HTTP Request node with the following configuration:

**Endpoint:**
