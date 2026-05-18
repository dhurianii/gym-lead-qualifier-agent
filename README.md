# gym-lead-qualifier-agent
# 🏋️ Gym Lead Qualification System

AI-powered lead qualifier built with n8n + OpenRouter + Google Sheets + Tally Forms

## 🔧 Tech Stack
- **Tally Forms** — Lead capture
- **n8n** — Workflow automation
- **OpenRouter (GPT-4o-mini)** — AI qualification
- **Google Sheets** — Lead database
- **Gmail** — Hot/Warm lead alerts

## 🎯 Qualification Rules
- 🔥 Hot — Right timeline + budget ₹2000+ + Powai/Vikhroli/Kanjurmarg
- 🟡 Warm — Interested but missing one Hot condition
- ❄️ Cold — Low budget OR not ready OR far location

## 📊 Workflow
Tally Form → n8n Webhook → Edit Fields → 
OpenRouter AI → Merge → Code Node → 
Google Sheets → IF Node → Gmail

## 🚀 How to Use
1. Import the `.json` file into n8n
2. Add your OpenRouter API key
3. Connect Google Sheets + Gmail
4. Update Tally webhook URL
5. Activate workflow
