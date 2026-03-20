# 🚀 AI Gmail AutoSorter  
Your Personal AI Inbox Assistant 📨🤖

> ✨ **Let AI manage your inbox!**  
Automatically sorts, labels, and drafts replies for Gmail — so you focus only on what matters.

---

## 🌟 Features

✅ **Real-time Inbox Monitoring** — new emails are processed instantly  
✅ **AI Categorization** — labels emails into:
- 📬 **Meetings**
- 📢 **Promos**
- 🕒 **Check Later**
- 🤝 **Sponsorships**
- 🚫 **Spam**

✅ **Auto Draft Replies** — AI writes drafts for important emails  
✅ **Zero Manual Sorting** — Inbox stays clean without you lifting a finger

---

## 🛠 How It Works  

1️⃣ **Trigger** → Gmail Trigger watches for new emails  
2️⃣ **Extract Details** → Fetch sender, subject, and body  
3️⃣ **AI Processing** → Uses `o3-mini` model with extra context  
4️⃣ **Draft Creation** → AI prepares reply drafts automatically  
5️⃣ **Smart Labeling** → Gmail labels applied instantly  

---

## 📸 Workflow Preview  

![Workflow Screenshot](workflow.png)  
*(Blur any personal info before uploading)*  

---

## 📦 Requirements  

- Gmail Account  
- [n8n](https://n8n.io/) or similar automation platform  
- OpenAI API key (or compatible AI model)  
- Basic workflow building knowledge  

---

## 🚀 Setup Guide  

```bash
# 1️⃣ Clone the repo
git clone https://github.com/yourusername/AI-Gmail-AutoSorter.git

# 2️⃣ Install & Run n8n
# (Follow n8n setup guide: https://docs.n8n.io/)

# 3️⃣ Import workflow.json into n8n

# 4️⃣ Add your Gmail + AI API credentials

# 5️⃣ Activate & watch the magic happen! ✨
