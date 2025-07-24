Streamlit Chatbot
A fully-featured, multi-session chatbot web app powered by OpenAI and Streamlit.

🚀 Features
User registration and login (PostgreSQL backend)

Multiple chat sessions per user (chat logs stored in database)

GPT-4o support (text and image input)

Image upload and visual analysis (for GPT-4o)

Secure secret management with Streamlit Cloud’s secrets

Fast, modern UI

🌐 Deployment
1. Requirements

Python 3.8+

Streamlit Community Cloud (or local run)

PostgreSQL database (for chat logs and users)

2. Installation

bash
git clone https://github.com/Becho-png/chatbot.git
cd chatbot
pip install -r requirements.txt
3. Running locally

Create a file at .streamlit/secrets.toml with your credentials:

OPENAI_API_KEY = "your-openai-key"
NEON_DB_URL = "your-neon-or-postgresql-connection-url"

Start the app:

bash
streamlit run app.py
4. Deploying to Streamlit Cloud

Push your repo to GitHub (public).

Go to streamlit.io/cloud, click “New app,” select your repo.

Add your secrets from the Streamlit Cloud “Secrets” UI.

Deploy!

📂 Project Structure

streamlit_app.py
requirements.txt
README.md

🧑‍💻 Credits

Developed by Becho-png
Uses Streamlit and OpenAI GPT-4o

🇹🇷 Türkçe Kısa Açıklama
Bu proje, OpenAI GPT-4o destekli çoklu oturumlu bir chatbot web uygulamasıdır. Kullanıcı kayıt/giriş, sohbet geçmişi, görsel yükleme ve analiz gibi modern özellikler içerir. Tüm veriler PostgreSQL’de saklanır ve Streamlit Cloud’da kolayca yayınlanabilir.

