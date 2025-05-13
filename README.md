# Sentiment Analysis with OpenAI GPT-3.5

This Python script performs **sentiment analysis** on a given text using OpenAI's `gpt-3.5-turbo` model.  
It analyzes the emotions expressed in the input, classifies the sentiment as **positive**, **negative**, or **neutral**, and provides detailed insights into the detected sentiments.

---

## 🔍 Features

- Performs **deep sentiment analysis** on input text  
- Classifies overall sentiment: **Positive / Negative / Neutral**  
- Identifies specific **emotions** and their **intensity (0-100)**  
- Highlights contributing **words/phrases**  
- Suggests possible **reasons** for the detected sentiments  
- Provides the model’s **reasoning** behind the analysis  
- Returns results in structured **JSON format**

---

## 🛠 Requirements

- **Python 3.x**
- [`openai`](https://pypi.org/project/openai/) Python library
- A valid **OpenAI API key**

---

## 📦 Installation

```bash
pip install openai
```

## 🔑 Setup
Set your OpenAI API key in your environment:

```bash
export OPENAI_API_KEY="your-api-key-here"
```

Or configure it directly in your Python script (not recommended for production):

```bash
import openai
openai.api_key = "your-api-key-here"
````

📄 License
This project is licensed under the MIT License.