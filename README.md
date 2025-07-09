# 🧠 Riya – Your Generative AI Assistant

Riya is a youthful, dynamic, and intelligent AI assistant built using cutting-edge generative AI tools. Developed during a Gen AI Workshop, Riya demonstrates the power of modern NLP and multimodal frameworks to create interactive and human-like AI assistants.

## 🔥 Features

- 💬 Conversational chatbot (Gradio Interface)
- 🤖 Personality-driven assistant (Riya – 21-year-old AI)
- 🌐 Hosted on Hugging Face Spaces
- ✨ User-friendly UI with branding and responsive layout
- 🎓 Built with practical exposure to GenAI tools

## 🛠️ Tech Stack

- **Gradio** – for interactive frontend
- **OpenAI** – for large language model integration
- **Hugging Face** – deployment and model hosting
- **Google Colab** – prototyping and backend logic
- **LangChain** – (planned or integrated) for chaining LLM tasks
- **PlayHT** – for voice generation (optional or planned)

## 📚 What I Learned

- Basics of Gradio, OpenAI APIs, and Hugging Face Spaces
- End-to-end deployment of an AI assistant
- UI/UX design and customization
- Prompt engineering for better AI responses
- Project structuring and public portfolio sharing

## 📷 Screenshots

<img src="https://herobot.app/wp-content/uploads/2022/11/AI-bot-1.jpg" width="300" />

## 🧑‍💻 About Me

👋 Hi, I'm **Amulya**, and I built this project as part of a Gen AI workshop. Riya represents my first step into the world of AI assistants and GenAI applications.

Connect with me on [LinkedIn](https://linkedin.com/in/amulyapriyaeamani)  
Explore more on [GitHub](https://github.com/Amulyapriyaeamani)

## ❤️ Acknowledgments

- Built during **NxtWave GenAI Workshop**
- Special thanks to the mentors and workshop organizers

## 🔧 Setup Instructions

### 📁 Project Structure

- `hf_chatbot/` → Backend app for Hugging Face Space  
  - `app.py` – main Gradio + LangChain chatbot logic  
  - `requirements.txt` – dependencies (`gradio`, `langchain`, `openai`)

- `static_site/` → Frontend website  
  - `index.html` – includes `<gradio-app>` iframe  
  - `styles.css` – basic styling  
  - `script.js` – optional interactivity

---

### Add your OpenAI API key as a secret in Hugging Face Spaces:

1. Create a new **Gradio (Python)** Space on Hugging Face.
2. Upload files from `hf_chatbot/`.
3. Add your OpenAI API key under:
   - `Settings → Secrets`
   - Key: `OPENAI_API_KEY`
   - Value: *your actual API key from https://platform.openai.com*
4. Upload `app.py`, `requirements.txt`, and other necessary files.
5. The chatbot will auto-launch on build.

> 🛠️ **Note:** Without a valid OpenAI API key, the app will show an error or fail to respond.
## 🚀 Live Demo
👉 [Try on website](amulyaaichatbot.ccbp.tech)
👉 [Try Riya on Hugging Face](https://amulyaeamani-mygenaichatbot.hf.space)
> ⚠️ Currently shows error due to missing OpenAI API key.

## 🛡️ Notes

- Do **not** hardcode API keys in your code.
- Always use secret variables in Spaces or `.env` files for safety.

### Embed in Website:

```html
<gradio-app src="https://your-space-url.hf.space"></gradio-app>


  
