# 🛍️ ShopAssist AI — E-Commerce Customer Care Bot
### FlowZint AI Hackathon 2026 Submission

---

## 📌 Problem Statement

E-commerce customers face long wait times, repetitive FAQs, and poor resolution quality from traditional support systems. This leads to cart abandonment, negative reviews, and high support costs.

---

## 💡 Solution

**ShopAssist AI** is an intelligent customer care chatbot designed for e-commerce platforms. It handles:

- 📦 Order tracking and status updates
- 🔁 Return & refund request processing
- 🛒 Product queries and recommendations
- 🚚 Delivery issue escalation
- 💳 Payment failure resolution

The bot uses NLP to understand natural language queries and provides instant, accurate responses — reducing human agent load by up to **70%**.

---

## 🏗️ Architecture

```
User → Chat UI (React)
         ↓
    Flask REST API
         ↓
   NLP Intent Engine (Claude AI / Gemini API)
         ↓
  ┌─────────────────────────┐
  │   Backend Logic Layer   │
  │  - Order DB (SQLite)    │
  │  - FAQ Knowledge Base   │
  │  - Escalation Engine    │
  └─────────────────────────┘
         ↓
   Response Generator
         ↓
      User
```

---

## 🛠️ Tech Stack

| Layer       | Technology          |
|-------------|---------------------|
| Frontend    | React.js + Tailwind CSS |
| Backend     | Python (Flask)      |
| AI Engine   | Claude API / Gemini API |
| Database    | SQLite              |
| Deployment  | Localhost / Vercel  |

---

## 🚀 How to Run

### Prerequisites
- Python 3.8+
- Node.js 16+
- API Key (Claude or Gemini)

### Backend Setup
```bash
cd backend
pip install -r requirements.txt
python app.py
```

### Frontend Setup
```bash
cd frontend
npm install
npm start
```

### Environment Variables
Create a `.env` file in `/backend`:
```
API_KEY=your_api_key_here
MODEL=claude-sonnet-4-20250514
```

---

## 💬 Sample Conversations

**Order Tracking:**
> User: "Where is my order #12345?"
> Bot: "Your order #12345 is out for delivery! Expected by 6 PM today. 📦"

**Return Request:**
> User: "I want to return the shoes I bought."
> Bot: "No problem! I've initiated a return for your order. You'll receive a pickup confirmation within 24 hours. 🔁"

**Product Query:**
> User: "Do you have wireless headphones under ₹2000?"
> Bot: "Yes! Here are 3 options that match your budget: ..."

---

## 🎯 Key Features

- ✅ Real-time order status lookup
- ✅ Multi-turn conversation support
- ✅ Automatic escalation to human agent
- ✅ 24/7 availability
- ✅ Supports 50+ FAQ categories
- ✅ Sentiment detection for frustrated customers

---

## 📊 Impact Metrics (Projected)

| Metric | Before | After |
|--------|--------|-------|
| Avg Resolution Time | 8 min | 45 sec |
| Human Agent Load | 100% | 30% |
| Customer Satisfaction | 62% | 89% |
| Support Cost/Month | ₹50,000 | ₹15,000 |

---

## 👥 Team

| Name | Role |
|------|------|
| Shaik Jasmine | Team Lead / AI Developer |

---

## 📁 Folder Structure

```
shopassist-ai/
├── frontend/
│   ├── src/
│   │   ├── App.jsx
│   │   ├── ChatWindow.jsx
│   │   └── MessageBubble.jsx
│   └── package.json
├── backend/
│   ├── app.py
│   ├── intent_classifier.py
│   ├── order_handler.py
│   └── requirements.txt
├── data/
│   └── faq_knowledge_base.json
└── README.md
```

---

## 📬 Contact

- **Name:** Shaik Jasmine
- **Email:** jasmineshaik395@gmail.com
- **Submission Portal:** https://flowzint.in/2026/ai/hackothon/

---

*Submitted for FlowZint AI Hackathon 2026 — Category: Customer Care Bot*
