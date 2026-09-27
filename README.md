Data Quality Copilot

## Overview
This is a simple AI assistant that checks the quality of your data. It looks at CSV files, finds problems, and suggests improvements.

## What You’ll Learn
- How to check data quality  
- How to work with CSV files  
- How AI can analyze data  
- Basic data cleaning ideas  

## Requirements
- Python 3.8+  
- Basic Python knowledge  
- OpenAI API key  

## Quick Start

### 1. Install
```bash
pip install -r requirements.txt
```

### 2. Add Your API Key
Create a file called `.env` in this folder:
```
OPENAI_API_KEY=your-api-key-here
```

### 3. Add Data
Put your CSV files in the `data/` folder.

### 4. Run
```bash
python data_copilot.py
```

### 5. See Results
You’ll get:
- A report of data issues  
- Suggestions for fixes  
- Summary statistics  

## Checks Performed
- **Completeness**: missing values, empty cells  
- **Consistency**: wrong data types, duplicates  
- **Validity**: out-of-range or invalid formats  
- **Accuracy**: outliers, suspicious patterns  

## Files
- `data_copilot.py` → main code  
- `requirements.txt` → dependencies  
- `data/` → your CSV files  
- `data/sample_data.csv` → example dataset  
- `.env` → your API key  

## Example Issues
- Missing values in a column  
- Duplicate rows  
- Invalid email formats  
- Outliers in numeric data  

## Output
- Console report  
- Text report file  
- Issue summary  
- Recommendations  

---

This version strips away the extra detail and keeps it practical: install, set up, run, and see results.  

Would you like me to also create a **minimal sample README.md file** you can drop straight into your GitHub repo so it looks clean and professional?