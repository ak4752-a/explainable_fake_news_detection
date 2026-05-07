# Data

This folder contains dataset references used in the project.

The datasets were downloaded from Kaggle and used directly in Google Colab.  
Large dataset files are not included in this repository.

---

## 1. ISOT Fake News Dataset

### Source
https://www.kaggle.com/datasets/clmentbisaillon/fake-and-real-news-dataset

### Authors
Ahmed H., Traore I., Saad S.  
University of Victoria / ISOT Research Lab

### Dataset Size
- Total Articles: 44,898
- Fake News Articles: 23,481
- Real News Articles: 21,417

### File Size
Approximately 63 MB

### Time Period
Mostly collected from 2016–2017.

### Dataset Attributes

| Attribute | Description |
|---|---|
| `title` | News headline |
| `text` | Main article content |
| `subject` | News category/topic |
| `date` | Publication date |

### Source Characteristics
- Real news articles were collected from Reuters.
- Fake news articles were collected from unreliable websites flagged by Politifact and Wikipedia.

---

## 2. External Validation Dataset

### Source
https://www.kaggle.com/datasets/mahdimashayekhi/fake-news-detection-dataset

### Author
Mahdi Mashayekhi

### Dataset Size
- Total Articles: 20,000
- Columns: 7

### File Size
Approximately 12 MB

### Time Period
Publication dates were synthetically generated over the past 3 years.

### Dataset Attributes

| Attribute | Description |
|---|---|
| `title` | News headline |
| `text` | Article content |
| `date` | Publication date |
| `source` | Media/news source |
| `author` | Author name |
| `category` | News category |
| `label` | Fake or Real classification |

### Source Characteristics
- Synthetic but realistic dataset
- Includes approximately 5% missing values
- Used for external validation and robustness analysis

---

## Files

- `dataset_links.txt`  
  Contains source links for all datasets used in the project.
