# 🎬 NLP-Based Tollywood Movie Recommendation Chatbot (Uplifting Edition)

This is a Natural Language Processing (NLP)-based command-line chatbot that recommends **Tollywood movies** to users based on their emotional state.  
Instead of reinforcing emotions, it smartly suggests movies from the **opposite emotional category** to uplift or balance the user’s mood.

---

## 🔍 Features

- 🧠 Detects emotions from user input using sentiment analysis (TextBlob)
- 🎭 Supports multiple emotions: happy, sad, angry, fear, and neutral
- 🎥 Recommends 10 random Tollywood movies **opposite to the detected mood**
- 🔁 Conversational chatbot experience in the terminal
- 🗂️ Categorized movie database for each emotion

---

## 🧰 Tech Stack

| Tool         | Purpose                                  |
|--------------|-------------------------------------------|
| Python       | Core programming language                 |
| TextBlob     | NLP-based sentiment analysis              |
| Random       | To randomly select 10 movies per emotion  |
| Terminal     | Runs as an interactive CLI chatbot        |
| Git & GitHub | Version control and hosting               |

---

## 🚀 Getting Started

### Prerequisites

- Python 3.x  
  👉 [Download Python](https://www.python.org/downloads/)
- Install dependencies:
  
```bash
pip install textblob
python -m textblob.download_corpora
```
🔧 Running the Chatbot
1. Clone the repository:

   ```bash
git clone https://github.com/your-username/tollywood-movie-chatbot.git
cd tollywood-movie-chatbot

```
2. Run the script:

   ```bash
   python movie_chatbot.py
---

## 💡 Example Output

```
Welcome to the NLP-Based Tollywood Movie Recommendation Chatbot! 🎬

Hi! Tell me how you're feeling today (type a sentence): I'm feeling down and stressed.

🔍 Detected Emotion: sad

🎥 To uplift your mood, here are 10 Tollywood movies you might enjoy:
- Baahubali
- DJ
- Gabbar Singh
- Arya 2
- Fidaa
- Julayi
- Dookudu
- SVSC
- Race Gurram
- Nenu Local

```

---

## 📂 Project Structure

```
tollywood-movie-chatbot/
├── movie_chatbot.py       
├── README.md              

```

---

## 🙋‍♀️ Author

Gugulothu Shruthi  
B.Tech,CSE—Narayanamma Institute of Technology  
✉️ [gugulothushruthi@gmail.com](mailto:gugulothushruthi@gmail.com)

---
