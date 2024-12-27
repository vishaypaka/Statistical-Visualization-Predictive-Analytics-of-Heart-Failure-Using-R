<h1>Heart Failure Analysis Using Statistical, Visualization & Predictive Analytics</h1>

<p>This repository contains a comprehensive analysis of heart failure data, integrating statistical methods, data visualization, and predictive modeling to uncover meaningful insights and improve prediction accuracy. The project employs machine learning techniques to analyze risk factors associated with heart failure.</p>

<h2>Project Overview</h2>
<p>The dataset (<code>heart_failure_clinical_records_dataset.csv</code>) includes clinical records of 299 heart failure patients, capturing 13 key features such as age, ejection fraction, and serum creatinine. This project focuses on data preprocessing, statistical correlation analysis, and the evaluation of multiple machine learning models to select the most accurate algorithm for predicting heart failure outcomes.</p>

<h2>Key Features</h2>
<ul>
  <li><strong>Data Preprocessing:</strong> 
    <ul>
      <li>Handling missing or null values.</li>
      <li>Transforming skewed variables and scaling numeric predictors.</li>
      <li>Factoring categorical and binary variables.</li>
    </ul>
  </li>
  <li><strong>Statistical and Correlation Analysis:</strong> 
    <ul>
      <li>Summary statistics for predictors and target variable.</li>
      <li>Heatmaps and correlation matrices for understanding relationships between variables.</li>
    </ul>
  </li>
  <li><strong>Machine Learning Models:</strong> 
    <ul>
      <li>Logistic Regression (with scaled and unscaled data).</li>
      <li>Random Forest Classification.</li>
      <li>Decision Trees and K-Nearest Neighbors (KNN).</li>
    </ul>
  </li>
  <li><strong>Visualization:</strong> 
    <ul>
      <li>Boxplots, histograms, and density plots for feature exploration.</li>
      <li>Bar charts to analyze the relationship of risk factors with heart failure outcomes.</li>
    </ul>
  </li>
</ul>

<h2>Technologies Used</h2>
<ul>
  <li><strong>Programming Language:</strong> R</li>
  <li><strong>Libraries:</strong> ggplot2, dplyr, caret, randomForest, corrplot, plotly, and more.</li>
</ul>

<h2>How to Use</h2>
<ol>
  <li>Clone the repository and load the R scripts into RStudio.</li>
  <li>Ensure the dataset <code>heart_failure_clinical_records_dataset.csv</code> is in the specified directory.</li>
  <li>Run the RMarkdown file <code>Final-Project.Rmd</code> to reproduce the analysis and visualizations.</li>
</ol>

<h2>Key Insights</h2>
<ul>
  <li>Features like serum creatinine, ejection fraction, and age are significant predictors of heart failure outcomes.</li>
  <li>Scaling data impacts the performance of some models, but logistic regression yielded 88.9% accuracy with unscaled data.</li>
  <li>Patients with low follow-up periods (<60 days) are at higher risk of mortality.</li>
</ul>

<h2>Future Enhancements</h2>
<ul>
  <li>Expand the dataset with additional clinical features for more robust predictions.</li>
  <li>Explore deep learning models for improved accuracy.</li>
  <li>Integrate survival analysis for time-based predictions of heart failure outcomes.</li>
</ul>

<p>This project demonstrates the integration of statistical, visualization, and predictive analytics techniques to analyze heart failure data, providing actionable insights and decision support for healthcare professionals.</p>
