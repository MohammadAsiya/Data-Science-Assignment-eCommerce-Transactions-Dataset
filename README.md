# ZeoTap Internship Assignment: Data Science Project   

## Project Overview  
This repository contains the solution to the **Data Science Assignment: eCommerce Transactions Dataset** provided by ZeoTap as part of the internship recruitment process. The goal of this project was to analyze eCommerce transaction data and build models for customer segmentation and lookalike recommendations. The project was completed with a focus on data exploration, clustering, and customer profiling.

---

## Repository Contents  
1. **`Asiya_Mohammad_Clustering.ipynb`**  
   - A Jupyter Notebook containing the code and steps for clustering analysis on the eCommerce dataset.  
   - The Clustering notebook implements unsupervised learning techniques to segment customers into different groups based on their transaction behavior. Techniques applied include:
    K-Means Clustering: To identify distinct customer groups based on purchasing patterns.
2. **`Asiya_Mohamnad_Clustering.pdf`**  
   - Results and insights from Asiya_Mohammad_Clustering analyses are detailed in the Clustering PDF.
3. **`Asiya_Mohammad_EDA.ipynb`**  
   - A Jupyter Notebook containing the Exploratory Data Analysis (EDA) performed on the eCommerce dataset.  
   - The notebook covers data cleaning, summary statistics, visualizations, and insights derived from customer, product, and transaction data.

4. **`Asiya_Mohammad_EDA.pdf`**  
   - The 5 business insights derived from the EDA as asked for.  

5. **`Asiya_Mohammad_Lookalike.csv`**  
   - The output file for the lookalike model, containing mappings of customer IDs to their top 3 similar customers and the associated similarity scores.  
   - **Format**: `Map<cust_id, List<cust_id, score>>`  

6. **`Samuel_Valla_Lookalike.ipynb`**  
   - The Lookalike notebook focuses on identifying potential lookalike customers for targeted marketing campaigns. The model leverages customer attributes to find similar profiles, enhancing marketing effectiveness by targeting high-potential segments.

---

## Project Highlights  
- **Exploratory Data Analysis (EDA)**:  
   - Comprehensive cleaning and visualization of customer, product, and transaction datasets.  
   - Insights into customer regions, product popularity, and monthly transaction trends.  

- **Customer Segmentation (Clustering)**:  
   - Implementation of clustering algorithms with a focus on finding the optimal number of clusters.  
   - Evaluated clustering performance using Davies-Bouldin Index (DB Index) and Silhouette Scores.  
   - Visualized clusters using PCA for interpretability.  

- **Lookalike Modeling**:  
   - Built a model to identify the top 3 similar customers for each given customer based on profile and transaction history.  
   - Generated similarity scores for recommendations and exported results to a CSV file.  

---
Tools Used: Python, Jupyter Notebook, Pandas, Matplotlib, Scikit-learn
---
## Results and Conclusion:

The findings from the analysis, including clustering results, insights from EDA, and potential marketing strategies based on lookalike analysis,
