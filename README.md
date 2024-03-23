# Dimensionality-Reduction-using-PCA-on-Heart-Attack-Dataset
<p>This project focuses on applying Principal Component Analysis (PCA) for dimensionality reduction on the Heart Attack dataset. The dataset contains features related to various factors that may contribute to the likelihood of a heart attack.</p>

### Overview  
**The process involves the following steps:**  

`Data Preprocessing:`
Loading the dataset using pandas.  
Encoding the target variable using LabelEncoder.  
Splitting the dataset into training and testing sets.  

`Model Building (Without PCA):`  
Training a Decision Tree Classifier on the original dataset.  
Evaluating the model's performance on training and testing sets.  
Displaying classification report and confusion matrix.  

`Data Preprocessing for PCA:`  
Scaling the features using StandardScaler.  
Applying PCA to reduce the dimensionality of the dataset to 2 principal components.  

`Model Building (With PCA):`  
Training a Decision Tree Classifier on the PCA-transformed dataset.  
Evaluating the model's performance on training and testing sets.  
Displaying classification report and confusion matrix.  
