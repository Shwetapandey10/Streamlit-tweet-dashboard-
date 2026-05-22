# 🐦 StreamlitTweet — Interactive Twitter Sentiment Dashboard

A **Streamlit** web app for real-time sentiment analysis of tweets about US Airlines, featuring interactive charts, filtering, and word clouds.

---

## Screenshots

### Sentiment Overview — Histogram

<img width="1366" height="731" alt="Screenshot 2026-05-19 132737" src="https://github.com/user-attachments/assets/01ec57e5-e121-40ea-8ea2-aad4f0c4a819" />

### Airline Breakdown & Statistics
<img width="1366" height="734" alt="Screenshot 2026-05-19 133024" src="https://github.com/user-attachments/assets/e167ab08-e5d9-4224-830e-34bc758e0a68" />


### Sentiment Pie Chart
<img width="1366" height="728" alt="Screenshot 2026-05-19 133240" src="https://github.com/user-attachments/assets/f3d8a9a1-6772-433f-be5f-dd89c29bc3be" />

---

## 📋 Description

StreamlitTweet is a powerful, interactive dashboard built with Streamlit that lets you explore and interpret Twitter sentiment data focused on major US Airlines. It provides real-time visual insights through histograms, pie charts, and word clouds — all with an easy-to-use sidebar for filtering and customization.

---

## 🚀 Features

- **Random Tweet Viewer** — Browse sample tweets filtered by sentiment (positive, neutral, negative)
- **Sentiment Charts** — Switch between a Histogram and Pie Chart to see tweet distribution
- **Airline Breakdown** — Filter by one or more airlines and compare sentiment across them
- **Sentiment Statistics** — At-a-glance totals for positive, neutral, and negative tweets
- **Word Cloud** — Visualize the most common words for any sentiment category

---

## 🛠️ Tech Stack

| Tool | Purpose |
|------|---------|
| [Streamlit](https://streamlit.io/) | Web app framework |
| [Pandas](https://pandas.pydata.org/) | Data manipulation |
| [NumPy](https://numpy.org/) | Numerical operations |
| [Plotly Express](https://plotly.com/python/plotly-express/) | Interactive charts |
| [WordCloud](https://github.com/amueller/word_cloud) | Word cloud generation |
| [Matplotlib](https://matplotlib.org/) | Word cloud rendering |

## 📁 Project Structure
├── app.py          # Main Streamlit application
├── Tweets.csv      # Dataset of tweets about US Airlines


---

## ⚙️ Installation & Setup

1. **Clone the repository**
```bash
   git clone https://github.com/your-username/streamlit-tweet-dashboard.git
   cd streamlit-tweet-dashboard
```

2. **Install dependencies**
```bash
   pip install streamlit pandas numpy plotly wordcloud matplotlib
```

3. **Run the app**
```bash
   streamlit run app.py
```

4. Open your browser at `http://localhost:8501`

---

## 📊 Dataset

The app uses `Tweets.csv`, which contains ~14,000 tweets about US Airlines including sentiment labels (positive, neutral, negative) and airline names (United, US Airways, American, Southwest, Delta, Virgin America).

---

## 🙌 Acknowledgements

Dataset sourced from the [Crowdflower Twitter US Airline Sentiment](https://www.kaggle.com/datasets/crowdflower/twitter-airline-sentiment) dataset on Kaggle.<img 

Uploading Streamlit - Work - Microsoft​ Edge 2026-05-19 13-35-57.mp4…


