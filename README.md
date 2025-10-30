# 🧠 Social Network Community Detection — Karate Club Graph

This project performs **community detection on the Zachary Karate Club social network** using Python, NetworkX, and K-Means clustering. It identifies social communities, detects influential nodes, and visualizes network structure.

---

## 🎯 Objective

- Detect communities in a social network graph  
- Identify influencer nodes using centrality metrics  
- Visualize community structure and relationships  

---

## 🛠️ Techniques Used

| Category | Methods / Tools |
|--------|----------------|
Graph Analysis | NetworkX Graphs, Modularity Score  
Clustering | K-Means  
Centrality | Degree Centrality, Betweenness Centrality  
Visualization | Network Graphs, Matplotlib  

---

## 📊 Dataset
**Zachary Karate Club Graph**  
- 34 nodes (club members)  
- 78 edges (friendship ties)  

---

## 🚀 Tech Stack

| Tool | Purpose |
|-----|--------|
Python | Core analysis  
NetworkX | Graph operations & centrality  
Pandas/Numpy | Data manipulation  
Scikit-Learn | K-Means clustering  
Matplotlib | Visualization  
Jupyter Notebook | Development environment  

---

## 🧾 Steps Performed

1. Loaded the Karate Club dataset from NetworkX
2. Calculated betweenness & degree centrality
3. Applied **K-Means clustering** on node embeddings
4. Computed **modularity score** to evaluate communities
5. Visualized clusters & highlighted influencer nodes

---

## 📈 Results

| Outcome | Description |
|--------|-----------|
✅ Communities detected | Members cluster based on relationships  
✅ Influencers found | Nodes with highest centrality scores  
✅ Visualizations | Colored network graph indicating clusters  

---

## 📦 How to Run

```bash
git clone https://github.com/yourusername/karate-club-network-analysis
cd karate-club-network-analysis
pip install -r requirements.txt
jupyter notebook
