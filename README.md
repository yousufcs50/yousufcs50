## Mohammad Yousuf

**Machine learning engineer working in applied AI and LLM systems.**

I build with Python and TypeScript, and I care about the unglamorous parts of AI systems: what happens when an option is silently ignored, when a model returns something unexpected, when the thing that worked in a notebook meets real input.

Open to freelance and contract work.

<p>
  <a href="https://yousufcs50.github.io"><img src="https://img.shields.io/badge/Portfolio-yousufcs50.github.io-222222?style=for-the-badge&logo=githubpages&logoColor=white" alt="Portfolio"></a>
  <a href="mailto:yousuf@cloudqrgen.com"><img src="https://img.shields.io/badge/Email-yousuf%40cloudqrgen.com-0A66C2?style=for-the-badge" alt="Email"></a>
</p>

---

### Open source

<img src="https://img.shields.io/badge/%E2%96%B2_vercel%2Fai-26k_stars-000000?style=for-the-badge&logo=vercel&logoColor=white" alt="vercel/ai">

**[#21178](https://github.com/vercel/ai/pull/21178) · fix(openai): warn when `reasoningSummary` is used with chat models**

Passing `reasoningSummary` to a Chat Completions model silently did nothing. The option belongs to the Responses API, so `parseProviderOptions` stripped it before the model ever saw it, which made the resulting behaviour hard to debug. The fix emits an explicit `unsupported` warning instead of failing quietly, and ships with a test, a docs update, and a changeset.

Continuing to contribute to the AI SDK.

---

### Selected work

| Project | What it does | Built with |
| :--- | :--- | :--- |
| **[Social distancing detector](https://github.com/yousufcs50/social_distancing_detection_CNN)** | Detects people in video frames and flags pairs standing closer than a set pixel distance | <img src="https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white" height="20"> <img src="https://img.shields.io/badge/-OpenCV-5C3EE8?logo=opencv&logoColor=white" height="20"> |
| **[Object detection](https://github.com/yousufcs50/Object-Detection)** | Bounding boxes and class probabilities predicted in a single pass over street camera footage | <img src="https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white" height="20"> <img src="https://img.shields.io/badge/-YOLOv3-00FFFF?logo=yolo&logoColor=black" height="20"> |
| **[ChatGPT integration API](https://github.com/yousufcs50/chatgpt-integration-api)** | Flask service exposing OpenAI chat completion, with a Whisper transcription script | <img src="https://img.shields.io/badge/-Flask-000000?logo=flask&logoColor=white" height="20"> <img src="https://img.shields.io/badge/-OpenAI_API-412991" height="20"> |
| **[Reaction time tester](https://github.com/yousufcs50/reaction_time_game)** | F1-style reaction game with randomised light timing and a persistent leaderboard | <img src="https://img.shields.io/badge/-Node.js-5FA04E?logo=nodedotjs&logoColor=white" height="20"> <img src="https://img.shields.io/badge/-SQLite-003B57?logo=sqlite&logoColor=white" height="20"> |
| **[MLflow experiment tracking](https://github.com/yousufcs50/working_with_mlflow)** | Comparing model runs on the UCI bike sharing dataset through the MLflow tracking UI | <img src="https://img.shields.io/badge/-MLflow-0194E2?logo=mlflow&logoColor=white" height="20"> |

---

### Stack

**ML and data**

<p>
<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white">
<img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white">
<img src="https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white">
<img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white">
<img src="https://img.shields.io/badge/MLflow-0194E2?style=for-the-badge&logo=mlflow&logoColor=white">
<img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white">
</p>

**Web and tooling**

<p>
<img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white">
<img src="https://img.shields.io/badge/Node.js-5FA04E?style=for-the-badge&logo=nodedotjs&logoColor=white">
<img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB">
<img src="https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white">
<img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white">
</p>
