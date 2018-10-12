# Finding Customer segmentation

In this project I will apply unsupervised learning techniques to identify segments of the population that form the core customer base for a mail-order sales company in Germany. These segments can then be used to direct marketing campaigns towards audiences that will have the highest expected rate of returns. The data that is provided by Bertelsmann Arvato Analytics, and represents a real-life data science task. Methods used for segmenttion after cleaning the data are:

- Kmeans
- Princial component analysis *(PCA)*

The final model successfuly can identify a customer group, who are generally older and have better financial status as primary customer target for Aravato's mail-ordering.

# Dependecies and packages:

- Python 3.x
- Numpy
- Pandas
- Scikit learn
- seaborn
- matplotlib



# Repository content:

- Jupter notebook file: `Identify_Customer_Segments.ipynb`
- html file: a `Identify_Customer_Segments.html` version of *.ipynb
- `kmean30_model.sav` file: containing best model trained with Kmeans with 30 clusters
- `pca70_model.sav` file: contaitning model from PCA with `~70` eigenvectors
- `onehotcode_model.sav` file: containing model after One-Hot coding 
- `standard_scaler_model.sav` file: containing model after normalizing data with Standard scalar
- MIT License file


# Repository content:

Input `csv` file is proprietary to Aravato and is not saved.