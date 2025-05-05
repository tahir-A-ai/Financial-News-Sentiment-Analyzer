#  Financial News Sentiment Analyzer

This project provides a **comparative sentiment analysis** of financial news headlines using **three different approaches**: Traditional Machine Learning, Deep Learning, and Transformers.

##  Project Goals

To evaluate how well various NLP techniques perform sentiment classification of financial news data, and to explore the trade-offs in speed, accuracy, and implementation complexity.

---

##  Approaches Used

###  1. Traditional ML
- **Technique**: TF-IDF Vectorizer + Logistic Regression
- **Pros**: Fast, easy to interpret
- **Cons**: Limited context awareness

###  2. Deep Learning
- **Technique**: Word2Vec Embeddings + LSTM
- **Pros**: Learns sequential context
- **Cons**: Slower, needs more tuning

###  3. Transformers
- **Model**: FinBERT (pretrained financial-domain BERT)
- **Pros**: Highest contextual understanding and accuracy
- **Cons**: Heavier, black-box nature

---

##  Performance Summary

| Model        | Pros                     | Cons                    |
|--------------|--------------------------|-------------------------|
| Logistic Reg | Fast, interpretable      | Lower context awareness |
| LSTM         | Sequential learning      | More compute, tuning    |
| FinBERT      | State-of-the-art results | Less interpretable      |

---

##  Dataset

Dataset used: `financial_news.csv` (must contain a `news` and `label` column)

##  Installation

```bash
git clone https://github.com/tahir-A-ai/Financial-News-Sentiment-Analyzer.git
cd Financial-News-Sentiment-Analyzer
pip install -r requirements.txt
```

##  Usage

Open the notebook:

```bash
jupyter notebook Financial_News_Sentiment_Analyzer.ipynb
```

Make sure you have `financial_news.csv` in the correct format.

##  Dependencies

See `requirements.txt`. Key packages:
- `nltk`, `scikit-learn`, `gensim`, `tensorflow`, `transformers`, `torch`
- 

##  License

MIT License

##  Contributing

Pull requests welcome! Please open an issue to discuss improvements or bugs.

##  Author

Tahir Ali (https://github.com/tahir-A-ai)
