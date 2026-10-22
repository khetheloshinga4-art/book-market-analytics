# Book Market Analytics – Books to Scrape

**Data Science 500 Assignment**  
**Richfield Graduate Institute of Technology**

---

## Project Overview

This project simulates a real-world data science workflow for a publishing analytics team. The goal is to analyse book catalogue trends on [Books to Scrape](https://books.toscrape.com) and build a predictive model that estimates book prices based on publicly available product information.

As a Junior Data Scientist, the work covers the full end-to-end pipeline:

1. **Data Acquisition** – Web scraping with BeautifulSoup  
2. **Data Cleaning & Preparation**  
3. **Exploratory Data Analysis & Visualisation**  
4. **Predictive Modelling** (Linear Regression)  
5. **Professional Reporting**

---

## Project Objectives

- Scrape a minimum of **200 books** (full catalogue of 1 000 books across 50 genres preferred) from https://books.toscrape.com  
- Extract key product attributes:  
  - Book title  
  - Price (GBP)  
  - Star rating (One–Five)  
  - Stock availability (In stock / Out of stock + quantity where available)  
- Clean and structure the raw data into an analytical dataset  
- Explore pricing patterns, rating distributions, and genre trends through visualisations  
- Build a linear regression model to predict book price from derived features  
- Deliver actionable insights and recommendations for retailers, publishers, and data-driven book buyers

---

## Project Structure

```
Book-Market-Analytics/
│
├── data/
│   ├── raw/                  # Raw scraped data
│   └── processed/            # Cleaned final dataset
│
├── notebooks/
│   └── Book_Market_Analytics.ipynb   # Complete end-to-end Jupyter Notebook
│
├── reports/
│   └── Project_Report.pdf            # Professional analytical report
│
├── src/                      # Optional: modular Python scripts
│   ├── scrape.py
│   ├── clean.py
│   └── model.py
│
├── requirements.txt
└── README.md
```

---

## Deliverables

| # | Deliverable                              | Description                                      |
|---|------------------------------------------|--------------------------------------------------|
| 1 | Jupyter Notebook                         | Full pipeline from scraping → modelling → interpretation |
| 2 | Final Dataset                            | Clean, structured dataset produced from scraping |
| 3 | Professional Project Report              | Methodology, insights, modelling outcomes & recommendations |

---

## Technical Requirements

### 1. Data Acquisition (20 marks)
- Use **BeautifulSoup** to scrape product listings
- Extract required fields for each book
- Collect ≥ 200 books (multiple pages / full catalogue encouraged)
- Clear, reproducible, well-structured code

### 2. Data Cleaning & Preparation (20 marks)
- Handle missing or inconsistent values
- Convert price and rating into numeric formats
- Prepare text fields for analysis
- Document cleaning decisions

### 3. Data Visualisation & Exploration (20 marks)
- Visualisations of price patterns, ratings, and genre trends
- Explore relationships between key variables
- Clear, readable plots with insightful interpretation

### 4. Predictive Modelling – Linear Regression (20 marks)
- Construct a modelling-ready dataset
- Implement Linear Regression correctly
- Justify feature selection
- Evaluate with appropriate metrics (e.g., MAE, RMSE, R²)
- Interpret coefficients and discuss model limitations

### 5. Report Quality & Communication (20 marks)
- Clear explanation of methods and workflow
- Professional structure and writing
- Practical insights and actionable recommendations

---

## How to Run

1. **Clone / download** the project repository.

2. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

3. **Open the Jupyter Notebook**:
   ```bash
   jupyter notebook notebooks/Book_Market_Analytics.ipynb
   ```

4. **Execute cells sequentially** to reproduce the full pipeline (scraping → cleaning → visualisation → modelling).

> **Note**: Internet access is required for the scraping step. The Books to Scrape website is a sandbox designed for educational scraping practice.

---

## Key Libraries

- `requests` + `BeautifulSoup4` – Web scraping  
- `pandas` – Data manipulation  
- `numpy` – Numerical operations  
- `matplotlib` / `seaborn` – Visualisation  
- `scikit-learn` – Linear Regression and evaluation metrics  

---

## Ethical & Academic Integrity

- This project uses the publicly available sandbox site **books.toscrape.com**, which is explicitly designed for web-scraping practice.  
- All work must be original. Proper citation (Harvard style) is required for any external sources.  
- A signed Declaration of Originality must accompany the submission.

---

## Submission Checklist

- [ ] Cover page completed (Name, Student ITS No, Qualification, Year, Semester, Due date, Submission date)  
- [ ] Jupyter Notebook (PDF or .ipynb as required)  
- [ ] Final cleaned dataset  
- [ ] Professional project report (PDF)  
- [ ] Declaration of Originality signed  
- [ ] Times New Roman, 12 pt, 1.5 line spacing, Harvard referencing  

---

## Author

**Khethelo Shinga**  
402605502  
Data Science 500  
Richfield Graduate Institute of Technology  

---


