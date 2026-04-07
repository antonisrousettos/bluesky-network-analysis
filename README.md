# BlueSky Social Network Analysis 📊

## 📌 Project Overview
This project presents a comprehensive analysis of user behavior and community dynamics within the BlueSky social network. The study models the platform as a directed graph, where users are represented as nodes and interactions (likes and follows) as edges.

The analysis focuses on uncovering structural properties, influence patterns, and community organization using network science techniques and visualization tools.

---

## 🧠 Objectives

- Analyze user interaction patterns (likes & follows)
- Identify influential users using centrality metrics
- Examine community structures and clustering behavior
- Investigate gender-based interaction dynamics
- Evaluate network topology and connectivity

---

## 📊 Dataset

The dataset was collected through API integration and includes:

- **Nodes**: Users with attributes (ID, name, gender, profile)
- **Edges**: Interactions (likes and follows)

The network consists of:
- ~18,781 nodes
- ~22,414 edges :contentReference[oaicite:1]{index=1}

---

## ⚙️ Methodology

- Data collection via API
- Data preprocessing and cleaning
- Network construction (directed graph)
- Export to CSV for analysis
- Visualization and analysis using **Gephi**

---

## 📈 Analysis Performed

### 🔹 Centrality Measures
- Degree Centrality
- Betweenness Centrality
- Closeness Centrality
- Eigenvector Centrality
- PageRank

→ Identified key influential nodes and network hubs

---

### 🔹 Network Structure
- Diameter: 5
- Average Path Length: ~2.15 :contentReference[oaicite:2]{index=2}
- Small-world characteristics observed

---

### 🔹 Community Detection
- Modularity-based clustering
- Up to 104 communities identified
- Strong internal connectivity within clusters

---

### 🔹 Clustering & Connectivity
- Low clustering coefficient → sparse local connectivity
- Presence of tightly connected subgroups

---

### 🔹 Gender Analysis
- Moderate homophily observed
- Balanced interaction between genders

---

## 🧰 Tools & Technologies

- Python (data collection & preprocessing)
- Gephi (network visualization & analysis)
- Graph theory & network science methods

---

## 📊 Key Insights

- The network exhibits a **small-world structure**
- A small number of nodes dominate influence (high centrality)
- Strong community structure with modular clusters
- Highly resilient network (no critical bridge edges)
- Balanced interaction patterns across demographics

---

## 📄 Report

📌 Full analysis available here:  
[View Report](report.pdf)

---

## 💡 Key Learnings

- Network analysis techniques (centrality, modularity)
- Graph-based modeling of social systems
- Data-driven insights from large-scale networks
- Visualization of complex systems using Gephi

---

## 👨‍💻 Author

Antonios Rousettos
