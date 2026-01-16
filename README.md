# Software Engineering Portfolio

This repository contains two data-centric Jupyter notebooks that demonstrate applied software engineering practices: reproducible analysis, clear project structure, and documented workflows. Each notebook includes narrative context, structured code, and outputs suitable for review during interviews.

## Projects

### 1) Text Classification Pipeline
A complete end-to-end NLP workflow that:
- loads and cleans text data,
- converts text to TF–IDF features,
- trains a logistic regression classifier,
- evaluates performance using classification metrics and a confusion matrix.

**Key skills demonstrated:** data preprocessing, model training, evaluation, and reproducibility.

Notebook: `Text_Classification_Pipeline.ipynb`

### 2) School Catalogue OOP Project
An object-oriented design exercise that models a school catalogue. The notebook walks through class design, instantiation, and usage to demonstrate core OOP concepts in Python.

**Key skills demonstrated:** class design, encapsulation, and clean, readable code in an instructional context.

Notebook: `School_Catalogue_OOP_Project.ipynb`

## How to Run

These notebooks are compatible with standard Jupyter environments (local Jupyter, VS Code, or Google Colab).

### Option A: Run locally
1. Create and activate a virtual environment (recommended).
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Launch Jupyter:
   ```bash
   jupyter notebook
   ```
4. Open the notebook you want to explore.

### Option B: Run in Google Colab
Each notebook includes a badge at the top that opens the file in Colab directly. No local setup is required.

## Repository Structure

```
.
├── README.md
├── requirements.txt
├── School_Catalogue_OOP_Project.ipynb
└── Text_Classification_Pipeline.ipynb
```

## Notes on Code Quality

- Each notebook is structured with markdown sections that explain intent and results.
- Code cells are organized to reflect a logical progression from setup to output.
- The text classification pipeline includes explicit evaluation steps to verify model behavior.

If you review this repository for hiring purposes, the notebooks are designed to be easy to follow, reproducible, and demonstrative of practical engineering skills.
