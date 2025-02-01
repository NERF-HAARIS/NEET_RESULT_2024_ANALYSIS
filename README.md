# NEET_RESULT_2024_ANALYSIS
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

*Insert bar chart here*

### 2️⃣ High Score Distribution (650+ Marks)

*Insert bar chart here*

### 3️⃣ Heatmap of Suspicious Centers by Score Ranges

*Insert heatmap here*

### 4️⃣ Misconduct Probability by State

*Insert state-wise bar chart here*

## 🚀 Technologies Used

- **Python:** Data processing and analysis.
- **Pandas:** Data manipulation.
- **PDFPlumber:** PDF text extraction.
- **Matplotlib & Seaborn:** Visualizations.
- **Selenium:** wev scraping

