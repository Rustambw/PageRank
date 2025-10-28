# Algorithms for Massive Data

## **PageRank Analysis on the Gowalla Social Network**

**Author:** Rustamjon Bobomuratov
**Academic Year:** 2024–2025
**University:** Università degli Studi di Milano
**Course:** Algorithms for Massive Data – Prof. Dario Malchiodi

---

### 📘 **Project Overview**

This project implements the **PageRank algorithm** using **Apache Spark (PySpark)** to analyze the **Gowalla social network dataset**, a large-scale graph representing user check-ins and interactions.

The goal is to identify the most influential users within the network and demonstrate the scalability of distributed graph analysis using Spark’s RDD-based computation model.

---

### 📂 **Repository Contents**

| File                                                 | Description                                                                            |
| ---------------------------------------------------- | -------------------------------------------------------------------------------------- |
| `Algorithms_for_Massive_Data_Gowalla_PageRank.ipynb` | Google Colab / Jupyter notebook implementing PageRank using PySpark                    |
| `Gowalla_Project_Report.pdf`                         | Full report including dataset description, methodology, visualizations, and discussion |
| `Gowalla_edges.csv`                                  | Input dataset (edges list) – may be omitted if dataset size is large                   |

---

### ⚙️ **Environment Setup**

* **Python:** 3.11
* **PySpark:** 3.5.0
* **Libraries:** `pandas`, `matplotlib`, `networkx`
* **Runtime:** Google Colab 

To run in Colab, simply upload the notebook and dataset, or clone this repository:

```bash
git clone https://github.com/RustamBw/PageRank.git
```

---

### 🚀 **Execution Steps**

1. Open the notebook in **Google Colab** or **Jupyter**.
2. Run all cells sequentially.
3. The notebook will:

   * Load and preprocess the Gowalla dataset
   * Build the user network
   * Compute PageRank iteratively (10 iterations)
   * Output top influencers and generate visualizations
4. Final results are saved as a CSV in `/content/gowalla_pagerank_output/`.

---

### 📊 **Key Results**

* Identified top-10 influential users using PageRank.
* Observed **power-law influence distribution** typical of real-world social networks.
* Visualized:

  * Top 10 PageRank nodes (bar chart)
  * PageRank distribution (histogram)
  * Network graph of top 50 users (NetworkX visualization)

---

### 🧠 **Concepts Demonstrated**

* **Link Analysis (PageRank)**
* **MapReduce Programming in Spark**
* **Distributed Graph Computation**
* **Massive Data Processing**
* **Visualization and Interpretation of Influence Networks**

---

### 📜 **Declaration**

This project is entirely my own work and was developed as part of the *Algorithms for Massive Data* course (A.Y. 2024–2025).
All code and materials are used strictly for educational purposes.
