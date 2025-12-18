# AWS CCP Generative AI Chatbot

Practice AWS Certified Cloud Practitioner (CLF-C02) questions in a chatbot style.

## Features
- Chatbox input for free questions
- AI answers with multiple choice + explanation (OpenAI API)
- Rule-based fallback if no API key
- Lightweight and deployable on Streamlit Cloud

## How to Deploy
1. Upload `app.py` and `requirements.txt` to GitHub
2. Go to [Streamlit Cloud](https://streamlit.io/cloud)
3. Click "New App" → select your repo → main file: `app.py` → Deploy
4. (Optional) Add OpenAI API key in **Secrets**:
