# 🛒 Association Rules Mining (Market Basket Analysis)

This repository provides a complete Python-based implementation of **Association Rule Mining**, focusing on **Market Basket Analysis** using the **Apriori algorithm**. The goal is to uncover interesting relationships and purchasing patterns from transactional retail data.

---

## 📂 Project Structure

- `Association Rules.ipynb` — Jupyter Notebook for data preprocessing, applying Apriori, generating and analyzing association rules.
- `Association Rules.docx` — Documentation covering objectives, preprocessing steps, techniques, results interpretation, and interview questions.
- `Online retail.xlsx - Sheet1.csv` — Dataset containing online retail transactional data used for mining.

---

## 🎯 Objective

- Understand and implement association rule mining.
- Apply the Apriori algorithm to identify frequently purchased product combinations.
- Generate and analyze rules based on support, confidence, and lift.
- Derive actionable insights into customer purchasing behavior.

---

## 🧰 Technologies Used

- **Python**
- **Pandas** — Data manipulation and cleaning.
- **Mlxtend** — `TransactionEncoder`, `apriori`, and `association_rules`.
- **Openpyxl** — For handling Excel files.

---

## 🧹 Data Preprocessing Steps

1. Handle missing values and duplicates.
2. Transform data into transaction format (list of item lists).
3. Apply one-hot encoding using `TransactionEncoder`.

---

## 📊 Association Rule Mining

- **Apriori Algorithm**: Finds frequent itemsets based on a minimum support threshold.
- **Association Rules Generation**: Based on support, confidence, and lift.
- **Thresholds Applied**:
  - Minimum support
  - Minimum confidence
  - Lift ≥ 2.0 (to ensure meaningful, strong associations)

---

## 📈 Analysis & Interpretation

### Key Insights:

- High-lift combinations such as:
  - **Ground Beef** & **Herb & Pepper**
  - **Mineral Water**, **Spaghetti**, & **Ground Beef**
  - **Olive Oil**, **Mineral Water**, & **Spaghetti**
- Business implications include:
  - Cross-selling strategies
  - Optimized product placement
  - Targeted promotions

---

## 📘 Key Concepts Covered

- **Support**: Frequency of itemsets.
- **Confidence**: Likelihood of rule occurrence.
- **Lift**: Strength of association beyond chance.
- **Limitations**: Sparsity, interpretability, temporal aspects, and computational cost.

---

## 🚀 How to Run

# 1. Clone the repository
git clone https://github.com/your-username/association-rules-mining.git
cd association-rules-mining

# 2. (Optional) Create a virtual environment
python -m venv env
source env/bin/activate  # On Windows, use: env\Scripts\activate

# 3. Install the required libraries
pip install pandas mlxtend openpyxl

# 4. Launch Jupyter Notebook
jupyter notebook "Association Rules.ipynb"

## 📬 Contact
Feel free to connect for feedback, questions, or collaborations.
