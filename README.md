# Frameworks_Assignment
# 🦠 CORD-19 Research Papers Analysis

This project explores the **CORD-19 dataset (metadata.csv)** through data analysis, visualization, and interactive exploration.  
It demonstrates skills in **data cleaning, statistical analysis, visualization, and app development**.

---
## 📂 Project Structure
- `CORD19_Analysis.ipynb` → Full Jupyter Notebook analysis (step-by-step)
- `app.py` → Streamlit app for interactive data exploration
- `metadata.csv` → Dataset file (CORD-19 metadata)

---

## 🔹 Tasks & Outcomes

### Part 1: Data Loading & Exploration
- Loaded CSV with pandas
- Inspected data (`.head()`, `.info()`)
- Checked for missing values

### Part 2: Data Cleaning
- Handled missing values
- Converted **publish_time** to datetime
- Extracted **year**
- Created **abstract word count** column

### Part 3: Data Analysis & Visualization
- 📈 Publications trend over time (line chart)  
- 📊 Top publishing journals (bar chart)  
- ☁️ Word cloud of paper titles  
- 📦 Paper distribution by source  

### Part 4: Streamlit App
- Sidebar filters (year, source)  
- Interactive preview of dataset  
- Dynamic charts & word cloud  
---

## ⚙️ Installation & Setup
1. Install required libraries:
```bash
pip install pandas matplotlib seaborn wordcloud streamlit

2. Place metadata.csv in the same directory

3. Run either the Jupyter Notebook or Streamlit app 


▶️ Run Instructions

Jupyter Notebook:
jupyter notebook CORD19_Analysis.ipynb

Streamlit App:
streamlit run app.py


---

🌍 Ubuntu Principles Applied

Community → Open-source COVID-19 research exploration

Respect → Error handling without crashing

Sharing → Clean structure for reuse

Practicality → Real-world tool for researchers

📌 Author
Developed with ❤️ using Python, Pandas, Matplotlib, Seaborn & Streamlit.
