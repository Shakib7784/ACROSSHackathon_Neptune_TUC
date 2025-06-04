# 📚 Smart Paper Recommender System
### ACROSS Hackathon 2025 — Team [Your Team Name]

A fast, intelligent academic paper recommender system that helps students, researchers, and educators discover relevant scientific papers using semantic similarity.

---

## 🚀 Problem We Solved

Finding relevant research papers is time-consuming, especially for early-stage researchers and students who may not know the exact keywords or jargon. Traditional keyword-based search engines often miss semantically similar work.

---

## 💡 Our Solution

We built a paper recommendation engine that allows users to search by title or keywords and receive a list of semantically similar academic papers, instantly. Our focus was on:
- Simplicity
- Speed
- Quality of results

---

## 🧠 How It Works

- The user enters a **paper title or keyword**.
- We find the most **semantically similar papers** using **cosine similarity** on **MiniLM embeddings**.
- The output is a clean list of related papers, sorted by similarity score.

---

## 🛠️ Technical Overview

| Component         | Choice / Tool                            |
|------------------|------------------------------------------|
| Language          | Python                                   |
| Runtime           | Google Colab (Notebook UI)               |
| Dataset           | 113,000 balanced arXiv papers            |
| Model             | MiniLM Embeddings (384-dim, fast & efficient) |
| Similarity        | Cosine Similarity (via scikit-learn)     |
| UI                | Text search with `ipywidgets`            |
| Filters           | Similarity threshold ≥ 0.5               |

---

## 🖥️ Live Demo

Our Colab notebook includes:
- 🔎 A text-based search bar
- 📌 Clean results with titles and similarity scores
- ⚡ Fast performance with ~113k papers

---


----------------------------------------------------------------------------------------------------------------------------


## 🔧 How to Run

1.	download the Hackathon.ipynb from github
2.	Upload it to the google colab
3.	Run all cells to initialize the UI.
4.	Enter any paper title or topic and get instant recommendations!

----------------------------------------------------------------------------------------------------------------------------

## 🔮 Future Plans

•	Incorporate NLP for semantic understanding
•	UI Enhancement
•	Broader data source integration
•	Implement hybrid techniques (metadata + user profiling) to recommend even when user data is sparse.
•	Connect with arXiv, Springer, IEEE, and university libraries for live content updates.
•	Introduce badges or learning tracks based on reading history, improving long-term user engagement.

---

## 🙌 Team Information
1.	Hamza boughanmi(hamza.boughanmi@ieee.org) ( Team Leader )
PHD Student
2.	Tanvir Islam (tanvirislam@ieee.org) 
Master’s Student
3.	Shakib Hasan Readoy ( shakibhasan@ieee.org)
Master’s Student
4.	Fardina Sultana Kimi ( sultanafardii@gmail.com)
Master’s Student
5.	Abubakr Alwi Alshatry (Abubakralwi@gmail.com )
Master’s Student

---

## 🏆 Built for:  
**ACROSS Hackathon 2025**  
“AI-based Tools for Research Discovery”

---
