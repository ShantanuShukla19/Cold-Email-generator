# 📧 Cold Email Generator

An AI-powered cold email generator built using **Groq, LangChain, Streamlit, and a vector database**. This application automates personalized business outreach by extracting job listings from company career pages and matching job requirements with relevant portfolio projects.

## 🚀 Overview

Writing personalized cold emails to potential clients can be time-consuming. This project streamlines the process by analyzing job openings on a company's careers page and generating tailored outreach emails based on the requirements of each position.

The application uses a Large Language Model (LLM) powered by Groq to generate professional emails and a vector database to retrieve relevant portfolio links based on job descriptions.

### 💡 Use Case

Imagine Nike is hiring a Principal Software Engineer and investing time and resources in recruitment, onboarding, and training.

AtliQ, a software development company, can offer dedicated software development engineers to Nike. Mohan, a Business Development Executive at AtliQ, can use this application to generate a personalized cold email highlighting AtliQ's relevant expertise and portfolio.

Instead of manually researching job openings and drafting emails, the application automates the process of identifying opportunities and creating targeted outreach messages.

## ✨ Features

- **Automated Job Extraction:** Extracts job listings and descriptions from company career pages.
- **AI-Powered Email Generation:** Generates personalized and professional cold emails using Groq-hosted LLMs.
- **Context-Aware Personalization:** Tailors email content to the skills, technologies, and requirements mentioned in job descriptions.
- **Portfolio Matching:** Retrieves relevant portfolio links from a vector database using semantic similarity.
- **Interactive User Interface:** Provides a Streamlit-based interface for entering career-page URLs and generating emails.
- **Reduced Manual Effort:** Simplifies client research and business development outreach.

## 🛠️ Tech Stack

- **Python** – Core application logic
- **Streamlit** – Interactive user interface
- **Groq** – Large language model inference
- **LangChain** – LLM integration and workflow orchestration
- **Vector Database** – Semantic search and portfolio retrieval
- **Web Scraping and HTML Parsing** – Job listing extraction
- **python-dotenv** – Environment variable management

## 🏗️ Architecture

The application follows a structured workflow:

1. **User Input:** Accepts a company's careers page URL.
2. **Job Extraction:** Fetches and parses the careers page to extract job listings and descriptions.
3. **Job Analysis:** Processes job descriptions to identify relevant skills, technologies, and requirements.
4. **Portfolio Retrieval:** Searches the vector database for portfolio links relevant to the extracted job requirements.
5. **Email Generation:** Uses LangChain to integrate job details and matching portfolio information into a prompt for the Groq LLM.
6. **Personalized Output:** Generates a customized cold email for the prospective client.

---

**Built with ❤️ using Python, Groq, LangChain, and Streamlit.**
