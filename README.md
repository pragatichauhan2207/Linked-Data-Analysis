#  Linked Data Analysis & Class Network Insights

A complete **Data Engineering + Graph Analysis** project that processes raw LinkedIn connection data, builds a network graph, and extracts meaningful insights about connectivity, influence, and employment trends.

---

##  Project Overview

This project transforms **raw LinkedIn connection datasets** into a structured graph and performs network analysis to uncover patterns such as:

- Most connected individuals  
- Employment distribution  
- Connection strength levels  
- Influential nodes (Dominating Set)  

###  Workflow

```
Raw Data → Cleaning → Structuring → Graph Modeling → Insights
```

---

##  Objectives

- Clean and unify raw LinkedIn data from multiple Excel files  
- Convert and standardize datasets into CSV format  
- Build a network graph using connections  
- Analyze graph structure using algorithms  
- Extract actionable insights  

---

##  Features

###  Data Cleaning Pipeline

| Step | Description |
|------|------------|
| ZIP Extraction | Extract LinkedIn data files |
| File Filtering | Keep only `.csv` and `.xls` |
| Conversion | Convert `.xls → .csv` |
| Renaming | Normalize filenames |
| Deduplication | Handle duplicate file names |

---

###  Data Processing

- Remove special characters  
- Remove HTML tags & URLs  
- Handle missing values  
- Standardize columns  

---

###  Data Structuring

- Combine `First Name + Last Name → Full Name`  
- Keep only:
  - Full Name  
  - Company  

---

###  Graph Construction

- Build adjacency list  
- Store graph in JSON format  
- Ensure node consistency  

---

###  Graph Analysis & Algorithms

| Algorithm | Purpose |
|----------|--------|
| Degree Calculation | Count connections |
| Sorting | Rank nodes |
| Random Walk | Analyze traversal |
| Dominating Set | Identify influencers |

---

##  Key Insights

###  Top Connected Individuals
- Identified most connected people in the network  
- Useful for mentorship and leadership roles  

---

###  Employment Distribution

| Category | Percentage |
|----------|-----------|
| Employed | ~50% |
| Unemployed | ~36% |

---

###  Connection Strength

| Range | Meaning |
|------|--------|
| < 500 | Low connectivity |
| 1000–2000 | Strong presence |
| 3000+ | Highly active users |

---

###  Dominating Set Insights

- Minimum nodes covering entire network  
- Useful for influence spreading and communication  

---

##  Visualizations

-  Bar Chart → Top 10 connected individuals  
-  Pie Chart → Employment distribution  
-  Horizontal Bar → Connection strength  

---

##  Tech Stack

| Category | Tools |
|--------|------|
| Language | Python |
| Libraries | pandas, matplotlib, json, os |
| Tools | Jupyter Notebook, VS Code |

---

##  Project Structure

```
Linked-Data-Analysis/
│
├── Data_Cleaning.ipynb
├── Graph Analysis.ipynb
├── adjacency_list.json
├── node_counts.json
├── Report_LinkedConnectionAnalysis.pdf
└── README.md
```

---

## How to Run

###  Clone Repository

```bash
git clone https://github.com/pragatichauhan2207/Linked-Data-Analysis.git
cd Linked-Data-Analysis
```

###  Install Dependencies

```bash
pip install pandas matplotlib
```

### Run Notebooks

- Run `Data_Cleaning.ipynb`  
- Then run `Graph Analysis.ipynb`  

---

## Real-World Problems Solved

- Messy datasets  
- File inconsistencies  
- Encoding issues  
- Missing values  
- Network analysis  

---

##  Use Cases

- Social Network Analysis  
- Placement Insights  
- Community Detection  
- Recommendation Systems  

---

##  Future Improvements

-  Web dashboard (Flask / React)  
-  Interactive graph visualization  
-  ML-based recommendations  
-  Cloud deployment  

---

##  Author

**Pragati Chauhan**  
B.Tech CSE Student  

---


This project demonstrates:

- Data Cleaning (real-world level)  
- Graph Theory application  
- Algorithm implementation  
- Insight generation  

 Combines **Data Engineering + Data Analysis**

---
