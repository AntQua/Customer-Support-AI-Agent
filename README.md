# Customer Support AI Agent

A Python-based AI-powered customer support agent, leveraging **LangFlow**, **RAG (Retrieval-Augmented Generation)**, and **Multi-Agent Systems**. The app integrates advanced AI capabilities to streamline customer support tasks like order management, FAQ handling, and real-world business workflows. It features a user-friendly interface built with **Streamlit** and a backend designed to optimize customer interactions.

## 🌐 Live Demo
Explore the live application: [Customer Support AI Agent](https://antqua-customer-support-ai-agent-main-4rumgl.streamlit.app/)

---

## 🚀 Features

### 🔍 **Order Management**
- Retrieve order details (e.g., shipped, canceled).
- Lookup product details, pricing, and availability.

### ❓ **FAQ Handling**
- Use RAG to provide accurate answers to common customer questions.
- Query PDFs or structured data for reliable replies.

---

## 🛠️ Key Capabilities
- **Database Querying**: Fetch order and product details directly using AI (no custom SQL required).
- **RAG Functionality**: AI processes PDF content to answer FAQs with verified data.
- **Multi-Agent Architecture**: Assign specific tasks like order lookups or FAQ handling to sub-agents.
- **Cancellation Assistance**: Automates policy lookups to assist with cancellations interactively.

---

## 🗂️ File Structure
- **`app.py`**: Main Streamlit application.
- **`requirements.txt`**: List of Python dependencies.
- **`README.md`**: Project documentation.
- **`data/`**: Sample datasets for orders and products.

---

## 🧰 Built With
- **[LangFlow](https://github.com/langflow/langflow)**: Drag-and-drop AI workflow builder.
- **[Streamlit](https://streamlit.io/)**: Python-based web app framework.
- **RAG**: Retrieval-Augmented Generation for contextually accurate responses.
- **[Astra DB](https://www.datastax.com/astra)**: Vector-enabled database for data storage and retrieval.



