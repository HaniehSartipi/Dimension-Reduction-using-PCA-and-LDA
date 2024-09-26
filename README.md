# Dimension-Reduction-using-PCA-and-LDA
In this analysis, I applied Principal Component Analysis (PCA) and Linear Discriminant Analysis (LDA) on the Breast Cancer dataset to classify tumors as benign or malignant. My primary classifier was the Random Forest, which yielded the best performance when combined with PCA.
The dataset exhibited multicollinearity, particularly among features such as radius_mean, perimeter_mean, and area_mean. This correlation can introduce redundancy and complicate model interpretation.
I employed forward selection for feature selection, incrementally adding variables to the model. Notably, accuracy plateaued after incorporating the second feature, allowing me to achieve an impressive 94% accuracy using only these two informative features.
After standardizing the data, PCA analysis revealed that the first principal component captured most of the variance. However, I found that utilizing two principal components provided clear separation between cancerous and healthy patients, enhancing classification performance.

