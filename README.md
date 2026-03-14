# FUTURE_ML_03
Machine Learning Resume Screening System using NLP and TF-IDF
# Resume Screening System using Machine Learning

## Project Overview

This project builds a **Machine Learning based Resume Screening System** that automatically analyzes resumes and ranks candidates based on their similarity to a given job description.

The system uses **Natural Language Processing (NLP)** techniques to process resume text and identify the most suitable candidates.

This type of system is commonly used in **HR Tech and Applicant Tracking Systems (ATS)** to reduce manual resume screening time.

---

## Features

* Resume text preprocessing
* NLP based text cleaning
* Resume and Job Description similarity calculation
* Candidate ranking using similarity scores
* Skill extraction from resumes
* Identification of missing skills
* Visualization of candidate scores

---

## Technologies Used

* Python
* Jupyter Notebook
* Pandas
* NumPy
* Scikit-learn
* NLTK
* Matplotlib
* Seaborn

---

## Machine Learning Approach

The project uses the following pipeline:

1. Resume text preprocessing
2. Stopword removal using NLTK
3. TF-IDF Vectorization
4. Cosine Similarity calculation
5. Candidate ranking based on similarity score

TF-IDF converts resume text into numerical vectors, and cosine similarity measures how closely a resume matches the job description.

---

## Project Structure

```
FUTURE_ML_03
│
├── Resume_Screening_System.ipynb
├── requirements.txt
├── README.md
└── dataset/
      └── resumes.csv
```

---

## Dataset

The dataset used in this project is the **Resume Dataset** from Kaggle.

Download the dataset from:

https://www.kaggle.com/datasets/snehaanbhawal/resume-dataset

After downloading, place the dataset inside a folder named **dataset** in the project directory.

Example path:

```
dataset/resumes.csv
```

In the notebook the dataset is loaded using:

```python
df = pd.read_csv("dataset/resumes.csv")
```

---

## How to Run the Project

1. Clone the repository

```
git clone https://github.com/yourusername/FUTURE_ML_03.git
```

2. Navigate to the project folder

```
cd FUTURE_ML_03
```

3. Install required libraries

```
pip install -r requirements.txt
```

4. Launch Jupyter Notebook

```
jupyter notebook
```

5. Open and run:

```
Resume_Screening_System.ipynb
```

---

## Example Output

The system ranks resumes based on similarity score with the job description.

Example output:

| Candidate   | Similarity Score | Skills Found     |
| ----------- | ---------------- | ---------------- |
| Candidate 1 | 0.82             | Python, Pandas   |
| Candidate 2 | 0.78             | Python, SQL      |
| Candidate 3 | 0.74             | Machine Learning |

---

## Future Improvements

* Build a web interface using Streamlit
* Use advanced NLP models like BERT
* Automatic resume parsing from PDF
* More accurate skill extraction using spaCy

---

## Author

Prashanth Gowda

Machine Learning Enthusiast | AI Developer
