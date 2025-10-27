# 🍽️ WhatsApp AI Agent – Dhaka Restaurant Assistant

An **AI-powered WhatsApp automation system** built using **n8n**, **Google Gemini (PaLM)**, and **Google Sheets** to handle restaurant customer interactions such as food ordering, FAQs, and inventory management — all through WhatsApp.

---

## 🚀 Project Overview

This project automates Dhaka Restaurant’s communication workflow by integrating **AI agents** with **WhatsApp Cloud API**.  
Customers can:
- 🛒 Place food orders  
- ℹ️ Ask FAQs (delivery time, payment, etc.)  
- 📦 Check order status or stock availability  

The system automatically logs and updates data into **Google Sheets**, while responding in real time via WhatsApp.

---

## 🧩 Workflow Overview

![Workflow Diagram](workflow.png)

### Components:
1. **WhatsApp Trigger** – Receives messages from customers via Meta Cloud API.  
2. **AI Agent** – Powered by LangChain and Google Gemini to interpret messages and respond intelligently.  
3. **Google Gemini Chat Model** – Provides AI-based responses.  
4. **Simple Memory** – Maintains session context for each customer.  
5. **Google Sheets Tools** –  
   - *Get Inventory* → Fetches food stock data.  
   - *Get FAQ* → Retrieves frequently asked questions.  
   - *Post Order* → Logs new confirmed orders.  
6. **Send Message** – Sends AI-generated WhatsApp replies to customers.

---

## ⚙️ Features

✅ Automated food ordering via WhatsApp  
✅ Intelligent conversation handling with AI (Google Gemini)  
✅ Real-time order & stock management through Google Sheets  
✅ Persistent chat memory for better user experience  
✅ Easy to deploy using **n8n workflow automation**

---

## 🧠 Tech Stack

- **n8n** – No-code/low-code workflow automation  
- **LangChain** – AI agent framework  
- **Google Gemini (PaLM)** – Chat model for natural conversation  
- **Google Sheets API** – Data management  
- **WhatsApp Cloud API** – Message sending and receiving  

---

## 📦 Setup Instructions

1. Clone this repository:
   ```bash
   git clone https://github.com/<your-username>/whatsapp-ai-agent.git
   cd whatsapp-ai-agent
