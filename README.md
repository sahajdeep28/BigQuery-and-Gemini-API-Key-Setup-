# BigQuery-and-Gemini-API-Key-Setup-


This repository provides beginner-friendly instructions to generate and securely use:

- **Google BigQuery API Key**
- **Gemini API Key (via Google AI Studio)**

---

## 📌 Prerequisites

- Google Account
- Access to [Google Cloud Console](https://console.cloud.google.com)
- A code editor like VS Code

---

## 📊 BigQuery API Key Setup

### 1. Create or Select a Google Cloud Project

1. Visit [Google Cloud Console](https://console.cloud.google.com)
2. Click the **project dropdown** at the top
3. Select an existing project or click **"New Project"**

### 2. Enable BigQuery API

1. Navigate to: `APIs & Services > Library`
2. Search for **BigQuery API**
3. Click it, then hit **Enable**

### 3. Create an API Key

1. Go to: `APIs & Services > Credentials`
2. Click **"Create Credentials" > "API Key"**
3. Copy the generated key and **store it securely**

### 4. Restrict the API Key (Highly Recommended)

1. In the Credentials tab, click the **✏️ (edit)** icon next to your API key
2. Scroll to **API restrictions**
3. Select ✅ **Restrict key**
4. Choose ✅ **BigQuery API**
5. Click **Save**

> 🔒 **With API restrictions**: Your key can only be used for BigQuery, making it more secure  
> ⚠️ **Without restrictions**: The key is general-purpose and less secure

---

## 🧠 Gemini API Key Setup (Google AI Studio)

### What is Gemini?

Gemini is Google’s advanced AI model from the PaLM/Gemini family. It supports:

- Text generation
- Summarization
- Q&A
- And more...

### Steps to Generate a Gemini API Key (Free Tier)

1. Visit [Google AI Studio](https://makersuite.google.com/)
2. Sign in with your **Google Account**
3. Click your **profile icon** (top-right)
4. Select **API Key**
5. Click **Create API Key**
6. Copy and **store your API key securely**

### Example Usage in Python


```python
gemini_api_key = "your_generated_gemini_api_key"
