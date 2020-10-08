# Summmary: Feature Engineering in Pyspark



<p>
Data sets consistings of millions and more observations are exceeding the capacities of a single machine. Based on the Hadoop distributed file system Apache Spark offers a solution for processing large, big data sets by building a virtual machine managing file chunks on distributed worker nodes. The goal here is to apply methods for preparing, cleaning and optimizing data sets. This support a smooth execution with good performance.
</p>

<p>
This project focuses on <b>Feature Engineering in Pyspark</b>. At the end some models are developed and algorithms applied, but this is not the main point. It is more to round up the project.
</p> 


<p>
For getting a better understanding a glossary of common terms is provided below:
</p> 

<p>
<b>Feature Engineering</b><br>
"Feature engineering is the process of using domain knowledge to extract features from raw data via data mining techniques. These features can be used to improve the performance of machine learning algorithms. Feature engineering can be considered as applied machine learning itself."<br>
<a href="https://en.wikipedia.org/wiki/Feature_engineering" target="_blank">Wikipedia</a> 
</p> 

<p>
<b>Feature selection</b><br>
"In machine learning and statistics, feature selection, also known as variable selection, attribute selection or variable subset selection, is the process of selecting a subset of relevant features (variables, predictors) for use in model construction. The central premise when using a feature selection technique is that the data contains some features that are either redundant or irrelevant, and can thus be removed without incurring much loss of information."<br>
<a href="https://en.wikipedia.org/wiki/Feature_selection" target="_blank">Wikipedia</a> 
</p> 

<p>
<b>Feature extraction</b><br>
"In machine learning, pattern recognition and in image processing, feature extraction starts from an initial set of measured data and builds derived values (features) intended to be informative and non-redundant, facilitating the subsequent learning and generalization steps, and in some cases leading to better human interpretations. Feature extraction is related to dimensionality reduction."<br>
<a href="https://en.wikipedia.org/wiki/Feature_extraction" target="_blank">Wikipedia</a> 
</p> 


<p>
Some topics and methods applied here in the context of feature engineering are in this project:
</p> 

<ul>
  <li>importing</li>
  <li>setting up Spark</li>
  <li>exploring RDDs</li>
  <li>exploring pyspark.sql.dataframes</li>
  <li>Parquet files</li>
  <li>data visualizations</li>
  <li>Spark.sql</li>
  <li>statistics</li>
  <li>outliers</li>
  <li>data cleaning</li>
  <li>missing values</li>
  <li>Helper functions</li>
  <li>UDFs</li>
  <li>feature scaling</li>
  <li>statistics</li>
  <li>outliers</li>
  <li>data cleaning</li>
  <li>user defined function</li>
  <li>feature scaling</li>
  <li>log transformation</li>
  <li>joining</li>
  <li>feature engineering by creating new features<br>
      from existing ones</li>
  <li>new features from time data<br>
      from existing ones</li> 
  <li>extracting new features from substrings</li> 
  <li>Yes / no filters with binarizing</li> 
  <li>OneHotEncoderEstimator</li>
  <li>Machine learning with pyspark.ml</li>
</ul> 

<p>
There are two data set used here is the real estate data set with the
target variable sales close price. The given label makes the data set
suitable for supervised machine learning.
</p> 
