# 🛒 E-commerce Order Notification System
**Automated order processing workflow built with n8n**

> Streamline your e-commerce operations with automated order processing, Google Sheets integration, and instant Telegram notifications.

[Demo Video] | [Live Demo] | [Documentation]

## 💡 The Problem

Small e-commerce businesses face these daily challenges:
- ⏰ **Manual Order Entry**: Copying order details from emails to spreadsheets
- 📱 **Delayed Notifications**: Missing orders during peak hours
- 😰 **Human Error**: Typos and missed information
- 💸 **Lost Revenue**: Customers abandoning orders due to slow confirmations

**Result**: Hours wasted on repetitive tasks instead of growing the business.

## ✨ The Solution

This n8n workflow automates your entire order confirmation process:

1. **📧 Email Monitoring** - Watches for new order emails in real-time
2. **🔍 Smart Extraction** - Parses order details automatically
3. **📊 Google Sheets Integration** - Updates your order tracking sheet instantly
4. **💬 Telegram Notifications** - Sends formatted confirmations to customers

**Time Saved**: 2-3 hours per day | **Orders Processed**: Unlimited | **Error Rate**: Near zero

## 🔄 Workflow Architecture
<img width="1022" height="655" alt="Porject#1" src="https://github.com/user-attachments/assets/7906f302-d024-4b83-8f84-f2f87b478c75" />


## 🎯 Key Features

### Core Functionality
- ✅ **Email Trigger** - IMAP/webhook integration
- ✅ **Data Extraction** - Order ID, customer info, items, total
- ✅ **Google Sheets** - Automatic row creation with timestamps
- ✅ **Telegram Bot** - Formatted order confirmations

### Advanced Features
- 🔔 **Error Handling** - Retry logic and fallback notifications
- 📈 **Analytics Ready** - Structured data for reporting
- 🎨 **Customizable Templates** - Easy message formatting
- 🔐 **Secure** - Environment variables for credentials

## 🚀 Quick Start

### Prerequisites
- n8n instance (self-hosted or cloud)
- Google account with Sheets API enabled
- Telegram Bot Token
- Email account with IMAP access

### Installation

1. **Clone the repository**
```bash
   git clone https://github.com/yourusername/n8n-ecommerce-order-automation.git
   cd n8n-ecommerce-order-automation
```

2. **Import workflow into n8n**
   - Open n8n
   - Go to Workflows > Import from File
   - Select `Project#1.json`

3. **Configure credentials**
```bash
   cp .env.example .env
   # Edit .env with your credentials
```

4. **Set up integrations** (see [detailed setup guide](docs/SETUP.md))
   - Gmail/Email configuration
   - Google Sheets API
   - Telegram Bot Token

5. **Test the workflow**
   - Send a test order email
   - Verify Google Sheets update
   - Check Telegram notification

### Configuration
See [Configuration Guide](docs/CONFIGURATION.md) for detailed setup instructions.
