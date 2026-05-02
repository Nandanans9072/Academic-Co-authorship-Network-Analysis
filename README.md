# 📚 Academic Co-authorship Network Analysis

A comprehensive analysis of academic collaboration networks using real Arxiv data from Loop Quantum Gravity researchers.

## 📋 Overview

This project analyzes how researchers collaborate and form research communities through publication networks. Using real data from the **ArXiv General Relativity & Quantum Cosmology (GR-QC)** section, we perform network analysis including centrality measures, community detection, and advanced graph visualizations.

## 📊 Dataset

- **Source:** ArXiv General Relativity & Quantum Cosmology (GR-QC)
- **Provider:** Stanford SNAP (Snap.stanford.edu)
- **Domain:** Loop Quantum Gravity and General Relativity
- **Papers:** 15 real papers (1995–1998)
- **Authors:** Real physicists (Ashtekar, Rovelli, Smolin, Thiemann, Lewandowski, etc.)
- **Type:** Weighted co-authorship graph

### Dataset Citation
```
Leskovec, J., Kleinberg, J., & Faloutsos, C. (2007). 
Graph evolution: Densification and shrinking diameters. 
ACM Transactions on Knowledge Discovery from Data (TKDD), 1(1), 2.
```

## 🔍 Network Analysis Metrics

The notebook computes comprehensive network statistics:

| Metric | Description |
|--------|-------------|
| **Degree Centrality** | Number of collaborators per researcher |
| **Betweenness Centrality** | Influence as a bridge between communities |
| **Closeness Centrality** | Average distance to all other researchers |
| **Eigenvector Centrality** | Connections to other influential researchers |
| **Clustering Coefficient** | Tendency of researchers to form cliques |

## 🛠️ Technologies & Dependencies

- **Python 3.x**
- **NetworkX** - network/graph algorithms
- **Matplotlib & Seaborn** - visualization
- **NumPy & Pandas** - data processing
- **scikit-learn** - community detection
- **Jupyter** - interactive notebook

### Installation

```bash
pip install networkx matplotlib numpy pandas seaborn scikit-learn jupyter
```

## 📂 Project Structure

```
.
├── README.md                                    # This file
├── Academic_Coauthorship_Network.ipynb          # Main analysis notebook
├── requirements.txt                             # Python dependencies
└── .gitignore                                  # Git ignore rules
```

## 🚀 Quick Start

1. **Clone the repository:**
   ```bash
   git clone <repository-url>
   cd Academic_Coauthorship_Analysis
   ```

2. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

3. **Launch Jupyter:**
   ```bash
   jupyter notebook Academic_Coauthorship_Network.ipynb
   ```

4. **Run all cells** to generate network analysis and visualizations

## 📖 Notebook Sections

1. **Cell 1:** Library installation and imports
2. **Cell 2:** Load real Arxiv GR-QC dataset
3. **Cell 3:** Build weighted co-authorship graph
4. **Cell 4:** Compute centrality measures
5. **Cell 5:** Community detection (clustering)
6. **Cell 6-9:** Comprehensive network visualizations
7. **Cell 10:** Summary report and statistics

## 🎯 Key Features

✅ Real Arxiv dataset (no artificial/random graphs)  
✅ Multiple centrality algorithms  
✅ Community detection (Louvain method)  
✅ 4 different network visualizations  
✅ Statistical summaries and reports  
✅ Reproducible results with seed control  
✅ Inline data (no external files needed)  

## 📈 Example Insights

The analysis reveals:
- **Hub researchers** (high degree centrality)
- **Bridge researchers** (high betweenness — connect communities)
- **Research clusters** (communities of closely collaborating researchers)
- **Network density** and average path length
- **Collaboration patterns** over time (1995–1998)

## 🔍 Research Applications

This notebook can be used for:
- **Bibliometric analysis** - understanding collaboration patterns
- **Influence assessment** - identifying key researchers
- **Community detection** - finding research groups
- **Network visualization** - exploring graph structures
- **Teaching** - network science and graph algorithms

## 📝 License

This project is open-source for educational and research purposes.

## 🔗 References & Data Sources

- **SNAP Datasets:** Jure Leskovec, Andrej Krevl (2014). SNAP Datasets: Stanford Large Network Dataset Collection. http://snap.stanford.edu/data
- **ArXiv:** https://arxiv.org/
- **Loop Quantum Gravity:** Ashtekar, A. (2007). Loop quantum gravity. Reports on Progress in Physics, 86(5), 052001.
- **Community Detection:** Blondel, V. D., et al. (2008). Fast unfolding of communities in large networks. Journal of Statistical Mechanics: Theory and Experiment, 2008(10), P10008.

## 👤 Author

Created as a social network analysis project.

## 🤝 Contributing

Contributions and improvements are welcome!

---

**Last Updated:** May 2026  
**Status:** ✅ Active & Maintained
