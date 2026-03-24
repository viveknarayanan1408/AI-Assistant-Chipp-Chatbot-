![Status](https://img.shields.io/badge/status-prototype-orange)
![Built With](https://img.shields.io/badge/built%20with-Chipp-blue)
![Type](https://img.shields.io/badge/type-AI%20Chatbot-purple)
![Approach](https://img.shields.io/badge/approach-Prompt%20Engineering-green)
![Architecture](https://img.shields.io/badge/architecture-RAG-lightgrey)
![Use Case](https://img.shields.io/badge/use%20case-B2B%20Automation-black)


# 🤖 Fecher AI Assistant (Chipp Chatbot)

An AI-powered business assistant created using **Chipp** to represent *fecher GmbH*, providing automated answers based on the company website content and structured prompt design.

🔗 **Live Chatbot:** https://faqbot-10037556.chipp.ai

---

## 🚀 Overview

This project demonstrates how a **no-code AI platform** can be used to build a professional, domain-specific chatbot for a real company.

The assistant was designed to:

* Answer questions about fecher GmbH
* Explain services like **Application Modernization**
* Present the **hunter recruitment software**
* Guide potential clients toward contact channels

---

## 🏗️ Architecture

This system follows a prompt-driven RAG (Retrieval-Augmented Generation) architecture, implemented without custom backend code.

        ┌───────────────┐
        │     User      │
        └──────┬────────┘
               │
               ▼
     ┌────────────────────┐
     │   Chat Interface   │
     └────────┬───────────┘
              │
              ▼
     ┌────────────────────┐
     │   System Prompt    │
     │ (Behavior Control) │
     └────────┬───────────┘
              │
              ▼
     ┌────────────────────┐
     │   Retrieval Layer  │
     │ (Website Content)  │
     └────────┬───────────┘
              │
              ▼
     ┌────────────────────┐
     │     AI Model       │
     │ (Response Gen)     │
     └────────┬───────────┘
              │
              ▼
        ┌───────────────┐
        │   Response    │
        └───────────────┘

---

## 🧠 Key Concept

Instead of traditional coding, this chatbot was built using:

* Prompt engineering
* Structured system instructions
* Website-based knowledge grounding

This project highlights how powerful AI systems can be created **without writing backend code**.

---

## 🏗️ How It Works

1. The company website (fecher.de) is used as the knowledge source
2. A structured system prompt defines behavior, tone, and constraints
3. The chatbot uses:

   * Knowledge base (primary)
   * Web browsing (secondary)
4. Responses are generated based on:

   * Context + prompt instructions + retrieved content

---

## ✍️ System Prompt Design

The core of this project is the system prompt, which defines:

* Role: AI assistant for fecher GmbH
* Business focus:

  * Application Modernization
  * Recruitment software (**hunter**)
* Communication style: B2B, professional
* Constraints:

  * No pricing
  * No hallucinated services
  * Knowledge base priority

👉 See full prompt here:
`/chatbot-config/system-prompt.md`

---

## 💡 Features

* 🌐 Website-aware responses
* 💬 Structured, professional answers
* 🎯 Lead qualification & redirection
* 🧭 Clear separation of business areas
* ⚙️ Tool usage strategy (KB + web search)

---

## 🧪 Example Interaction

**User:**
"What services does fecher provide?"

**Bot:**

* Application Modernization (legacy → .NET)
* Web-enabling software
* Database migration
* Recruitment solution: **hunter**

---

## 📸 Screenshots

<img width="1920" height="1032" alt="AI Chatbot_fecher" src="https://github.com/user-attachments/assets/d3333103-1240-414e-955a-50465127519d" />



To find out the chat structure, check out the video in `/screenshots/example-conversation.mp4`


---

## ⚠️ Limitations

* No custom backend logic (platform-based)
* Dependent on Chipp infrastructure
* Limited control over the retrieval pipeline

---

## 🛠️ Tech Stack

* [Chipp Platform](https://chipp.ai?utm_source=chatgpt.com) (No-code AI builder)
* Prompt Engineering
* Web-based knowledge retrieval

---

## 📌 Learnings

This project demonstrates:

* How to design structured AI prompts for real businesses
* How to control hallucinations using constraints
* How to guide AI behavior using tool strategies
* How to build usable AI products without coding

---

## 🔮 Future Improvements

* Export to custom RAG pipeline (LangChain / OpenAI)
* Add analytics & user tracking
* Improve UI customization
* Deploy as an embedded website widget

---

## 📄 Disclaimer

This chatbot was created as a prototype and was not deployed in production.

---

## 🙌 Author

Developed by Vivek Narayanan

---

## ⭐ Why This Project Matters

This is not just a chatbot — it demonstrates:

* AI system design thinking
* Prompt engineering expertise
* Business-oriented AI application
