<h1 align="center">Yash Dhokane</h1>
<h3 align="center">AI Engineer · LLMs · RAG · Voice AI Agents · MCP · Computer Vision</h3>

<p align="center">
  <a href="https://www.linkedin.com/in/yash-dhokane-3a914821b"><img src="https://img.shields.io/badge/LinkedIn-Yash%20Dhokane-0A66C2?logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <img src="https://img.shields.io/badge/Based%20in-Edinburgh%2C%20UK-2E3440" alt="Edinburgh, UK">
  <img src="https://img.shields.io/badge/MSc-Artificial%20Intelligence%20·%20Heriot--Watt-8A2BE2" alt="MSc AI">
</p>

---

I build **AI systems end to end**: retrieval-augmented LLM applications, real-time voice agents, tool-using agents built on the Model Context Protocol, and applied machine learning and computer vision. I came to AI from building and running production software, so I care about the parts that make AI work outside a notebook: clean APIs, guardrails, latency, privacy and maintainable code.

- 🤖 **Now:** AI Engineer at **BlinkBag**, and studying for an **MSc in Artificial Intelligence at Heriot-Watt University** (BCS-accredited, finishing May 2027)
- 🔬 **Researching:** do ML models struggle on the same lung nodules that radiologists disagree on? (LIDC-IDRI, CT imaging)
- 🛠️ **Background:** full-stack and backend engineering on production web platforms, including the MCP integrations that connected them to AI assistants
- 🎯 **Open to:** AI / ML / GenAI Engineer roles in the UK from May 2027

## Featured projects

| Project | What it shows |
|---|---|
| 🎙️ **[AI Voice Customer Support Agent](https://github.com/yashdhokane/AI-Human-Voice-Support)** | Real-time speech-to-speech agent: VAD → Vosk ASR → **RAG over Pinecone** → **Llama 3.1 (Ollama)** → neural TTS, with guardrailed **live human handoff over LiveKit/WebRTC** |
| 🔌 **[Custom MCP Servers for AI Agents](https://github.com/yashdhokane/Custom-MCP-Server-for-Weather-Data-HR-Modules)** | Model Context Protocol tools that let Claude query live weather, job applications and interview schedules; Zod-validated, one service per capability |
| 📄 **[AI Resume Analyzer & Job Matcher](https://github.com/yashdhokane/ai_resume_analyzer)** | Semantic CV–job matching with **Sentence Transformers** and chunked embeddings for long documents, plus an ATS-style keyword gap; privacy-first, nothing stored |
| 🧠 **[AI Text Summarizer](https://github.com/yashdhokane/ai_text_summarizer)** | Abstractive summarization with **BART** (Hugging Face) and map-reduce chunking for documents beyond the model's context window |
| 🚗 **[Lane Detection System](https://github.com/yashdhokane/lane_assist_system)** | Classical computer-vision pipeline in **OpenCV**: Canny, region-of-interest mask, Hough transform and slope-based lane averaging on dashcam video |
| 📊 **[ML internship projects](https://github.com/yashdhokane/LGMVIP-DataScience)** | LSTM next-word prediction, classifier comparison and decision trees, plus [linear regression](https://github.com/yashdhokane/TheSparkFoundation-INTERN) |

## Tech stack

**AI / ML**
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-D00000?style=flat-square&logo=keras&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging%20Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)
![NLTK](https://img.shields.io/badge/NLTK-154F5B?style=flat-square)
![pandas](https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)

**LLMs and agents**
![Ollama](https://img.shields.io/badge/Ollama%20·%20Llama%203.1-000000?style=flat-square&logo=ollama&logoColor=white)
![RAG](https://img.shields.io/badge/RAG-Retrieval%20Augmented%20Generation-6E56CF?style=flat-square)
![Pinecone](https://img.shields.io/badge/Pinecone-Vector%20DB-1C17FF?style=flat-square)
![MCP](https://img.shields.io/badge/Model%20Context%20Protocol-MCP-6E56CF?style=flat-square)
![Sentence Transformers](https://img.shields.io/badge/Sentence%20Transformers-embeddings-FFD21E?style=flat-square)
![Prompt Engineering](https://img.shields.io/badge/Prompt%20Engineering-guardrails-2E3440?style=flat-square)

**Speech and real-time**
![Vosk](https://img.shields.io/badge/Vosk-ASR-4B8BBE?style=flat-square)
![Silero VAD](https://img.shields.io/badge/Silero-VAD-EE4C2C?style=flat-square)
![LiveKit](https://img.shields.io/badge/LiveKit-WebRTC-FF6352?style=flat-square)
![edge-tts](https://img.shields.io/badge/Neural-TTS-0078D4?style=flat-square)

**Engineering**
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white)
![REST APIs](https://img.shields.io/badge/REST%20APIs-005571?style=flat-square)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05033?style=flat-square&logo=git&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white)

## How I build AI systems

- **Ground the model.** Retrieval first, and generation only from what was retrieved. If confidence is low, say so or hand off.
- **Guardrails before generation.** Deterministic checks for escalation, safety and scope run before any LLM call.
- **Privacy by default.** Local models where possible, no stored personal data, secrets only in the environment.
- **Measure, then optimise.** Clear metrics (accuracy, retrieval score, latency) before any tuning.

## Let's connect

I'm happy to talk about LLM applications, voice AI, agents and MCP, or applied ML in healthcare imaging. The best way to reach me is **[LinkedIn](https://www.linkedin.com/in/yash-dhokane-3a914821b)**.
