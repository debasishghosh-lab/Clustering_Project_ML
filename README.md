# Clustering_Project_ML

**Clustering Students Based on Clubs, Hobbies, and Teamwork Preferences**

---

### 👨‍💻 Author  
**Debasish Ghosh**  
Year 3, Section 09  
B.Tech CSE (AI-ML)  

---

## 🔍 Project Overview  
Friendship and collaboration are essential for fostering student well-being and campus culture at **Student National University (SNU)**.  
This project applies **Unsupervised Machine Learning (Clustering)** to group students based on their **club memberships, hobbies, and teamwork preferences**.  

The insights can help in:  
- Designing **seating arrangements** in common rooms.  
- Planning **events & activities** that maximize peer bonding.  
- Supporting **club management** and collaboration.  

---

## 🛠️ Methodology  

1. **Data Preprocessing**  
   - Cleaned and normalized text data.  
   - Created combined “interests” feature from clubs and hobbies.  
   - Encoded features using **MultiLabelBinarizer**.  

2. **Clustering Approach**  
   - Algorithm: **Agglomerative Clustering (Ward linkage)**  
   - Distance: **Euclidean**  
   - Cluster range tested: **k = 2 to 7**  

3. **Evaluation**  
   - Metric: **Silhouette Score** (best at k=5).  
   - Visualization: **Multidimensional Scaling (MDS)** → 2D “Friendship Map”.  

---

## 📊 Results  

- **Optimal number of clusters (k): 5**  
- **Clusters identified:**  
  1. **Athletic Coders** – Sports + Coding  
  2. **Performing Artists** – Dance, Music, Cultural Club  
  3. **Tech Innovators** – Coding, Robotics, Startups  
  4. **Creative All-Rounders** – Music + Sports + Photography  
  5. **Literary Enthusiasts** – Writing, Literature, Creativity  

- **Silhouette Score:** ~0.11 (low due to overlapping interests, but clusters remain meaningful).  

---

## 🎯 Key Insights  

- Students with overlapping interests naturally form communities.  
- Friendship groups can guide **seating design, event planning, and hackathon teams**.  
- Demonstrates how **machine learning can model social dynamics** in student life.  

---

## 📂 Repository Contents  

-  Full Colab Notebook (code, preprocessing, clustering, visualizations).  
-  Dataset

---
