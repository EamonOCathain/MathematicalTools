<h1 style="font-size:32px;">Lizard Dataset Analysis Project</h1>

<h2 style="font-size:24px;">Project Overview</h2>
<p style="font-size:16px;">
This project focuses on analyzing a dataset of lizard species (<code>lizard.csv</code>) to explore their life history traits in asscociation with environmental drivers using advanced statistical and machine learning techniques. The project involves Principal Component Analysis (PCA), Random Forest modeling, and unsupervised learning approaches to uncover patterns and relationships within the data.
</p>
<p style="font-size:16px;">
The repository contains R Markdown files (<code>.Rmd</code>) for conducting and documenting the analysis, as well as associated outputs in HTML format.
</p>

<h2 style="font-size:24px;">Folder Structure and Files</h2>

<h3 style="font-size:20px;">Main Files</h3>
<ul style="font-size:16px;">
  <li><strong>FinalAnalysis.Rmd:</strong> The main analysis script containing data cleaning, PCA, correlation matrix, random forest modeling, and visualization code. Final output is an HTML document with results.</li>
  <li><strong>lizard.csv:</strong> The primary dataset containing lizard-related data, including species traits like clutch frequency, habitat type, and body size.</li>
  <li><strong>Eamon'sSketch.Rmd / Rich_Sketch.Rmd:</strong> The working scripts of each team member to avoid overlapping changes while working on the script at the same time.</li>
  <li><strong>Eamon'sOld.Rmd:</strong> A previous version of the working script.</li>
  <li><strong>MathematicalTools.Rproj:</strong> RStudio project file to organize and manage the working directory for this analysis.</li>
  <li><strong>Clobert et al., 1998.pdf:</strong> A relevant reference used to guide the project.</li>
</ul>

<h2 style="font-size:24px;">Methods and Techniques</h2>
<p style="font-size:16px;">
This project applies several statistical and machine learning techniques using the R programming language:
</p>
<ul style="font-size:16px;">
  <li><strong>Data Cleaning:</strong> Removal of duplicates and handling missing values. Conversion of variables to appropriate data types for analysis.</li>
  <li><strong>Principal Component Analysis (PCA):</strong> Reduces dimensionality and highlights key variables influencing species differences. Visualized using biplots and scree plots.</li>
  <li><strong>Random Forest Modeling:</strong> Predicts clutch frequency based on species traits. Evaluates model accuracy and identifies important predictors.</li>
  <li><strong>Correlation Analysis:</strong> Examines relationships between numeric variables to identify redundancy or strong correlations.</li>
  <li><strong>Unsupervised Learning:</strong> Clustering techniques to explore hidden patterns and groupings within the data.</li>
</ul>

<h2 style="font-size:24px;">Requirements</h2>
<h3 style="font-size:20px;">Software</h3>
<ul style="font-size:16px;">
  <li><strong>RStudio:</strong> For running R Markdown files and managing the project.</li>
  <li><strong>LaTeX (optional):</strong> For generating PDF outputs from <code>.Rmd</code> files.</li>
</ul>

<h3 style="font-size:20px;">R Libraries</h3>
<p style="font-size:16px;">
The following libraries are used in the analysis and must be installed:
</p>
<pre style="font-size:14px; background-color:#f8f8f8; padding:10px; border-radius:4px;">
install.packages(c("tidyverse", "corrplot", "FactoMineR", "factoextra", 
                   "vegan", "ggplot2", "rsample", "rpart", 
                   "rpart.plot", "randomForest"))
</pre>

<h2 style="font-size:24px;">Usage</h2>
<h3 style="font-size:20px;">Set Up</h3>
<ul style="font-size:16px;">
  <li>Clone the repository and open the <code>MathematicalTools.Rproj</code> file in RStudio.</li>
  <li>Ensure all required packages are installed.</li>
</ul>

<h3 style="font-size:20px;">Run Analysis</h3>
<ul style="font-size:16px;">
  <li>Open <code>Analysis.Rmd</code>.</li>
  <li>Knit the file to generate an HTML or PDF report with results.</li>
</ul>

<h3 style="font-size:20px;">Explore Results</h3>
<ul style="font-size:16px;">
  <li>View output file <code>Analysis.nb.html</code> for detailed results and visualizations.</li>
</ul>

<h2 style="font-size:24px;">Key Contributions</h2>
<ul style="font-size:16px;">
    <li><strong>Data Cleaning:</strong> Ensures high-quality data by removing duplicates, converting variables to appropriate types, and handling missing values effectively.</li>
  <li><strong>Correlation Analysis:</strong> Identifies relationships and redundancy among numeric variables, guiding feature selection and interpretation.</li>
  <li><strong>Principal Component Analysis (PCA):</strong> Highlights the key variables influencing species differences and reduces dimensionality for clearer visualization and clustering.</li>
  <li><strong>Clustering Analysis:</strong> Uses unsupervised learning methods to uncover hidden patterns and groupings within the data.</li>
  <li><strong>Random Forest Modeling:</strong> Develops a predictive model for clutch frequency, evaluates model accuracy, and identifies the most important predictors influencing the outcome.</li>
  <li><strong>Visualization:</strong> Generates informative plots, including correlation heatmaps, PCA biplots, and Random Forest variable importance charts, to present findings clearly and effectively.</li>
</ul>


<h2 style="font-size:24px;">How to Contribute</h2>
<ul style="font-size:16px;">
  <li>Fork the repository and create a new branch.</li>
  <li>Make your changes or additions (e.g., improve code, add new analyses).</li>
  <li>Submit a pull request with a description of your changes.</li>
</ul>

<h2 style="font-size:24px;">Acknowledgments</h2>
<ul style="font-size:16px;">
  <li><strong>Clobert et al., 1998:</strong> Referenced as part of the biological context for the analysis.</li>
  <li>Teaching and guidance from: </li>
  <ul style="font-size:16px; padding-left:30px;">
  <li>Eric Macron <strong>(R Markdown)</strong></li>
  <li>Lucia Clarotto <strong>(Mathematical Tools)</strong></li>
<li>Reseracher X <strong>(LaTex)</strong></li>
<li>Reseracher Y <strong>(Zotero)</strong></li>
</ul>

</ul>
