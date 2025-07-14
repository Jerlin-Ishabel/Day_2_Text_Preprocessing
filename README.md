📘 Day 2 – NLP Text Preprocessing with Streamlit

✅ Learning Summary

On **Day 2** of my NLP journey, I explored how to clean raw text using common preprocessing techniques in NLP. This helps prepare text data for machine learning models by removing noise and simplifying structure.

Key concepts I learned and implemented:

- Lowercasing the text
- Removing punctuation
- Tokenization (splitting text into words)
- Stopword removal (removing common filler words)
- Stemming (reducing words to their base root)
- Lemmatization (smarter root form using grammar context)

I used **NLTK** for all core NLP tasks and built a **Streamlit web app** to interactively process any text.

---

📝 Tasks Completed

| Task No. | Description |
|----------|-------------|
| ✅ Task 1 | Wrote a script that applies all preprocessing steps |
| ✅ Task 2 | Tested with my own sentence (emojis, punctuation, numbers) |
| ✅ Task 3 | Compared results of Stemming vs Lemmatization |
| ✅ Task 4 | Saved script as `day2_preprocessing.py` |
| ✅ Bonus  | Created a function `clean_text(text)` that automates all steps |

---

💻 Mini Project – Text Preprocessor App

**Project Name**: NLP Text Preprocessing App  
**Built With**: Python 🐍 + Streamlit 🚀 + NLTK 🧠

Demo Link : https://day2textpreprocessing-nanbxgbmzht7dvrjtehjbk.streamlit.app/

📌 This app lets you:
- Paste or type any raw text
- Clean it using standard NLP steps
- View:
  - Cleaned word tokens
  - Stemmed version
  - Lemmatized version

---

📂 Files:

- `text_preprocessor_app.py` – Main Streamlit app  
- `requirement.txt` – Python packages  
- `Day_2_Text_Preprocessing.ipynb` – Optional notebook version  

---

▶️ How to Run:

```bash
pip install -r requirement.txt
streamlit run text_preprocessor_app.py
