# 🧠 Real-Time Text Summarization using NLP and Flask

This project is a Flask-based web application that leverages pre-trained NLP models from Hugging Face to generate concise summaries from lengthy documents in real-time. It enables users to submit large texts via a RESTful API and instantly receive summarized output, enhancing readability and reducing manual effort.

---

## 🚀 Features

- ⚡ **Real-Time Summarization**: Processes and summarizes content within seconds.
- 🤖 **Hugging Face Transformers**: Uses state-of-the-art NLP models for accurate and fluent summaries.
- 🔌 **RESTful API**: Clean and scalable architecture for easy integration into other applications.
- 🐳 **Dockerized Deployment**: Containerized using Docker for easy setup, portability, and scalability.

---

## 🛠️ Tech Stack

- **Backend**: Flask (Python)
- **NLP**: Hugging Face Transformers (e.g., `facebook/bart-large-cnn`, `t5-base`)
- **Containerization**: Docker
- **Others**: Gunicorn (for production deployment), Requests, JSON handling

---

## 🧪 How to Run Locally

1. **Clone the repository**
   ```bash
   git clone https://github.com/YourUsername/text-summarizer-flask.git
   cd text-summarizer-flask
