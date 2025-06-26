⚙️ n8n Workflow Automation Suite – Powered by AI
A powerful, production-ready collection of automation workflows built on n8n.io, designed to optimize operations, improve response time, and boost content engagement using OpenAI (ChatGPT) and other modern tools.

📦 Included Workflows
1. 🧠 Feedback Control Agent
Dynamically adjusts internal workflows based on structured user feedback such as scores and issue types.

Features:

Parses score & feedback type

Auto-routes logic (e.g., escalate bug reports, ignore positive scores)

Lightweight decision engine with Set + IF logic

Trigger: Webhook
Tech: n8n built-ins only

2. 💬 Customer Support Bot (ChatGPT)
Real-time customer support automation using OpenAI's ChatGPT.

Features:

Instant answers to customer questions

AI-generated responses from structured prompts

Easily connectable to Telegram, WhatsApp, or web chatbots

Trigger: Webhook
Tech: OpenAI (ChatGPT) + Webhook

3. 📣 Marketing Post Generator
Auto-generates polished marketing posts for social media from product data.

Features:

Accepts product name, features, tone

Builds prompt dynamically

ChatGPT returns copy-ready content

Trigger: Webhook
Tech: OpenAI (ChatGPT)

4. 📺 YouTube Automation Flow
Automates transcription, SEO metadata generation, and prepares for YouTube upload.

Features:

Transcribes audio into captions using Whisper

Generates title, description, tags using ChatGPT

Can be extended to auto-publish to YouTube or Notion

Trigger: Webhook
Tech: OpenAI GPT + Whisper, YouTube-ready

🛠 Setup & Usage
Requirements
n8n (self-hosted or cloud)

OpenAI API key

(Optional) Google API credentials for YouTube automation

Importing Workflows
Open the n8n editor UI

Go to Workflows > Import

Paste the JSON content provided in each section

Add your credentials:

OpenAI: Settings → Credentials → OpenAI

YouTube/Google: if applicable

Testing Workflows
Use tools like Postman or cURL to trigger the webhook endpoints.

Example:
bash
Copy
Edit
curl -X POST http://localhost: /webhook/suppo  \
  -H "Content-Type: application/json" \
  -d '{"question": "How do I reset my password?"}'
📈 Benefits
✅ Automates repetitive tasks

🤖 Leverages ChatGPT for dynamic content and decisions

⏱ Saves time and improves consistency

🔌 Easily extendable to external tools like Slack, Twitter, Airtable, Google Sheets, etc.

🔐 Security Notes
Ensure webhook URLs are protected or rate-limited

Validate API inputs before passing to GPT models

Keep OpenAI and Google credentials secure

📎 License
MIT License – feel free to adapt and enhance.

 
