# 🏥 Hospital Chatbot

A smart and ethical chatbot designed to assist users with common hospital-related queries. This chatbot combines a rule-based architecture and Google Gemini AI to deliver accurate, context-aware, and reliable responses. Built with **Python** and **Streamlit**, the chatbot offers an intuitive web interface suitable for hospital websites or internal systems.

---

## 🧠 Features

- **Rule-Based Engine**: Uses a pre-defined knowledge base to handle frequent and specific hospital-related questions.
- **AI Integration**: Connects to **Google Gemini AI** for intelligent and dynamic response generation beyond rule-based capabilities.
- **Medical Ethics Compliance**: Ensures all interactions align with basic healthcare ethical standards — no diagnoses, no sharing of personal medical data, and clear disclaimers.
- **Streamlit Frontend**: Lightweight, fast, and user-friendly interface for seamless interactions.

---

## 🚀 Technologies Used

| Tool/Library     | Purpose                          |
|------------------|----------------------------------|
| Python           | Backend logic and AI integration |
| Streamlit        | Web-based frontend UI            |
| Google Gemini AI | Advanced natural language responses |
| JSON/Dict        | Rule-based knowledge base        |

---

## 📁 Project Structure

```bash
hospital-chatbot/
│
├── chatbot.py             # Core logic for rule-based and AI responses
├── config.py    # Custom question-answer dataset
├── app.py                 # Streamlit frontend
├── requirements.txt       # Dependencies
└── README.md              # Project documentation

## ⚙️ Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/hospital-chatbot.git
cd hospital-chatbot
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
pip install -r requirements.txt
export GEMINI_API_KEY="your_api_key_here"
streamlit run app.py
```

## 🧪 Sample Questions You Can Try

- "What are the visiting hours?"
- "How can I book an appointment?"
- "Where is the emergency unit located?"
- "Tell me about your maternity services."

---

## ⚖️ Ethical Considerations

This chatbot adheres to healthcare standards by:

- Not giving medical advice or diagnoses.  
- Encouraging users to consult licensed professionals.  
- Handling user data with confidentiality (no PII storage).  
- Presenting AI responses with disclaimers where necessary.

---

## 📌 Future Improvements

- Integration with hospital booking systems or EMR  
- Multilingual support  
- Voice interaction support  
- Real-time handoff to human agents

---

## 🤝 Contributions

Feel free to fork, clone, and improve the chatbot. Pull requests are welcome!

---

## 📄 License

This project is licensed under the **MIT License**.

---

## 🙏 Acknowledgments

- Streamlit for the frontend framework  
- Google Gemini for AI response generation  
- OpenAI & developer communities for inspiration
