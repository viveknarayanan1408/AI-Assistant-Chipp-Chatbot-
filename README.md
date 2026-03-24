![Status](https://img.shields.io/badge/status-prototype-orange)
![Built With](https://img.shields.io/badge/built%20with-Chipp-blue)
![Type](https://img.shields.io/badge/type-AI%20Chatbot-purple)
![Approach](https://img.shields.io/badge/approach-Prompt%20Engineering-green)
![Architecture](https://img.shields.io/badge/architecture-RAG-lightgrey)
![Use Case](https://img.shields.io/badge/use%20case-B2B%20Automation-black)

# 🤖 Fecher AI Assistant

> A **prompt-engineered, retrieval-augmented AI assistant** designed to represent a real company (*fecher GmbH*) — built entirely without backend code.

🔗 **Live Demo:** https://faqbot-10037556.chipp.ai

---

## 🚀 What This Project Shows

This is not just a chatbot.

It demonstrates how to:

* Design **AI systems using prompt engineering**
* Build **domain-specific assistants grounded in real data**
* Apply **RAG (Retrieval-Augmented Generation)** without custom infrastructure
* Translate **business requirements → AI behavior**

---

## 🏗️ Architecture

This system follows a **prompt-driven RAG architecture**, implemented without custom backend code.

```
User
 │
 ▼
Chat Interface (Chipp UI)
 │
 ▼
System Prompt Layer
 - Role definition
 - Constraints
 - Tone & style
 │
 ▼
Retrieval Layer
 - Knowledge Base (fecher.de)
 - URL Retrieval
 - Web Search (optional)
 │
 ▼
AI Model (LLM)
 - Context + Prompt + Query
 │
 ▼
Response Generation
 │
 ▼
User Output
```

---

## 🧠 Core Idea

Instead of building a traditional backend, this system uses:

* **Prompt engineering as the control layer**
* **Website content as the knowledge base**
* **Tool-assisted retrieval for grounding**

👉 Result: A fully functional AI assistant with **zero custom backend code**

---

## 🎯 Use Case

The assistant acts as a **digital B2B representative** for fecher GmbH:

* Explains **Application Modernization** services
* Presents the **hunter recruitment software**
* Answers company-related questions
* Guides users toward **contact and conversion points**

---

## ⚙️ How It Works

1. The company website (`fecher.de`) is used as the knowledge source
2. A structured system prompt defines:

   * Behavior
   * Tone
   * Constraints
3. The system retrieves relevant information via:

   * Knowledge base (primary)
   * Web search (secondary)
4. The AI generates responses using:

   * Query + Context + Prompt

---

## ✍️ Prompt Engineering (Core of the System)

The system prompt defines:

* **Role:** AI assistant for fecher GmbH
* **Business domains:**

  * Application Modernization
  * Recruitment software (**hunter**)
* **Communication style:** Professional, B2B
* **Constraints:**

  * No pricing
  * No hallucinated services
  * Knowledge base priority

👉 Full prompt:
`/chatbot-config/system-prompt.md`

---

## 💡 Key Features

* 🌐 Website-grounded responses
* 💬 Structured, business-friendly answers
* 🎯 Lead qualification & redirection
* 🧭 Clear separation of service domains
* ⚙️ Controlled AI behavior via prompt constraints

---

## 🧪 Example Interaction

**User:**
“What services does fecher provide?”

**Assistant:**

* Application Modernization (legacy → .NET)
* Web-enabling existing systems
* Database migration
* Recruitment solution: **hunter**

---

## 📸 Demo

<img width="1920" height="1032" alt="AI Chatbot_fecher" src="https://github.com/user-attachments/assets/d3333103-1240-414e-955a-50465127519d" />

🎥 See full interaction flow:
`/docs/screenshots/example-conversation.mp4`

---

## ⚠️ Limitations

* Platform-dependent (Chipp)
* No custom backend or fine-tuning
* Limited control over retrieval internals

---

## 🛠️ Tech Stack

* No-code AI platform: [Chipp](https://chipp.ai?utm_source=chatgpt.com)
* Prompt Engineering
* Retrieval-Augmented Generation (RAG principles)

---

## 📌 Key Learnings

* Designing **AI behavior through structured prompts**
* Preventing hallucinations using **constraints + grounding**
* Building **usable AI systems without coding infrastructure**
* Translating **business needs into AI workflows**

---

## 🔮 Future Improvements

* Rebuild as a custom RAG pipeline (LangChain / OpenAI)
* Add analytics & user tracking
* Improve UI customization
* Deploy as embeddable widget

---

## 📄 Disclaimer

This project is a prototype and was not deployed in production.

---

## 👨‍💻 Author

**Vivek Narayanan**

---

## ⭐ Why This Project Stands Out

This project demonstrates:

* AI system design (not just usage)
* Prompt engineering as a control mechanism
* Real-world business application of AI
* Understanding of modern architectures like **RAG**

---
