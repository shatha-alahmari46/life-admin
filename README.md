# Life Admin 🤖

> مساعد شخصي ذكي لتنظيم المهام والمواعيد والإيميلات باستخدام اللغة الطبيعية والذكاء الاصطناعي.

## ✨ Features

- 🧠 **Natural Language** — تنفيذ الطلبات بصياغة طبيعية باللغة العربية.
- ✅ **Task Management** — إنشاء المهام وإدارتها عبر Google Tasks.
- 📅 **Calendar Management** — إنشاء المواعيد والأحداث عبر Google Calendar.
- 📧 **Email Management** — قراءة وتنظيم وإرسال الإيميلات عبر Gmail.
- 📊 **Daily Overview** — عرض مهام اليوم والمواعيد والإيميلات المهمة وسجل النشاط.
- 🌐 **Arabic & RTL** — واجهة مصممة للعربية مع دعم كامل للـ RTL.

## 🏗️ Architecture

```text
User
  ↓
Life Admin Web App
  ↓
Backend API
  ↓
n8n Webhook
  ↓
AI Agent
  ├── Google Tasks
  ├── Google Calendar
  └── Gmail
  ↓
Structured Response
  ↓
Life Admin Dashboard
🛠️ Technologies
React
Google Gemini
n8n
AI Agents
Google Tasks
Google Calendar
Gmail
GitHub
🔄 How It Works
يكتب المستخدم طلبه باللغة الطبيعية.
يتم إرسال الطلب إلى الـ Backend.
ينتقل الطلب إلى Workflow في n8n.
يقوم الـ AI Agent بفهم الطلب وتحديد الإجراء المناسب.
يتم تنفيذ العملية من خلال خدمة Google المناسبة.
تعود النتيجة إلى التطبيق وتظهر للمستخدم.
🔐 Security

Sensitive credentials and API keys should never be stored in the source code.

Environment variables and secure credential management should be used for sensitive configuration.

📸 Project Preview

The repository includes screenshots and a demonstration of the Life Admin interface.

🚀 Project Status

Life Admin is an ongoing project exploring practical applications of AI Agents, workflow automation, natural-language interfaces, and productivity tools.

🎯 Future Improvements
Smarter intent detection
More AI-powered actions
Improved Arabic natural-language understanding
Smarter daily planning
Additional Google Workspace integrations
More personalization
👩🏻‍💻 Project

Life Admin — An AI-powered personal productivity assistant built to explore practical applications of AI Agents and workflow automation.
