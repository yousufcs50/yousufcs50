## Mohammad Yousuf

**AI engineer building production LLM systems.**

I work on retrieval-augmented generation pipelines, LLM evaluation, fine-tuning and agent workflows, and on the deployment side that turns any of it into something that survives real traffic. Before that, computer vision and classical ML.

Most of what interests me sits at the seams: the option that gets silently dropped, the retrieval step that quietly returns nothing useful, the model that behaves differently the moment it leaves the notebook.

Open to projects and partnerships.

<p>
  <a href="https://yousufcs50.github.io"><img src="https://img.shields.io/badge/Portfolio-yousufcs50.github.io-222222?style=for-the-badge&logo=githubpages&logoColor=white" alt="Portfolio"></a>
  <a href="mailto:yousuf@cloudqrgen.com"><img src="https://img.shields.io/badge/Email-yousuf%40cloudqrgen.com-0A66C2?style=for-the-badge" alt="Email"></a>
</p>

---

### What I work on

| Area | |
| :--- | :--- |
| **Retrieval** | RAG pipelines, embeddings, chunking and retrieval quality |
| **Evaluation** | Real-time LLM evaluation, hallucination and relevance monitoring |
| **Fine-tuning** | LoRA and QLoRA for domain-specific models |
| **Agents** | Multi-step agent workflows and orchestration |
| **Vision** | Object detection and recognition, deployed rather than benchmarked |
| **Forecasting** | Time-series modelling for operational prediction |
| **Delivery** | Dockerised pipelines, CI/CD, real-time inference, multi-cloud |

---

### Open source

<img src="https://img.shields.io/badge/%E2%96%B2_vercel%2Fai-26k_stars-000000?style=for-the-badge&logo=vercel&logoColor=white" alt="vercel/ai">

**[#21178](https://github.com/vercel/ai/pull/21178) · fix(openai): warn when `reasoningSummary` is used with chat models**

Passing `reasoningSummary` to a Chat Completions model silently did nothing. The option belongs to the Responses API, so `parseProviderOptions` stripped it before the model ever saw it, which made the resulting behaviour hard to debug. The fix emits an explicit `unsupported` warning instead of failing quietly, and ships with a test, a docs update, and a changeset.

The kind of bug you only trip over by running these SDKs in anger.

---

### Public repositories

Most of my production work is closed source. What is public here is earlier computer vision and ML work, plus smaller experiments.

| Project | What it does | Built with |
| :--- | :--- | :--- |
| **[ChatGPT integration API](https://github.com/yousufcs50/chatgpt-integration-api)** | Flask service exposing OpenAI chat completion, with a Whisper transcription script | <img src="https://img.shields.io/badge/-Flask-000000?logo=flask&logoColor=white" height="20"> <img src="https://img.shields.io/badge/-OpenAI_API-412991" height="20"> |
| **[Social distancing detector](https://github.com/yousufcs50/social_distancing_detection_CNN)** | Detects people in video frames and flags pairs closer than a configured pixel distance | <img src="https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white" height="20"> <img src="https://img.shields.io/badge/-OpenCV-5C3EE8?logo=opencv&logoColor=white" height="20"> |
| **[Object detection](https://github.com/yousufcs50/Object-Detection)** | Bounding boxes and class probabilities in a single pass over street camera footage | <img src="https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white" height="20"> <img src="https://img.shields.io/badge/-YOLOv3-00FFFF?logo=yolo&logoColor=black" height="20"> |
| **[MLflow experiment tracking](https://github.com/yousufcs50/working_with_mlflow)** | Comparing model runs on the UCI bike sharing dataset through the MLflow UI | <img src="https://img.shields.io/badge/-MLflow-0194E2?logo=mlflow&logoColor=white" height="20"> |
| **[Reaction time tester](https://github.com/yousufcs50/reaction_time_game)** | F1-style reaction game with randomised timing and a persistent leaderboard | <img src="https://img.shields.io/badge/-Node.js-5FA04E?logo=nodedotjs&logoColor=white" height="20"> <img src="https://img.shields.io/badge/-SQLite-003B57?logo=sqlite&logoColor=white" height="20"> |

---

### Stack

**LLM and generative AI**

<p>
<img src="https://img.shields.io/badge/Claude-D97757?style=for-the-badge&logo=claude&logoColor=white">
<img src="https://img.shields.io/badge/LangGraph-1C3C3C?style=for-the-badge&logo=langgraph&logoColor=white">
<img src="https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white">
<img src="https://img.shields.io/badge/CrewAI-FF5A50?style=for-the-badge&logo=crewai&logoColor=white">
<img src="https://img.shields.io/badge/Hugging_Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black">
<img src="https://img.shields.io/badge/OpenAI_API-412991?style=for-the-badge">
</p>

**Machine learning**

<p>
<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white">
<img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white">
<img src="https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white">
<img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white">
<img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white">
<img src="https://img.shields.io/badge/MLflow-0194E2?style=for-the-badge&logo=mlflow&logoColor=white">
</p>

**Engineering and cloud**

<p>
<img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white">
<img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white">
<img src="https://img.shields.io/badge/Google_Cloud-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white">
<img src="https://img.shields.io/badge/Azure-0078D4?style=for-the-badge">
<img src="https://img.shields.io/badge/AWS-FF9900?style=for-the-badge">
<img src="https://img.shields.io/badge/Oracle_Cloud-F80000?style=for-the-badge">
<img src="https://img.shields.io/badge/CI%2FCD-4A4A4A?style=for-the-badge&logo=githubactions&logoColor=white">
</p>

**Languages**

<p>
<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white">
<img src="https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white">
<img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white">
</p>
