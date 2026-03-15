# Social Media and Mental Health Analysis

## What is this project about?

Every day, millions of people scroll through Instagram, TikTok, and YouTube for hours. At the same time, more and more people — especially young people — are feeling depressed and anxious. Is there a connection?

This project tries to answer one simple question:

**Can we predict if a person is at risk of depression just by looking at their social media habits?**

---

## The Problem

Most people know that too much social media is not good for mental health. But we wanted to go deeper and find out exactly WHICH habits are most harmful. Is it the number of hours spent online? Or is it HOW people use social media — like scrolling without purpose, or waiting for likes to feel good about themselves?

---

## The Data

We used a real survey dataset from Kaggle. 451 real people answered questions about their social media use and their mental health.

- **Source:** Kaggle — Social Media and Mental Health Survey
- **Size:** 451 people, 21 questions each
- **Questions asked:** How many hours do you use social media? Which platforms? Do you scroll without purpose? Do you feel restless without social media? How often do you feel depressed?

---

## What We Did

**Step 1 — Cleaned the data**
We removed empty rows and fixed messy column names so Python could read them properly.

**Step 2 — Explored the data with charts**
We made 5 charts to understand patterns in the data.

**Step 3 — Built an AI model**
We trained a Random Forest machine learning model to predict whether a person has high or low depression risk based on their social media habits.

---

## The 5 Charts We Made

**Chart 1 — Daily Usage Hours**
Shows how many hours per day people use social media. Most people use it more than 5 hours per day.

**Chart 2 — Most Used Platforms**
Shows which social media platforms are most popular among the survey respondents.

**Chart 3 — Correlation Heatmap**
Shows which social media habits are most strongly connected to depression and anxiety.

**Chart 4 — Anxiety by Usage Group**
Shows that people who use social media more than 5 hours per day have the highest anxiety scores. People who use it less than 1 hour have the lowest.

**Chart 5 — Feature Importance**
Shows which habits the AI model found most useful for predicting depression risk.

---

## Results

Our Random Forest model achieved **72.3% accuracy** — meaning it correctly predicted whether someone has depression risk in 72 out of every 100 cases, using only their social media behaviour.

The most important predictors were:
- Scrolling without any purpose
- Seeking validation from likes and comments
- Feeling restless when not using social media
- Total daily hours spent on social media

---

## What We Found

More social media use does lead to higher anxiety and depression risk. But the TYPE of use matters even more than the time. People who scroll passively and seek validation online are at much higher risk than people who use social media with a clear purpose.

---

## Files in This Repository

| File | Description |
|------|-------------|
| `Social_Media_Mental_Health_Project.ipynb` | Full Python code notebook |
| `Social_Media_Mental_Health_Report.docx` | Project report |
| `chart1_usage.png` | Daily usage distribution chart |
| `chart2_platforms.png` | Platform popularity chart |
| `chart3_heatmap.png` | Correlation heatmap |
| `chart4_anxiety.png` | Anxiety by usage group chart |
| `chart5_features.png` | Feature importance chart |

---

## How to Run the Code

1. Open the `.ipynb` file in Google Colab
2. Upload the dataset file `smmh.csv` from Kaggle
3. Run all cells from top to bottom

Dataset link: https://www.kaggle.com/datasets/souvikahmed071/social-media-and-mental-health

---
