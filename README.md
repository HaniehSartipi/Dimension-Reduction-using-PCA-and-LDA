# Dimension-Reduction-using-PCA-and-LDA
Applied PCA and LDA on the Breast Cancer dataset and used a Random Forest Classifier to classify cancer as benign or malignant. Achieved the best results with the PCA & Random Forest model combination.
The dataset shows multicollinearity, with variables like radius_mean, perimeter_mean, and area_mean being highly correlated. We reduce dimensions by removing highly correlated variables and applying PCA or LDA.
Feature Selection: Using forward selection, we add variables to the model one by one. Accuracy plateaus after the second feature, so we stop, achieving 94% accuracy with just two features.
PCA: After standardizing the data, PCA shows that most variance is explained by the first component, but two components provide clear separation between cancerous and healthy patients.
LDA and Classification: LDA combined with a Random Forest classifier gives the best performance. The forward selection approach also performs well with two features, making it a viable option.
