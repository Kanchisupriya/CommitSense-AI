# CommitSense-AI
**Real-Time GitHub Commit Intelligence & Risk Monitoring Agent**

CommitGuard AI is an AI-powered DevOps automation system that monitors GitHub commits in real time, analyzes them using OpenAI, and sends structured email alerts with risk insights.

Built using webhook-based event architecture for instant commit intelligence.

**✨ Features**

⚡ Real-time GitHub push event monitoring

🧠 AI-powered commit analysis

🏷 Automatic change classification (Feature / Bug / Documentation / Refactor)

📊 Risk scoring (1–10 scale)

🚨 Production-sensitivity detection

**🏗 System Architecture**


GitHub Push Event

        ↓
Webhook Trigger (Make.com)
        
        ↓
OpenAI Commit Analysis
        
        ↓
Risk & Classification Engine
        
        ↓
Automated Email Notification

This architecture ensures event-driven, real-time processing without polling.


**🛠 Tech Stack**

Make.com (Workflow Automation & Webhooks)

GitHub Webhooks

OpenAI API

Gmail Integration

**🧠 AI Output Structure**

The system generates structured commit intelligence in the following format:

Summary:

Change Type:

Risk Score (1-10):

Affected Area:

Production Sensitive (Yes/No):



## 🎥 Live Demo

Watch the project demo here:  
🔗 [CommitSense AI – Demo Video]()
