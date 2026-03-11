# chicago-rent-analysis

### Software Used
- Python (version 3.9 or higher)

### Python Packages Required

The following packages must be installed:

- pandas  
- matplotlib  
- numpy

### Platform

This project was developed and tested on macOS.  
It should also run on Windows or Linux with the same Python setup.

## Section 2: Map of the Documentation

Project Folder Structure:

```
move_review_analysis/
│
├── DATA/
│   ├── Business_Licenses_Chicago.csv
│   ├── cleaned_chicago_dataset.csv
│   └── Zillow_Rent_Prices.csv
│
├── SCRIPTS/
│   ├── data_cleaning.py
│   └── eda.py
│
├── OUTPUT/
│
├── README.md
└── LICENSE
```
## Section 3: Instructions for Reproducing Results

### Step 1: Clone the Repository

```bash
git clone https://github.com/purplemorgy/chicago-rent-analysis
cd move_review_analysis
```

---

### Step 2: Create a Virtual Environment

Create a virtual environment:

```bash
python3 -m venv venv
```

Activate the virtual environment:

**Mac/Linux**
```bash
source venv/bin/activate
```

**Windows**
```bash
venv\Scripts\activate
```

---

### Step 3: Install Packages

**Base Packages (Required)**

These packages are required to run data preprocessing and exploratory data analysis:

```bash
pip install pandas matplotlib numpy
```

---

### Step 4: Run Data Cleaning and Exploratory Data Analysis Script

Run this script to generate a cleaned time series dataset:

```bash
python SCRIPTS/eda.py
```
