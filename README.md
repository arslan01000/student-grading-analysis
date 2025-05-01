# Student Grading Dataset – Clustering Analysis

This project explores the **Students Grading Dataset** from Kaggle using data preprocessing and unsupervised learning techniques to uncover patterns in student performance.

## 📁 Dataset
Features include:
- Hours Studied
- Attendance
- Participation
- Previous Grades
- Final Grade

## 🧹 Data Preprocessing
- **Data Cleaning**: Removed missing and duplicate values
- **Normalization**: Min-Max Scaling
- **Dimensionality Reduction**: PCA (reduced to 2 components for clustering visualization)
- **Regression**: Linear regression to assess correlations

## 🤖 Modeling
Applied **K-Means Clustering (k=3)** on PCA-reduced data to identify:
- High-performing students
- Average-performing students
- At-risk students

## 📊 Output Files
- `student_grading_clusters.csv`: Clustered data with PCA
- `kmeans_pca_plot.png`: Visual representation of 3 clusters
- `Final_Report_StudentGrading.pdf`: Summary report of methods and findings

## 🔗 Report
Read the final project report [here](Final_Report_StudentGrading.pdf)

## 🧠 Conclusion
Clustering revealed meaningful student groups that can be used for academic support strategies. PCA improved interpretability, and regression confirmed that study habits and past performance strongly influence final outcomes.

---

