# 📈 Sentiment Analysis of Stock News

This project performs sentiment analysis on stock market news headlines using Natural Language Processing (NLP) techniques. It scrapes live news from [Finviz](https://finviz.com) for selected stock tickers and analyzes their sentiment using the VADER sentiment analyzer. The results are visualized through various plots for easy interpretation.

---

## 🛠️ Tools & Libraries Used

- `Python`
- `BeautifulSoup` – for web scraping news headlines
- `NLTK (VADER)` – for sentiment analysis
- `TextBlob` – optional alternative sentiment tool
- `Matplotlib & Seaborn` – for plotting
- `WordCloud` – for sentiment word clouds
- `Pandas` – for data manipulation

---

## 📊 Project Features

- ✅ Real-time scraping of stock news headlines
- ✅ Sentiment scoring using VADER
- ✅ Classification into Positive, Negative, or Neutral
- ✅ Visualizations:
  - Line graph of average sentiment over time
  - Bar chart by ticker and date
  - Pie chart of sentiment distribution
  - Word clouds for positive and negative words
  - Box plots by ticker

---

## 📌 Tickers Analyzed

- `TSLA` (Tesla)
- `AMZN` (Amazon)
- `GOOG` (Google)
- `AMD` (Advanced Micro Devices)

---

## 🚀 How to Run the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/sentiment-analysis-stock-news.git
   cd sentiment-analysis-stock-news
