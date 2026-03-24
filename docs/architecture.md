# Architecture

## Overview

The Fecher AI Assistant follows a **prompt-driven, retrieval-augmented architecture**, implemented through a no-code AI platform.

---

## System Components

### 1. User Interface (Chat Widget)

* Web-based chatbot interface
* Accepts user queries
* Displays AI-generated responses

---

### 2. Prompt Layer (Core Logic)

The system prompt defines:

* Role and identity (Fecher AI Assistant)
* Business context
* Communication style
* Constraints and rules
* Tool usage strategy

This acts as the **primary control mechanism** of the system.

---

### 3. Knowledge Base

* Derived from the fecher.de website
* Acts as the **single source of truth**
* Used to ground responses in factual company information

---

### 4. Retrieval Layer

The system retrieves relevant information via:

* Website scraping (pre-indexed by platform)
* URL-based content fetching

---

### 5. AI Model Layer

* Processes:

  * User query
  * Retrieved context
  * System prompt

* Generates structured, context-aware responses

---

### 6. Tooling Layer

Includes:

* Knowledge base lookup (primary)
* Web browsing (secondary)
* URL retrieval

---

## Data Flow

1. User submits a query
2. System interprets intent
3. Relevant knowledge is retrieved
4. Prompt + context are combined
5. AI generates response
6. Response is returned to user

---

## Design Principles

* **Grounded Responses** → prioritize knowledge base
* **Controlled Behavior** → strict prompt constraints
* **Clarity** → structured output formatting
* **Business Alignment** → B2B tone and focus

---

## Architecture Type

This system can be categorized as:

👉 Retrieval-Augmented Generation (RAG)
👉 Prompt-Driven AI System
👉 No-Code AI Application

---

## Limitations

* Limited visibility into internal retrieval mechanisms
* No custom fine-tuning
* Platform dependency (Chipp)
