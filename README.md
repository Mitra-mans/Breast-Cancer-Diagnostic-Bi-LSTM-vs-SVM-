This project was done in collaboration with Lord Kavi, Prangya Parida, and Masoomeh Akbari. It focuses on leveraging machine learning (ML) to enhance the accuracy of Breast Cancer Diagnosis, a critical aspect in the fight against one of the leading causes of mortality among women. Accurate and timely diagnosis is essential to improving treatment outcomes and saving lives.
Methodology and Dataset Features

The methodology involves a systematic approach that includes data preprocessing, feature engineering, model development, and evaluation. The dataset consists of 30 features, categorized into three types of measurements:

    Mean: Average value of each feature.
    Standard Error (SE): Variability in the feature values.
    Worst: Extreme values (mean of the three largest nuclei measurements).

The features describe various properties of cell nuclei and are grouped into categories such as size (radius, area, perimeter), shape (smoothness, compactness, concavity, concave points), and texture (symmetry, fractal dimension). These features are crucial in distinguishing between benign and malignant tumors.

A diverse set of machine learning models was employed, including K-Nearest Neighbors (KNN), Support Vector Machines (SVM), Random Forests, Decision Trees, and Logistic Regression, with hyperparameter tuning to optimize performance. Additionally, ensemble methods and a deep learning neural network were implemented to capture complex relationships in the data.
Results

The results demonstrate significant improvements in diagnostic accuracy:

    Support Vector Machines achieved the highest accuracy of 98% among the classical models.
    Deep Learning Neural Network produced an accuracy of 95.61% after 100 epochs, showcasing its ability to generalize effectively.

Feature importance analysis highlighted key predictors such as "concave points" and "texture," which play a significant role in distinguishing between tumor types. This project not only emphasizes the potential of machine learning and deep learning in medical diagnostics but also offers a user-friendly tool for healthcare professionals to enhance decision-making and improve patient outcomes.
