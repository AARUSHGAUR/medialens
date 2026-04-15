# 📰 MediaLens — News Bias Detector

MediaLens is a lightweight, browser-based tool that analyzes news articles to detect **political bias, emotional tone, and credibility** using rule-based NLP techniques.

🔗 Live Demo: https://medialens-tau.vercel.app/

---

## 🚀 Features

* 🧭 **Political Bias Detection**
  Classifies content as Left, Center, or Right leaning

* 📊 **Bias Spectrum Visualization**
  Displays position on a political spectrum

* 💬 **Emotional & Sensational Analysis**
  Detects emotionally charged and sensational language

* 📉 **Credibility Scoring**
  Evaluates trustworthiness based on linguistic signals

* ⚖️ **Balance Assessment**
  Measures how balanced the article is

* 🧠 **Loaded Word Detection**
  Highlights biased or emotionally loaded terms

* 🔍 **Missing Perspectives**
  Suggests viewpoints not represented in the article

* 💡 **Reader Recommendation**
  Advises how to approach the article critically

---

## 🛠️ Tech Stack

Frontend:
- HTML, CSS, JavaScript (Vanilla)

Text Analysis Engine:
- Rule-based NLP (Lexicon-based classification)
- Keyword frequency analysis
- Regex-based pattern matching

Deployment:
- Vercel

---

## ⚙️ How It Works

MediaLens uses predefined lexical datasets to analyze input text:

* Left vs Right keyword frequency → political lean
* Emotional & sensational word density → tone scoring
* Factual indicators → credibility estimation
* Loaded words → bias intensity
* Perspective gaps → missing viewpoints

All processing happens **client-side**, with **no external APIs**.

---

## 📦 Installation & Usage

1. Clone the repository:

   ```bash
   git clone https://github.com/AARUSHGAUR/medialens.git
   cd medialens
   ```

2. Open in browser:

   ```bash
   open index.html
   ```

3. Paste any news article and click **Run Bias Analysis**

---

## 🌐 Deployment

This project is deployed using Vercel for fast and serverless hosting.

To deploy:

* Push to GitHub
* Import project in Vercel
* Deploy instantly

---

## 📸 Screenshots

(Add screenshots here after deployment)

---

## ⚠️ Limitations

* Rule-based (not ML-powered)
* Accuracy depends on keyword coverage
* Cannot detect nuanced sarcasm or deep context
* Not a replacement for professional fact-checking

---

## 🎯 Future Improvements

* Integrate ML/NLP models (BERT, etc.)
* Add real-time news API support
* Multi-language analysis
* User feedback loop for improved accuracy
* Backend for storing analysis history

---

## 🤝 Contributing

Pull requests are welcome. For major changes, open an issue first to discuss improvements.

---

## 📄 License

This project is open-source and available under the MIT License.

---

## 🙌 Acknowledgment

Built as part of an academic project on **AI & Data Science**, focusing on real-world applications of NLP in media analysis.

---

## 💡 Author

**Aarush**
Cybersecurity Student | Aspiring Security Engineer

---

## ⭐ If you found this useful

Give it a star ⭐ on GitHub — it helps a lot!
