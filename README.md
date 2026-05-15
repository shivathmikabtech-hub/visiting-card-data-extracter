Here’s a professional GitHub README description for your **Advanced AI Visiting Card Extractor Workflow using n8n + OpenAI + Google Sheets**.

---

# 📇 AI Visiting Card Extractor using n8n + OpenAI

An intelligent automation workflow built using **n8n**, **OpenAI GPT-4o-mini**, and **Google Sheets** to extract structured business lead information from visiting card images automatically.

The workflow accepts a visiting card image through a webhook, processes the image using AI vision capabilities, extracts key details in JSON format, and stores the data directly into Google Sheets for lead management and CRM workflows.

---

## 🚀 Features

✅ AI-powered visiting card OCR extraction
✅ Extracts structured lead information automatically
✅ Uses GPT-4o-mini vision model
✅ Smart industry detection logic
✅ Auto-saves leads to Google Sheets
✅ Supports image upload via webhook/API
✅ Handles missing values gracefully
✅ JSON parsing and data cleaning included
✅ No manual data entry required

---

# 📌 Extracted Fields

The workflow extracts:

* First Name
* Last Name
* Phone Number
* Email Address
* Company Name
* Designation
* Address
* Industry Type

---

# 🧠 Smart Industry Classification

The AI intelligently identifies industries based on:

* Company name
* Products/services
* Designation
* Business keywords
* Taglines
* Logo text

### Example Classifications

| Card Content                | Industry Output                  |
| --------------------------- | -------------------------------- |
| Hospital furniture supplier | Hospital Furniture Manufacturing |
| Software company            | Technology                       |
| Hospital/Clinic             | Healthcare                       |
| Construction company        | Construction                     |
| Bank/Insurance              | Finance                          |
| Hotel/Travel agency         | Hospitality                      |

---

# ⚙️ Workflow Architecture

## 🔹 Step 1 — Webhook Trigger

Receives visiting card image through POST API request.

## 🔹 Step 2 — OpenAI Vision Processing

GPT-4o-mini analyzes the image and extracts structured information.

## 🔹 Step 3 — JSON Parsing

Custom JavaScript cleans and parses AI response.

## 🔹 Step 4 — Google Sheets Integration

Automatically appends extracted lead data into Google Sheets.

---

# 🛠️ Technologies Used

* n8n
* OpenAI GPT-4o-mini
* JavaScript
* Google Sheets API
* Webhooks
* AI Vision Models
* JSON Processing

---

# 📂 Workflow Components

## 1️⃣ Webhook Node

Receives image uploads.

## 2️⃣ OpenAI Model Node

Processes image and extracts structured data.

## 3️⃣ JavaScript Code Node

* Cleans JSON
* Parses AI response
* Formats phone numbers

## 4️⃣ Google Sheets Node

Stores lead data automatically.

---

# 📊 Sample JSON Output

```json
{
  "firstname": "John",
  "lastname": "Doe",
  "phone": "9876543210",
  "email": "john@example.com",
  "company": "ABC Technologies",
  "designation": "Sales Manager",
  "address": "Hyderabad, India",
  "industry": "Technology"
}
```

---

# 🔥 Use Cases

* CRM Automation
* Lead Management
* Sales Automation
* Business Card Digitization
* Contact Database Creation
* Event Lead Collection
* Networking Automation

---

# 📈 Benefits

✅ Saves manual data entry time
✅ Faster lead processing
✅ Reduces human errors
✅ Scalable automation
✅ AI-powered business categorization
✅ Easy integration with CRM systems

---

# 🧪 Future Improvements

* Duplicate lead detection
* CRM integrations (Salesforce/HubSpot)
* WhatsApp lead notifications
* Email automation
* Multi-language visiting card support
* QR code extraction
* Database storage support

---

# 📸 Workflow Overview

```text
Webhook → OpenAI Vision → JSON Parsing → Google Sheets
```

---

# 👨‍💻 Developed By

AI Automation & Data Engineering Project using:

* n8n Workflow Automation
* OpenAI Vision Models
* Google Workspace Integration

---

# ⭐ GitHub Topics / Tags

```text
n8n
openai
automation
ocr
business-card-reader
ai-workflow
google-sheets
lead-generation
workflow-automation
gpt4o
artificial-intelligence
computer-vision
crm-automation
ai-agent
json-processing
```
