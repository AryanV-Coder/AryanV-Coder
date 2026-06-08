<!-- Aryan Varshney GitHub Profile README -->

<h1 align="center">Namaste 🙏🏼 , I'm Aryan Varshney</h1>
<h3 align="center">🚀 AI Tools Creator | AI/ML Dev | Django, FastAPI & Flutter Dev | B.Tech CSE @ JIIT | 🇮🇳</h3>

<p align="center">
  <a href="https://aryan-varshney.vercel.app/" target="_blank">
    <img src="https://img.shields.io/badge/Portfolio-Visit%20My%20Website-blue?style=for-the-badge&logo=vercel&logoColor=white" alt="Portfolio Website">
  </a>
</p>

---

<img align="right" alt="Coding" width="400" src="https://user-images.githubusercontent.com/74038190/229223263-cf2e4b07-2615-4f87-9c38-e37600f8381a.gif">

### 💡 About Me

- 🎓 Computer Science student at **JIIT Noida** (2024–28)
- 💻 I love building intelligent systems that **interact, automate, and improve lives**
- 🔬 Exploring **AI agents, automation, FastAPI, Flutter**, and **AI APIs**
- 🇮🇳 Mission-driven to use tech for **India's advancement in defense and wellness**
- 🧪 Constantly experimenting with **AI, ML, automation, and hardware integration**

---

### 🧩 Featured Projects

#### 🌬️ [Vayu — Interactive Face Recognition Bot](https://github.com/AryanV-Coder/Vayu-InteractiveFaceRecognitionBot)

*Python, OpenCV, DeepFace (Facenet512), FAISS, SQLite, Silero VAD, Groq LLaMA, Sarvam STT/TTS*

**Vayu**, an interactive face recognition bot that **recognizes faces** via FAISS embeddings and runs a **personalized, streaming voice conversation** pipeline (STT → LLM → TTS).

- Developed a real-time AI booth assistant for a college fest (JIIT Converge'26) that identifies attendees via FAISS-based cosine-similarity search over Facenet512 face embeddings and delivers fully personalized conversations
- Built an end-to-end voice pipeline (Sarvam AI Speech-to-Text → LLaMA 3.3-70B → Sarvam AI Text-to-Speech over WebSocket) with streaming audio playback that begins speaking within **~0.4 seconds**
- Engineered concurrent execution using Python's `ProcessPoolExecutor` to run face recognition in an isolated process alongside live camera capture (OpenCV) and a Silero VAD audio thread, ensuring smooth real-time operation

---

#### 📈 Stock Market Voice

*Python, Sarvam AI, Groq, Twilio, Silero VAD*

**Stock Market Voice**, an AI-powered voice calling system for brokers that schedules and initiates automated calls to clients, delivering personalized daily stock purchase summaries with real-time conversation handling.

- Architected an end-to-end voice pipeline (Speech-to-Text → LLaMA 3.3-70B → Text-to-Speech) integrated with **Silero VAD** for speech detection, enabling **1–2s response latency** from speech input to synthesis
- Leveraged Twilio for scalable call automation and broker APIs for dynamic retrieval of client-specific stock data, supporting multi-user calling and seamless callback-based query handling

---

#### 📝 [Customer Recovery Automation Tool](https://www.linkedin.com/posts/aryan-varshney-392446310_ai-automation-n8n-activity-7466010657302269953-WXOl?utm_source=share&utm_medium=member_desktop&rcm=ACoAAE8WXp4BgI2VsM4AocmLbTP2t3RwvE585ao)

*n8n, Twilio, Sarvam AI, Gemini, Python*

**Customer Recovery Automation Tool**, an AI-powered customer recovery workflow that transforms vague negative reviews into actionable business insights through intelligent voice conversations.

- Built an intelligent review analysis pipeline that detects negative and unclear customer feedback, then automatically triggers personalized AI voice calls to gather detailed feedback through natural, human-like conversations
- Integrated a multi-stack voice system using **Twilio for calling**, **Sarvam AI for STT & TTS**, and **Gemini AI for review analysis**, orchestrated seamlessly through **n8n workflows**
- Engineered an AI-driven escalation logic system where the workflow autonomously decides when to escalate for human intervention, transforming passive feedback analysis into proactive customer recovery actions

---

#### 😴 [Sleep Debt Predictor](https://github.com/AryanV-Coder/SleepDebtPredictor) ([Live Demo](https://sleep-debt-predictor.vercel.app/))

*Python, FastAPI, Scikit-learn, Linear Regression*

**Sleep Debt Predictor**, a web-based ML system that estimates user sleep debt by analyzing facial fatigue indicators (eye redness, dark circles, yawn frequency) captured via a real-time browser video feed.

- Trained a Scikit-learn Linear Regression model on a self-collected dataset, achieving **R² 0.87**, **MAE 0.80 hours**, and **RMSE 1.02** on the test split
- Built an end-to-end pipeline integrating a FastAPI backend with Google Gemini API for feature extraction, and implemented Web Speech API for AI-generated personalized voice feedback

---

#### 🕵🏻‍♂️ [Spy AI](https://github.com/AryanV-Coder/SpyAI)

*Flutter, FastAPI, Dart, Python, Gemini, PostgreSQL*

**Spy AI**, an AI-powered full-stack mobile app using **Flutter** (Dart) frontend and **FastAPI** (Python) backend that turns your phone into a searchable, lifelong memory by recording and indexing meetings.

- Implemented a background recorder with real-time audio capture, transcription pipeline, structured database storage and **full-text search**; integrated a **Gemini 2.5 Flash-powered** chatbot to surface insights instantly
- Delivered end-to-end production features including secure storage, privacy controls, meeting-level metadata, and cross-platform deployment—empowering users to recall details, verify claims, and unlock institutional knowledge

---

#### 📞 [AI Calling](https://github.com/AryanV-Coder/AICalling)

*Flask, Html, Twilio, Gemini*

**AI Calling**, a full-stack voice-first application with an **HTML** frontend and **Flask** backend that enables natural, real-time phone conversations with an **AI** assistant.

- Integrated telephony providers and built real-time **speech-to-text** and **text-to-speech** pipelines, plus automated call initiation to allow users to talk directly to an LLM-driven agent over phone
- Implemented an **emergency auto-call** feature to send urgent voice messages when users cannot place calls manually, and delivered secure call handling and scalable backend services

---

#### 🍽️ [Flavor Match](https://github.com/AryanV-Coder/FlavorMatch) ([Live Demo](https://flavor-match-aat.vercel.app/))

*FastAPI, Gemini, Html, CSS, JavaScript*

**Flavor Match**, a full-stack family food recommendation web app using **HTML/CSS** and **JavaScript** on the frontend with a **FastAPI + PostgreSQL** backend; deployed a live demo on **Vercel**.

- Designed and implemented a normalized relational schema (Family → Member → Food) applying **primary/foreign keys, UNIQUE/NOT NULL** constraints and cascade operations, with timestamped logs
- Implemented streamlined family/member registration and daily food-logging flows, plus an **SQL-driven recommendation pipeline** (rule-based / lightweight AI) to deliver personalized meal suggestions

---

### 🛠️ Tech Stack

**Languages**  
![Python](https://img.shields.io/badge/Python-blue?style=flat-square&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-orange?style=flat-square&logo=openjdk&logoColor=white)
![Dart](https://img.shields.io/badge/Dart-0175C2?style=flat-square&logo=dart&logoColor=white)
![C](https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=c%2B%2B&logoColor=white)

**Frameworks & Tools**  
![Django](https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat-square&logo=spring-boot&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)

**AI & APIs**  
![Google Gemini](https://img.shields.io/badge/Gemini-000000?style=flat-square&logo=google)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai)

---

### 📫 Connect with Me

[![LinkedIn](https://img.shields.io/badge/LinkedIn-blue?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/aryan-varshney-392446310/)  

---

## 📊 GitHub Stats

<div align="center">

<a href="https://github.com/AryanV-Coder">
  <img height=200 align="center" src="https://github-readme-stats-sigma-five.vercel.app/api?username=AryanV-Coder&show_icons=true&include_all_commits=true&count_private=true&theme=react&title_color=FF9933&icon_color=138808&text_color=138808&bg_color=0,fff8f0,ffffff,f0fff4&border_color=FF9933" alt="GitHub Stats">
</a>
&nbsp;&nbsp;
<a href="https://github.com/AryanV-Coder">
  <img height=200 align="center" src="https://github-readme-stats-sigma-five.vercel.app/api/top-langs/?username=AryanV-Coder&layout=compact&include_all_commits=true&count_private=true&theme=react&title_color=FF9933&text_color=138808&bg_color=0,fff8f0,ffffff,f0fff4&border_color=138808" alt="Top Languages">
</a>

</div>

<div align="center">

### 🔥 Contribution Streak

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://streak-stats.demolab.com?user=AryanV-Coder&theme=transparent&hide_border=false&border_radius=5&date_format=M%20j%5B%2C%20Y%5D&ring=FF9933&fire=FF9933&currStreakLabel=138808&sideLabels=138808&dates=138808&currStreakNum=FF6600&sideNums=FF6600&background=0%2Cfff8f0%2Cffffff%2Cf0fff4&border=FF9933">
  <source media="(prefers-color-scheme: light)" srcset="https://streak-stats.demolab.com?user=AryanV-Coder&theme=transparent&hide_border=false&border_radius=5&date_format=M%20j%5B%2C%20Y%5D&ring=FF9933&fire=FF9933&currStreakLabel=138808&sideLabels=138808&dates=138808&currStreakNum=FF6600&sideNums=FF6600&background=0%2Cfff8f0%2Cffffff%2Cf0fff4&border=FF9933">
  <img alt="GitHub Streak" src="https://streak-stats.demolab.com?user=AryanV-Coder&theme=transparent&hide_border=false&border_radius=5&date_format=M%20j%5B%2C%20Y%5D&ring=FF9933&fire=FF9933&currStreakLabel=138808&sideLabels=138808&dates=138808&currStreakNum=FF6600&sideNums=FF6600&background=0%2Cfff8f0%2Cffffff%2Cf0fff4&border=FF9933">
</picture>

</div>

### 📅 Contribution Activity
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-activity-graph.vercel.app/graph?username=AryanV-Coder&bg_color=ffffff&color=000080&line=ff9933&point=138808&area=true&hide_border=false&custom_title=Contribution%20Graph">
  <source media="(prefers-color-scheme: light)" srcset="https://github-readme-activity-graph.vercel.app/graph?username=AryanV-Coder&bg_color=ffffff&color=000080&line=ff9933&point=138808&area=true&hide_border=false&custom_title=Contribution%20Graph">
  <img alt="Contribution Graph" src="https://github-readme-activity-graph.vercel.app/graph?username=AryanV-Coder&bg_color=ffffff&color=000080&line=ff9933&point=138808&area=true&hide_border=false&custom_title=Contribution%20Graph">
</picture>

</div>

---

<div align="center">

  <h3>💡 Empowering Ideas with Intelligence</h3>
  <strong>✨ Building for Impact. Innovating for Bharat. ✨</strong>

  <br><br>

  <em>Crafted with 💻 logic, ☕ passion, and 🇮🇳 heart</em>

</div>

---

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=24&height=100&section=footer&text=Code+for+the+Nation.+Code+for+the+Future.+🇮🇳&fontSize=20&fontColor=ffffff">
</div>
