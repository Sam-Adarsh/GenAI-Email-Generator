# 📧 Cold Email Generator

An AI-powered Streamlit application that scrapes job postings from career pages and automatically generates personalized cold emails using Llama 3 via Groq.

---

## 🔍 Overview

This tool is designed to help businesses and consultants create tailored cold emails for job leads. It extracts job data from a provided URL, matches the job's required skills with your portfolio projects, and crafts a professional cold email ready to send.

---

## 💡 Features

- 🔗 **Web Scraper**: Scrapes job details from any career or job listing webpage.
- 🧠 **LLM Integration**: Uses Llama 3 (`llama3-8b-8192`) via Groq API to generate emails.
- 🧹 **Content Cleaner**: Removes noise and irrelevant content from scraped text.
- 📁 **Portfolio Matching**: Recommends portfolio links based on job skill match.
- 💌 **Cold Email Generator**: Outputs a clean, customized cold email including client company name.

---

## 🧱 Tech Stack

- **Python 3.10+**
- **Streamlit** – for frontend UI
- **LangChain** – to manage prompts and chains
- **Groq** – to access Llama 3 models
- **dotenv** – for API key and environment config
- **ChromaDB** – (optional for future RAG-style improvements)

---

## 📁 Directory Structure

<pre>
<code>
```
cold-email-generator/
├── app/
│   ├── main.py
│   ├── chains.py
│   ├── portfolio.py
│   ├── utils.py
│   └── resource/
│       └── my_portfolio.csv
├── .env.example
├── requirements.txt
└── README.md
```
</code>
</pre>
