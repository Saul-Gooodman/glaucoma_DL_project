# Glaucoma Visual Field Deep Learning Project

### Overview
This project explores and preprocesses the **Washington Visual Field (UWHVF)** dataset to prepare data for deep learning–based glaucoma progression modeling.

It covers exploratory data analysis (EDA), creation of per-eye triplets for temporal modeling, and visualization of visual fields using Voronoi approximation.

---

### Steps Completed
1. **Data understanding** — read and explored `VF_Data.csv`  
2. **Descriptive statistics** — computed mean, min, max, std for key metrics (Age, MS, MTD, PSD, TDs)  
3. **Triplet creation** — generated sequences `(v1, v2 → v3)` per eye  
4. **Visualization** — produced Voronoi-based maps of visual fields  
5. **Data ready for training** — exported `.npy` arrays and metadata

---

### Data Source
**Washington Visual Field Dataset**, derived from the article shared in the project description.  
All data are anonymized and publicly available for research and educational use.

---

### Requirements
numpy
pandas
matplotlib
seaborn
scipy

---

### Next Steps
- Implement PyTorch data loaders and model training scripts.
- Train temporal models (CNN / VAE / RNN) to predict future visual fields.
- Evaluate with MAE and compare with point-wise regression.

---

### 🧑‍💻 Author
**Yuwei Liu**  
University of Bern – Master in Bioinformatics and Computational Biology  
GitHub: [Saul-Gooodman](https://github.com/Saul-Gooodman)
