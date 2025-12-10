# Summarise-ai
#  Text Summarization Pipeline using NLTK, TF-IDF & HTML UI

This project is an **end-to-end NLP summarization system** built entirely in **Google Colab**.  
It supports uploading CSV files, automatically selecting text columns, cleaning text, tokenizing, scoring sentences, and generating summaries using **TF-IDF**.  
Finally, it displays the results in a **beautiful HTML dashboard** (30/20/8-line summaries).

---

##  Features

- CSV file upload via Google Colab
- Auto-detection of file encoding
- Selects the longest text column automatically
- Text cleaning (lowercase, URLs, special characters, stopwords)
- Tokenization using NLTK
- Word frequency table extraction
- Sentence scoring
- TF-IDF based summarization
- Beautiful 3-panel HTML output:
  - **Detailed Summary (30 lines)**
  - **Key Concepts (20 lines)**
  - **Important Takeaways (8 lines)**

---

##  Requirements

Google Colab will install everything automatically, but the main dependencies are:

- Python 3.8+
- pandas
- numpy
- nltk
- scikit-learn
- chardet
- tqdm

---

##  How It Works

### ** Upload CSV File**
You upload a CSV file in Colab using:

```python
uploaded = files.upload()
