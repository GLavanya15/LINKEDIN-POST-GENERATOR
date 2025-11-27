# 🌟 LinkedIn Post Generator — Generative AI Powered Content Creator 

🚀Generate professional, context-aware LinkedIn posts in seconds.

This project is a Generative AI–powered LinkedIn Post Generator designed to help users create engaging, polished, and professional LinkedIn posts with minimal input.  
It eliminates the effort of drafting posts manually by using a Large Language Model (LLM) to produce high-quality content tailored to user preferences.

🔗 **Live App:** [LinkedIn Post Generator](https://linkedin-post-generator-xyz.streamlit.app)

---

## 🎯 Project Aim
To design and develop a Generative AI-based system that automatically creates context-aware, professional LinkedIn posts using only minimal user inputs.

---

## ✨ Features

### 📝 Customizable Post Generation
Users can generate posts based on:
- **Topic:** Career Goals, Job Search, Skills, LinkedIn Tips, Motivation, Mental Health, Personal Growth, etc.  
- **Length:** Short, Medium, Long  
- **Language:** English, Hinglish  

### 🤖 LLM-Powered Content Creation
- Uses a Large Language Model (LLM) to generate polished, structured, and engaging LinkedIn-ready content.  
- Ensures clarity, personalization, and professional tone.  

### ⚡ Fast and Efficient
- Generates posts in seconds  
- Reduces time and effort needed to create impactful content  
- Helps users maintain consistency on LinkedIn  

---

## 🛠️ Tech Stack

| Component   | Technology |
|-------------|------------|
| Frontend    | Streamlit  |
| Backend     | Python     |
| AI Model    | Groq LLM (via ChatGroq) |
| Frameworks  | LangChain, Streamlit, Groq API |
| Deployment  | Streamlit Cloud |

---

## 📦 Project Structure
```
├── main.py # Streamlit UI & flow 
├── requirements.txt # Dependencies 
├── data/ 
│ ├── llm_helper.py # LLM initialization & API calls 
│ └── post_generator.py # Core function to generate posts 
└── README.
```
---

## ⚙️ How It Works
1. User selects topic, language, and post length  
2. User enters a short prompt/description  
3. System sends the inputs to the LLM  
4. LLM generates a high-quality LinkedIn post  
5. Output is displayed with formatting and copy options  

---
## 🚀 Deployment
Deployed using Streamlit Community Cloud.

### Steps:
1. Push project to GitHub
2. Go to Streamlit Cloud → New app
3. Select repo & branch
4. Add GROQ_API_KEY under Secrets
5. Deploy 🚀
---
## 🔒 Environment Variables (Secrets)
Add this in Streamlit → Settings → Secrets:
```ini
GROQ_API_KEY = "your_groq_api_key_here"
```

---
## 📥 Installation (Local Setup)

```bash
git clone https://github.com/GLavanya15/LINKEDIN-POST-GENERATOR.git
cd LINKEDIN-POST-GENERATOR
pip install -r requirements.txt
streamlit run main.py
```
