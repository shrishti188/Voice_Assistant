# 🗣️ Voice Command Shopping Assistant (Multilingual NLP)

This is a Django-based voice-controlled shopping assistant web app that accepts natural language input (speech or text) and returns useful shopping commands.

🔊 Powered by:
- ✅ Django (Backend & Admin)
- ✅ NLP using [spaCy](https://spacy.io/) (Local only)
- ✅ Translation using `googletrans`
- ✅ Deployed on [PythonAnywhere](https://www.pythonanywhere.com)

---

## 🚀 Live Demo (Hindi-only version)

👉 Try the **live deployed app** here (basic features + Hindi translation only):  
🔗 [https://shrishtiisharma.pythonanywhere.com]

> Note: The deployed version does not support spaCy-based NLP due to hosting limitations.

---

## 💻 Run Locally (with NLP & Multilingual Support)

If you want the **full experience** with English + multilingual translation and NLP features (like intent parsing), run the project locally.

### 🛠️ Setup Instructions

1. **Clone the repository:**

```bash
git clone https://github.com/shrishti188/voice-assistant-deployment.git
cd voice-assistant-deployment

*2. Create and activate a virtual environment:

python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

*3. Install dependencies:

pip install -r requirements.txt

*4. Run the server:

python manage.py runserver

*5. Open your browser at http://127.0.0.1:8000



🧠 Technologies Used
Python 3.10

Django 5.1.6

spaCy (for NLP)

Googletrans (for translation)

PostgreSQL (production-ready DB support)

Gunicorn & Whitenoise (for deployment)


🤝 Contributing
Pull requests are welcome! If you want to improve NLP logic or add UI features, feel free to fork and send PRs.

📜 License
This project is licensed under the MIT License.
See the LICENSE file for more details.



Made with ❤️ by Shrishti Sharma