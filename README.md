# Social_Media_Data_Analysis_DVA_Assignment_2
# 📊 DVA Lab — Social Media Data Analysis

A data visualization and text analytics project built on the **Reddit Comments Dataset**.  
This notebook explores a large-scale Reddit corpus, cleans the text, detects languages, translates non-English comments, extracts features, analyzes sentiment, and visualizes the data using techniques such as **TF-IDF**, **t-SNE**, and **K-Means clustering**. The notebook works on a **1 million comment dataset** with selected samples for some compute-heavy steps like language detection, translation, TF-IDF, and t-SNE. fileciteturn7file4

## 📌 Dataset

- **Source:** [1 Million Reddit Comments from 40 Subreddits](https://www.kaggle.com/datasets/smagnan/1-million-reddit-comments-from-40-subreddits)
- **Domain:** Social media / text analytics
- **Focus:** Reddit comment preprocessing, visualization, and feature extraction

## ✨ Features

- Data loading and overview
- Raw text visualization
- Text preprocessing pipeline
- Before vs after comparison plots
- Language detection on a sample of comments
- Translation of non-English comments to English
- Sentiment analysis using **VADER**
- Feature extraction using **TF-IDF**
- Dimensionality reduction using **SVD + t-SNE**
- Clustering using **K-Means**
- Top-term analysis per subreddit and cluster

## 🛠️ Tools and Libraries

- Python
- Pandas, NumPy
- Matplotlib, Seaborn, Plotly
- NLTK
- langdetect
- deep_translator
- VADER Sentiment
- scikit-learn
- WordCloud
- tqdm

## 🔄 Workflow

1. **Environment setup and dataset download**
2. **Load and inspect the Reddit comments dataset**
3. **Visualize raw comments**
4. **Clean and preprocess text**
5. **Compare results before and after preprocessing**
6. **Detect languages and translate non-English comments**
7. **Extract features with TF-IDF and sentiment analysis**
8. **Visualize embeddings with t-SNE and group them using clustering**

## 📊 Sample Analysis Sizes

To keep the notebook practical, some steps use sampled subsets:
- **50,000** comments for language detection
- **5,000** non-English rows for translation
- **30,000** rows for TF-IDF
- **8,000** rows for t-SNE visualization

## 📁 Outputs

The notebook generates visualizations such as:
- Word clouds
- Bar charts and histograms
- Box plots
- Sentiment distribution charts
- TF-IDF term plots per subreddit
- t-SNE projections colored by subreddit, sentiment, and cluster
- Elbow and silhouette plots for cluster selection

## 🚀 How to Run

### In Google Colab
1. Open the notebook in Colab
2. Mount Google Drive if needed
3. Install the required packages
4. Run the cells from top to bottom

### Locally
```bash
git clone <your-repo-url>
cd <repo-folder>
pip install -r requirements.txt
jupyter notebook
```

## 📦 Suggested `requirements.txt`

```txt
pandas
numpy
matplotlib
seaborn
plotly
nltk
scikit-learn
wordcloud
tqdm
langdetect
deep-translator
vaderSentiment
```

## 📝 Notes

- The notebook is designed for **Google Colab** and saves several figures to Google Drive.
- Some translation and visualization steps may take time depending on the runtime and dataset size.
- The project is well-suited for a GitHub portfolio or academic submission.

## 👤 Authors

**Akash Senigarapu    and**
**Chidvilas Reddy**

---

If this project helped you, consider starring the repository.

