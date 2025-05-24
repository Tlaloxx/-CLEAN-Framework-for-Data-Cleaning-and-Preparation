# ✨ CLEAN Framework for Data Cleaning and Preparation

## 📌 About This Framework

**CLEAN** is a practical and adaptable framework for cleaning and preparing datasets before analysis.  
This version is a standardized and enriched adaptation created by **Tlaloc Alvarez**, based on industry best practices in Exploratory Data Analysis (EDA), and inspired by data experts like **Christine Jiang**, who introduced the original CLEAN concept.

<br/>

🎥 **Watch the Original Presentation**  
**Christine Jiang – _The ONLY Data Cleaning Framework You Need_**  
[![Watch on YouTube](https://img.youtube.com/vi/y9wFFD2bXQM/0.jpg)](https://www.youtube.com/watch?v=y9wFFD2bXQM)

<br/>

Use CLEAN as a flexible, step-by-step checklist to ensure your data is tidy, structured, and analysis-ready.  
Ideal for analysts working in Excel, Python, Power BI, SQL, or any modern data tool.

## 🧠 C – Conceptualize the Data

> _Understand the structure, meaning, and purpose of the data._

### ✅ Steps:
- Identify key columns and their roles (e.g., ID, Date, Value, Category).
- Detect variable types (categorical, numerical, date, etc.).
- Understand business context and logic.

### 🔧 Techniques:
- Data dictionary creation  
- Column profiling (summary statistics)  
- Frequency counts for categorical data  
- Visual table inspection or profiling tools

**🛠 Tools:** Excel, Power BI, pandas, OpenRefine

## 🔍 L – Locate Solvable Issues

> _Find and fix common and correctable data problems._

### ✅ Steps:
- Handle missing values  
- Remove duplicates  
- Normalize inconsistent formatting  
- Fix invalid entries (e.g., negative ages)

### 🔧 Techniques:
- Drop rows/columns with excessive nulls  
- Replace missing values (mean, median, mode, forward/backward fill)  
- Use `TRIM`, `UPPER`, `LOWER`, `PROPER` for text normalization  
- Apply filters and conditional formatting to spot issues

**🛠 Tools:** Excel, Power Query, pandas, Data Wrangler

## ⚠️ E – Evaluate Unsolvable Issues

> _Identify issues that can’t be easily fixed and must be documented or excluded._

### ✅ Steps:
- Spot extreme outliers with no logical correction  
- Flag irreparable missing values in critical columns  
- Identify ambiguous or unreliable entries

### 🔧 Techniques:
- Boxplots or z-scores for outliers  
- Create flags for suspicious records  
- Log and review rows before removing

**🛠 Tools:** Power BI, pandas, seaborn, matplotlib

## 🧩 A – Augment the Data

> _Transform and enrich your dataset for better analysis._

### ✅ Steps:
- Reshape data (pivot/unpivot)  
- Merge or append from other sources  
- Create new features (e.g., month from date)  
- Encode categorical variables  
- Scale numerical data if needed

### 🔧 Techniques:
- Use Power Query or pandas for merging/reshaping  
- Date/time extraction (year, month, weekday)  
- One-hot or label encoding  
- Min-max or z-score normalization  
- Group and aggregate for KPIs

**🛠 Tools:** Power BI, Excel, pandas, scikit-learn

## 📝 N – Note and Document

> _Keep a clear record of all changes and decisions._

### ✅ Steps:
- Document every cleaning step  
- Save pre- and post-cleaning versions  
- Explain assumptions and removals  
- Create metadata for teams or future you

### 🔧 Techniques:
- Maintain a cleaning log (spreadsheet or text)  
- Use comments/notes in BI tools or notebooks  
- Save intermediate versions during workflow

**🛠 Tools:** Excel, Notion, markdown, version control (Git)

## ✅ Suggested Workflow

1. **Conceptualize** the structure and meaning of your dataset.  
2. **Locate** and fix all solvable issues.  
3. **Evaluate** problematic or ambiguous entries.  
4. **Augment** your data with transformations and new features.  
5. **Note** all your changes to ensure traceability.

## 💡 Pro Tips

- 🔒 Always keep the original dataset untouched — work on a copy.  
- 🔁 Cleaning is iterative — don’t hesitate to revisit steps.  
- 👀 Trust your eyes — visual inspection is powerful.  
- 🗒 Document everything — clarity beats memory.

Feel free to **adapt or extend** this framework to fit your own workflow, tools, and industry needs.  

Made with care 💙 by **Tlaloc Alvarez**
