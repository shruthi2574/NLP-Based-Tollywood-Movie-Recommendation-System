# 🎬 NLP-Based Tollywood Movie Recommendation Chatbot 

An NLP-powered chatbot that suggests **Tollywood movies** based on your current emotional state — but with a twist!  
It recommends **movies from the opposite mood** to uplift and improve your emotional well-being.

---

## 🔍 Features

- 🧠 Detects user emotion via sentiment analysis (TextBlob)
- 🎭 Supports moods: happy, sad, angry, fear, and neutral
- 🎥 Recommends 10 uplifting Tollywood movies per session
- 🤖 Runs interactively in Google Colab (no setup required)
- 🗂️ Custom movie database mapped to emotional states

---

## 🧰 Tech Stack

| Tool         | Purpose                                  |
|--------------|-------------------------------------------|
| Python       | Core programming language                 |
| TextBlob     | Sentiment analysis (NLP)                  |
| Random       | Random movie sampling                     |
| Google Colab | Run interactively in the cloud            |

---

## 🚀 Getting Started (Google Colab)

1. Open this project in Google Colab.

2. Install required libraries:

```python
!pip install textblob
python -m textblob.download_corpora
```
3. Paste the chatbot code into a cell and run.. 

4. Type a sentence about how you feel and receive movie suggestions!


   

## 💡 Example Output

```
Hi! Tell me how you're feeling today (type a sentence): I’m very upset and heartbroken.

🔍 Detected Emotion: sad

🎥 To uplift your mood, here are 10 Tollywood movies you might enjoy:
- Baahubali
- DJ
- Arya 2
- Fidaa
- SVSC
...


```

---

## 📂 Project Structure

```
weather-dashboard–java /
├── WeatherDashboard.java
└── README.md
```

---

## 🙋‍♀️ Author

Gugulothu Shruthi  
B.Tech,CSE—Narayanamma Institute of Technology  
✉️ [gugulothushruthi@gmail.com](mailto:gugulothushruthi@gmail.com)
