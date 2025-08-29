# Ethics Metrics in Emergency Departments (ED)

This repository contains the code and analysis for my MSc thesis project:  
**"Ethics Metrics in Emergency Department Hospitals"**

The project focuses on evaluating **bias and fairness** in predictive models for 30-day mortality in ED hospitals, using Bayesian posterior algorithms and fairness metrics such as calibration, equalized odds, and disparate impact.  

## Repository Contents
- `preprocessing.ipynb` → Data cleaning and preparation  
- `exploratory_maincodes.ipynb` → Exploratory data analysis  
- `new_code/` → Additional scripts and calibration experiments  
- CSV files → Supporting datasets and statistics  

## Dataset
The dataset used in this project is too large to be stored in GitHub.  
You can access it here:  
🔗 [Google Drive Dataset](https://drive.google.com/drive/folders/1m1m-oELBkccWJB5IqY2FsHB_l9jux6Ep?usp=sharing)

## Objectives
- Assess fairness across demographic groups (gender, race, age)  
- Evaluate calibration and bias in mortality prediction models  
- Explore mitigation strategies for ethical use of algorithms in healthcare  

---

### How to Update Your Repo with This README
1. Open a terminal in your repo (`C:\Users\mitra\codes\thesis\ethicsinED`).  
2. Run:

```powershell
echo "# Ethics Metrics in Emergency Departments (ED)" > README.md
echo "" >> README.md
echo "This repository contains the code and analysis for my MSc thesis project: **Ethics Metrics in Emergency Department Hospitals**" >> README.md
