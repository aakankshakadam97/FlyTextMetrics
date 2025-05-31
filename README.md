# FlyTextMetrics
## 🚀 Project Overview

- Extracted customer reviews of British Airways flights from a travel review website using web scraping.
- Classified reviews into **positive**, **negative**, and **neutral** categories using NLP.
- Visualized sentiment trends using charts and word clouds.
- Analyzed flight booking data to discover **customer ticket buying behavior**.
- Applied machine learning to predict which **days of the week** typically have the most flight bookings.

---

## 🛠️ Tech Stack

| Area                     | Tools & Libraries                                      |
|--------------------------|--------------------------------------------------------|
| Web Scraping             | `BeautifulSoup`, `requests`                           |
| Data Processing          | `pandas`, `numpy`                                     |
| NLP & Sentiment Analysis | `nltk`, `spaCy`, `TextBlob`                           |
| Visualization            | `matplotlib`, `seaborn`, `wordcloud`                  |
| Machine Learning         | `scikit-learn` (RandomForest, DecisionTree, etc.)     |

---

## 📥 Data Collection

- Scraped British Airways customer reviews using `BeautifulSoup` and `requests`.
- Parsed HTML pages to extract review text, rating, review date, and reviewer details.
- Loaded separate dataset for flight bookings containing booking date, flight details, and ticket class.

---

## 🧠 Sentiment Analysis

- Cleaned review texts (removal of stopwords, punctuation, lemmatization).
- Labeled reviews into:
  - **Positive**
  - **Negative**
  - **Neutral**
- Applied polarity scoring using `TextBlob` and keyword-based tagging for validation.

---

## 🌐 Text Visualization

- **Word Clouds**: Generated for each sentiment group to highlight frequent terms.
- **Bar Charts & Pie Charts**: To show the proportion of sentiment types and keyword frequency.
- Explored trends based on routes, review dates, and classes.

---

## 📊 Booking Pattern Analysis

- Preprocessed flight booking data and extracted relevant features (e.g., day of the week, seasonality).
- Explored booking frequency trends visually.
- Trained machine learning models to predict the most common days for ticket purchases.
- Evaluated model performance using accuracy and cross-validation.

---

## 💡 Key Insights

- Common issues found in negative reviews included delays, customer service, and seat comfort.
- Positive reviews focused on cleanliness, flight staff behavior, and on-time performance.
- Most bookings occurred mid-week, suggesting strategic pricing/marketing opportunities.

---
