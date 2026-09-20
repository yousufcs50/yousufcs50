## Mohammad Yousuf

Machine learning engineer working in applied AI and LLM systems. Based in Lahore.

I build with Python and TypeScript, and I care about the unglamorous parts of AI systems: what happens when an option is silently ignored, when a model returns something unexpected, when the thing that worked in a notebook meets real input.

Open to freelance and contract work.

### Open source

**[vercel/ai](https://github.com/vercel/ai)** (26k+ stars), the AI SDK for TypeScript
[#21178](https://github.com/vercel/ai/pull/21178) fix(openai): warn when `reasoningSummary` is used with chat models

Passing `reasoningSummary` to a Chat Completions model silently did nothing. The option belongs to the Responses API, so `parseProviderOptions` stripped it before the model ever saw it, which made the resulting behaviour hard to debug. The fix emits an explicit `unsupported` warning instead of failing quietly, and ships with a test, a docs update, and a changeset.

Continuing to contribute to the AI SDK.

### Selected work

**[Social distancing detector](https://github.com/yousufcs50/social_distancing_detection_CNN)** · Python, YOLOv3, OpenCV
Detects people in video frames and flags pairs standing closer than a set pixel distance, using YOLO-COCO weights and centroid comparison.

**[Object detection](https://github.com/yousufcs50/Object-Detection)** · Python, YOLOv3, Jupyter
Bounding boxes and class probabilities predicted in a single pass over full images, run against street camera footage at varying angles.

**[ChatGPT integration API](https://github.com/yousufcs50/chatgpt_intergration_api)** · Python, Flask, OpenAI
A small Flask service exposing OpenAI chat completion behind `/v1/chat`, with a separate Whisper transcription script.

**[Reaction time tester](https://github.com/yousufcs50/reaction_time_game)** · JavaScript, Node, SQLite
An F1-style reaction game with randomised light timing and a persistent leaderboard.

**[Experiment tracking with MLflow](https://github.com/yousufcs50/working_with_mlflow)** · Python, MLflow
Comparing model runs on the UCI bike sharing dataset through the MLflow tracking UI.

### Stack

`Python` `TensorFlow` `scikit-learn` `OpenCV` `MLflow`
`TypeScript` `Node` `React` `Flask`

### Contact

Site: [yousufcs50.github.io](https://yousufcs50.github.io)
Email: [yousuf@cloudqrgen.com](mailto:yousuf@cloudqrgen.com)
