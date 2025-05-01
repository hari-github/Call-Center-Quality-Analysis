# 📞 Agent/Call Quality Analysis

This web app evaluates customer service call transcripts to provide an automated quality assessment. Built with **Gradio**, it uses an **LLM hosted by NVIDIA's API** to analyze and score interactions across several key performance metrics.

🔗 **Live Demo**: [Try it on Hugging Face Spaces](https://huggingface.co/spaces/rewin14/apps_test)
🔗 **Video Demo**: https://youtu.be/M9TYLmQP_sU

---

## 🚀 Features

- **Upload a Transcript (.txt)**: Supports customer service call transcripts in plain text format.
- **AI-Powered Quality Assessment**: Scores agent performance across:
  - Communication Skills
  - Problem Resolution
  - Agent Knowledge
  - Professionalism
  - Customer Satisfaction
- **Topic Extraction**: Highlights key topics discussed in the call.
- **Visual Feedback**: Displays a bar chart of evaluation results.
  
---

## 📊 Sample Output

- A breakdown of each category with a rating (High / Medium / Low) and a short explanation.
- A visual bar chart representing the agent's performance.
- A list of extracted conversation topics.

---

## 📂 How to Use

1. Upload a `.txt` file containing the call transcript.
2. Click **Analyze**.
3. View the chart, performance feedback, and extracted topics.

> **Note**: Ensure the transcript is structured clearly to improve analysis accuracy.

---

## 🧠 Powered By

- [OpenAI-compatible LLM via NVIDIA API](https://integrate.api.nvidia.com/)
- [Gradio](https://www.gradio.app/)
- [Plotly](https://plotly.com/) for visualizations
- Python libraries: `PIL`, `re`, `json`, `io`

---

## 📝 Example Transcript - In the repo

