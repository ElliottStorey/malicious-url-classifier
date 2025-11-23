# Malicious URL Classifier

Malicious URL classifier implemented using Pytorch with a streamlit frontend. Trained on [Malicious_n_Non-Malicious URL](https://www.kaggle.com/datasets/antonyj453/urldataset), [Malicious URLs dataset](https://www.kaggle.com/datasets/sid321axn/malicious-urls-dataset), and [Malicious And Benign URLs](https://www.kaggle.com/datasets/siddharthkumar25/malicious-and-benign-urls).

## Getting Started

### Installation

Clone the repository:

```bash
git clone https://github.com/ElliottStorey/malicious-url-classifier.git
cd malicious-url-classifier
```

Install required packages:

```bash
pip install -r requirements.txt
```

### Usage

Initialize and train Word2Vec model:

```bash
python3 word2vec.py
```

Train classifier (optional):

```bash
python3 train.py
```

Run streamlit app:

```bash
streamlit run streamlit_app.py
```
