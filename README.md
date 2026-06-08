<!-- Aryan Varshney GitHub Profile README -->

<h1 align="center">Namaste 🙏🏼 , I'm Aryan Varshney</h1>
<h3 align="center">🚀 AI Tools Creator | AI/ML Dev | Django, FastAPI & Flutter Dev | B.Tech CSE @ JIIT | 🇮🇳</h3>

<p align="center">
  <a href="https://aryan-varshney.vercel.app/" target="_blank">
    <img src="https://img.shields.io/badge/Portfolio-Visit%20My%20Website-0A66C2?style=for-the-badge&logo=vercel&logoColor=white" alt="Portfolio Website">
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

- Developed a real-time AI booth assistant for a college fest (JIIT Converge'26) that identifies attendees via FAISS-based cosine-similarity search over Facenet512 face embeddings and delivers fully personalized spoken responses through a conversational pipeline, with average face recognition latency of **10ms per frame**.
- Built an end-to-end voice pipeline (Sarvam AI Speech-to-Text → LLaMA 3.3-70B → Sarvam AI Text-to-Speech over WebSocket) with streaming audio playback that begins speaking within **~0.4 seconds** of the first audio chunk arriving.
- Engineered concurrent execution using Python's `ProcessPoolExecutor` to run face recognition in an isolated process alongside live camera capture (OpenCV) and a Silero VAD audio thread, ensuring smooth, non-blocking operation.

---

#### 📈 Stock Market Voice

*Python, Sarvam AI, Groq, Twilio, Silero VAD*

**Stock Market Voice**, an AI-powered voice calling system for brokers that schedules and initiates automated calls to clients, delivering personalized daily stock purchase summaries with real-time conversational interaction.

- Architected an end-to-end voice pipeline (Speech-to-Text → LLaMA 3.3-70B → Text-to-Speech) integrated with **Silero VAD** for speech detection, enabling **1–2s response latency** from speech input to spoken reply over calls.
- Leveraged Twilio for scalable call automation and broker APIs for dynamic retrieval of client-specific stock data, supporting multi-user calling and seamless callback-based query handling.

---

#### 🔥 [Customer Recovery Automation](https://www.linkedin.com/posts/aryan-varshney-392446310_ai-automation-n8n-activity-7466010657302269953-WXOl?utm_source=share&utm_medium=member_desktop)

*n8n, Twilio, Sarvam AI, Gemini, Python*

**Customer Recovery Automation**, an AI-powered customer recovery workflow that transforms vague negative reviews into actionable business insights through intelligent voice conversations.

- Built an intelligent review analysis pipeline that detects negative and unclear customer feedback, then automatically triggers personalized AI voice calls to gather detailed feedback through natural conversations.
- Integrated a multi-stack voice system using **Twilio for calling**, **Sarvam AI for STT & TTS**, and **Gemini AI for review analysis**, orchestrated seamlessly through **n8n workflows**.
- Engineered an AI-driven escalation logic system where the workflow autonomously decides when to escalate for human intervention, transforming passive feedback analysis into proactive customer recovery.

---

#### 😴 [Sleep Debt Predictor](https://github.com/AryanV-Coder/SleepDebtPredictor) ([Live Demo](https://sleep-debt-predictor.vercel.app/))

*Python, FastAPI, Scikit-learn, Linear Regression*

**Sleep Debt Predictor**, a web-based ML system that estimates user sleep debt by analyzing facial fatigue indicators (eye redness, dark circles, yawn frequency) captured via a real-time browser video input.

- Trained a Scikit-learn Linear Regression model on a self-collected dataset, achieving **R² 0.87**, **MAE 0.80 hours**, and **RMSE 1.02** on the test split, enabling accurate and interpretable sleep debt estimation.
- Built an end-to-end pipeline integrating a FastAPI backend with Google Gemini API for feature extraction, and implemented Web Speech API for AI-generated personalized voice feedback.

---

#### 🕵️ [Spy AI](https://github.com/AryanV-Coder/SpyAI)

*Flutter, FastAPI, Dart, Python, Gemini, PostgreSQL*

**Spy AI**, an AI-powered full-stack mobile app using **Flutter** (Dart) frontend and **FastAPI** (Python) backend that turns your phone into a searchable, lifelong memory by recording and indexing meetings in real time.

- Implemented a background recorder with real-time audio capture, transcription pipeline, structured database storage and **full-text search**; integrated a **Gemini 2.5 Flash-powered** chatbot to surface summaries, exact quotes, timestamps and context on demand across past conversations.
- Delivered end-to-end production features including secure storage, privacy controls, meeting-level metadata, and cross-platform deployment—empowering users to recall details, verify claims, and track decisions.

---

#### 📞 [AI Calling](https://github.com/AryanV-Coder/AICalling)

*Flask, Html, Twilio, Gemini*

**AI Calling**, a full-stack voice-first application with an **HTML** frontend and **Flask** backend that enables natural, real-time phone conversations with an **AI** assistant.

- Integrated telephony providers and built real-time **speech-to-text** and **text-to-speech** pipelines, plus automated call initiation to allow users to talk directly to an LLM-driven agent over phone calls.
- Implemented an **emergency auto-call** feature to send urgent voice messages when users cannot place calls manually, and delivered secure call handling and scalable backend services.

---

#### 🍽️ [Flavor Match](https://github.com/AryanV-Coder/FlavorMatch) ([Live Demo](https://flavor-match-aat.vercel.app/))

*FastAPI, Gemini, Html, CSS, JavaScript*

**Flavor Match**, a full-stack family food recommendation web app using **HTML/CSS** and **JavaScript** on the frontend with a **FastAPI + PostgreSQL** backend; deployed a live demo on **Vercel**.

- Designed and implemented a normalized relational schema (Family → Member → Food) applying **primary/foreign keys, UNIQUE/NOT NULL** constraints and cascade operations, with timestamped logs.
- Implemented streamlined family/member registration and daily food-logging flows, plus an **SQL-driven recommendation pipeline** (rule-based / lightweight AI) to deliver personalized meal suggestions.

---

### 🛠️ Tech Stack

**Languages**  
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-007396?style=flat-square&logo=openjdk&logoColor=white)
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
![Google Gemini](https://img.shields.io/badge/Gemini-8F7500?style=flat-square&logo=google)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai)

---

### 📫 Connect with Me

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/aryan-varshney-392446310/)  

---

## 📊 GitHub Stats

<div align="center">

### ⭐ My Performance

<table>
  <tr>
    <td align="center" width="50%">
      <img src="https://github-readme-stats-sigma-five.vercel.app/api?username=AryanV-Coder&show_icons=true&include_all_commits=true&count_private=true&theme=tokyonight&bg_color=0D1117&title_color=58A6FF&text_color=C9D1D9&icon_color=79C0FF&border_color=30363D&border_radius=10" alt="GitHub Stats" />
    </td>
    <td align="center" width="50%">
      <img src="https://github-readme-stats-sigma-five.vercel.app/api/top-langs/?username=AryanV-Coder&layout=compact&include_all_commits=true&count_private=true&theme=tokyonight&bg_color=0D1117&title_color=58A6FF&text_color=C9D1D9&border_color=30363D&border_radius=10" alt="Top Languages" />
    </td>
  </tr>
</table>

</div>

<div align="center">

### 🔥 Contribution Streak

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://streak-stats.demolab.com?user=AryanV-Coder&theme=dark&hide_border=false&border_radius=10&date_format=M%20j%5B%2C%20Y%5D&background=0D1117&stroke=58A6FF&ring=58A6FF&fire=FF7E34&currStreakNum=C9D1D9&currStreakLabel=58A6FF&sideNums=C9D1D9&sideLabels=58A6FF&dates=C9D1D9" />
  <source media="(prefers-color-scheme: light)" srcset="https://streak-stats.demolab.com?user=AryanV-Coder&theme=subtle&hide_border=false&border_radius=10&date_format=M%20j%5B%2C%20Y%5D" />
  <img alt="GitHub Streak" src="https://streak-stats.demolab.com?user=AryanV-Coder&theme=dark&hide_border=false&border_radius=10&date_format=M%20j%5B%2C%20Y%5D&background=0D1117&stroke=58A6FF&ring=58A6FF&fire=FF7E34&currStreakNum=C9D1D9&currStreakLabel=58A6FF&sideNums=C9D1D9&sideLabels=58A6FF&dates=C9D1D9" />
</picture>

### 📅 Contribution Activity

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-activity-graph.vercel.app/graph?username=AryanV-Coder&bg_color=0D1117&color=58A6FF&line=58A6FF&point=79C0FF&area=true&hide_border=false&custom_title=Aryan's%20GitHub%20Contribution%20Graph&title_color=58A6FF&area_color=58A6FF" />
  <source media="(prefers-color-scheme: light)" srcset="https://github-readme-activity-graph.vercel.app/graph?username=AryanV-Coder&bg_color=FFFFFF&color=000000&line=0969DA&point=0969DA&area=true&hide_border=true&custom_title=Aryan's%20GitHub%20Contribution%20Graph" />
  <img alt="Contribution Graph" src="https://github-readme-activity-graph.vercel.app/graph?username=AryanV-Coder&bg_color=0D1117&color=58A6FF&line=58A6FF&point=79C0FF&area=true&hide_border=false&custom_title=Aryan's%20GitHub%20Contribution%20Graph&title_color=58A6FF&area_color=58A6FF" />
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
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&height=100&section=footer&text=Code%20for%20the%20Nation.%20Code%20for%20the%20Future.%20🇮🇳&fontSize=16&fontColor=fff&animation=fadeIn&descSize=20" />
</div>
