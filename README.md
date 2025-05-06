
## 📚 SS Chatbot – Signals and Systems Assistant

A Gradio-based chatbot powered by Groq LLM to assist KTU S4 students (2019 Scheme) in understanding the ECT 204 Signals and Systems subject. The bot provides detailed exam-focused notes and relevant previous year questions for each topic.

### 🔗 Live Demo

[🔵 Try it on Gradio] : https://c855c5178e75de9d5b.gradio.live/

---

### 🚀 Features

* 💬 Natural language chat interface
* 📚 Topic-wise assistance (Elementary Signals, LTI Systems, etc.)
* 📝 Previous year question integration (2019 Scheme)
* 🧠 Uses Groq LLM (LLaMA3 or Mistral) for high-speed reasoning
* 🎨 Interactive UI built with Gradio
* ⚙️ Custom system prompt for accurate responses

---

### 🛠️ Tech Stack

* [Python](https://www.python.org/)
* [Gradio](https://www.gradio.app/)
* [Groq LLM API](https://groq.com/)
* [Llama3 / Mistral](https://www.groq.com/models/)

---

### 🧾 Requirements

```bash
pip install gradio openai
```

> ✅ Make sure you have Groq API key set up as `GROQ_API_KEY` in your environment.

---



### 🧠 Sample System Prompt

```python
def initialize_messages():
    return [{
        "role": "system",
        "content": (
            "You are a skilled and experienced teacher for the KTU S4 ECT 204 Signals and Systems subject. "
            "Assist students by providing detailed exam-oriented notes when they ask. "
            "Also, include previous year questions from the KTU 2019 scheme relevant to the topics discussed."
        )
    }]
```

---

### 📸 Screenshot

![{0813D36B-02E0-4503-80BF-15DD209D20E6}](https://github.com/user-attachments/assets/943b511e-c899-4588-9d07-059f363d4710)
![{E1BE0BB4-9ACA-47B9-866D-7C41763DFA0D}](https://github.com/user-attachments/assets/4909d9ef-fd64-498a-80f3-64861cc0238a)


---

### 🗂️ Available Topics (Buttons)

* Elementary signals
* Continuous/Discrete time signals and systems
* Signal operations
* Differential equation representation
* Continuous/Discrete time LTI Systems
* Correlation between signals
* Orthogonality of signals
* Frequency domain representation
* Continuous time Fourier series

---

### ✅ How to Use

1. Clone the repo or open the notebook.
2. Run the notebook or Python script.
3. Enter your Groq API key (if prompted).
4. Ask your questions or click on a topic button.

---

### 🙋‍♀️ Made by

Avanthika K S


