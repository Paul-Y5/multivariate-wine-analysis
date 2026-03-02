# Multivariate Exploratory Analysis - Wine Quality Dataset

**Course:** IAA  
**Academic Year:** 2025/2026  
**Degree:** Computer Science Engineering - 3rd Year  
**University of Aveiro**  
**Paper Theme:** *"Multivariate Exploration: Beyond Pairwise Analysis"*

## Description

This project was developed as part of the IAA course for writing an academic paper on the theme **"Multivariate Exploration: Beyond Pairwise Analysis"**. The work explores multivariate exploratory analysis techniques applied to the Wine Quality Dataset. The main objective is to demonstrate how multivariate methods reveal global patterns in the data that are not visible through traditional pairwise analysis.

## Objectives

- Compare traditional pairwise analysis vs. multivariate analysis
- Apply PCA (Principal Component Analysis) for dimensionality reduction
- Identify natural clusters in the data using K-means
- Visualize complex multidimensional structures
- Interpret loadings and principal components

## Dataset

**Wine Quality Dataset**
- Source: UCI Machine Learning Repository
- Samples: 6497 wines (1599 red + 4898 white)
- Variables: 11 physicochemical attributes + quality (target)
- Type: Real data from Portuguese wines (Vinho Verde)

### Analyzed Variables
1. Fixed acidity
2. Volatile acidity
3. Citric acid
4. Residual sugar
5. Chlorides
6. Free sulfur dioxide
7. Total sulfur dioxide
8. Density
9. pH
10. Sulphates
11. Alcohol
12. Quality (score 0-10)

## Technologies Used

- **Python 3.x**
- **Jupyter Notebook**
- **pandas** - Data manipulation
- **numpy** - Numerical operations
- **matplotlib & seaborn** - Visualization
- **scikit-learn** - PCA, K-means, StandardScaler
- **scipy** - Hierarchical clustering

## How to Run

1. **Clone the repository:**
   ```bash
   git clone https://github.com/YOUR_USERNAME/multivariate-wine-analysis.git
   cd multivariate-wine-analysis
   ```

2. **Install dependencies:**
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn scipy jupyter
   ```

3. **Run the notebook:**
   ```bash
   jupyter notebook multivariate_exploration.ipynb
   ```

## Main Results

### Pairwise Analysis (Traditional)
- Individual correlations between variables
- 2D scatter plots
- Limitations: does not capture global structure

### Multivariate Analysis
- **PCA:** Reduction from 11D → 3-4D while maintaining 80-85% of variance
- **Clustering:** Identification of 4 natural groups
- **Separation:** Clear distinction between red and white wines in multivariate space
- **Insight:** Quality depends on combinations of properties, not isolated metrics

## Concepts Learned

- Dimensionality reduction with PCA
- Interpretation of loadings and biplots
- K-means clustering and elbow method
- Hierarchical analysis (dendrograms)
- Multidimensional data visualization
- Difference between pairwise correlation and multivariate structure

## Author

Computer Science Engineering Student  
University of Aveiro

## Notes

This project was developed for academic purposes as part of the evaluation for the IAA course. The analysis and visualizations presented here support the paper **"Multivariate Exploration: Beyond Pairwise Analysis"**, which compares traditional pairwise exploratory techniques with advanced multivariate methods.

## License

This project is licensed under the **MIT License** - See the [LICENSE](LICENSE) file for details.

**Academic Use:** This work may be freely used, modified, and distributed for educational and research purposes, provided proper attribution is given.
