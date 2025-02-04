# NEET_RESULT_2024_ANALYSIS
### Misconduct Probability by State
![Screenshot (163)](https://github.com/user-attachments/assets/0cb1bdc2-95c8-4a26-9019-e7b51f0161c2)
unknow = out of india
### Findings
There were totally 60 centers, where students scored Full marks that is 720 . Also within some of these centers more than 100 students from the same center scored above 650 plus.
why is this something that needs to be stated, because never in the history of NEET examination more than one or two students have scored 720 and this shows taht this is not some gradual change , making it an anamoly - (The exact details can be seen in the visualization and notebooks )

scraped the non -inspectable result website to download 4750 pdfs then extracted data form them to perform analysis 
## 📊 Objectives

- Detect centers with suspiciously high numbers of full marks (720) and near-perfect scores.
- Analyze score distributions to identify patterns of misconduct.
- Visualize anomalies to highlight potential fraud hotspots.

## 🗂️ Data Description

- **Input:** NEET result PDFs from various exam centers.
- **Extracted Fields:**
  - **Srlno:** Serial number of each student.
  - **Marks:** Marks obtained.
  - **Center Name:** Full name of the exam center.
  - **State:** Extracted from the center name for regional analysis.

## ⚡ Key Features

1. **Fraud Detection:**
   - Identifies centers with 720 or near-720 scores.
   - Flags centers with abnormal percentages of 700+ and 600+ scores.
2. **State-Level Misconduct Analysis:**
   - Highlights states with a higher probability of exam misconduct.

## 📈 Visualizations

### 1️⃣ Suspicious Centers Ranked by Full Marks (720)

![Screenshot (164)](https://github.com/user-attachments/assets/ff3cc9ea-6f32-4c66-a38b-5192724a683f)

total number of students who got full = 61





### 2️⃣ High Score Distribution (650+ Marks)

![650plus](https://github.com/user-attachments/assets/f5143a9a-6a9e-4e41-9b8a-2ce2b2b4e797)


### 3️⃣ Heatmap of Suspicious Centers by Score Ranges

![heatmap_anamoly](https://github.com/user-attachments/assets/aeeb53ea-dfdd-463a-8de6-85bac317b4fa)

very high = 700 + , high = 650 +




## 🚀 Technologies Used

- **Python:** Data processing and analysis.
- **Pandas:** Data manipulation.
- **PDFPlumber:** PDF text extraction.
- **Matplotlib & Seaborn:** Visualizations.
- **Selenium:** wev scraping
- **regex:** data extraction 
