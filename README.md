# 🐛 AI Code Debugger

An AI-powered code bug fixer using Flask and OpenAI API — detects errors and returns fixes with natural language explanations.

---

## ✨ Features
- Paste any code and get instant bug detection
- AI explains the error in plain English
- Suggests a fixed version of the code
- Usage tracking per session
- Stripe payment integration for premium access

---

## 📁 Project Structure
ai-code-debugger/
├── app.py              # Flask backend + OpenAI logic
├── index.html          # Main debugger interface
├── charger.html        # Onboarding page
├── payment.html        # Stripe payment page
├── app.db              # SQLite database
├── requirements.txt    # Python dependencies
├── .gitignore
└── .env                # API keys (not tracked)---

## 🚀 Getting Started

### 1. Clone the repo
git clone https://github.com/khadigaah/ai-code-debugger.git
cd ai-code-debugger### 2. Install dependencies
pip install -r requirements.txt### 3. Set up your .env file
OPENAI_API_KEY=your_openai_key_here
STRIPE_SECRET_KEY=your_stripe_key_here### 4. Run the app
python app.py---

## 🛠️ Tech Stack
| Layer | Tech |
|-------|------|
| Backend | Python / Flask |
| AI | OpenAI API |
| Database | SQLite |
| Payments | Stripe |
| Frontend | HTML / CSS / JS |

---

## 🔒 Security
- API keys stored in .env only
- .env is excluded via .gitignore

---

*Built by [@khadigaah](https://github.com/khadigaah)*
